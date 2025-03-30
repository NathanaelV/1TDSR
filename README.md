# 1TDSR

## Recomendações de atualizações:

### No terminal

1. Fazer o clone na sua máquina

```bash
git clone git@github.com:Japitu/1TDSR.git
```

2. Entrar na pasta 1TDSR

```bash
cd 1TDSR
``` 

3. Caso já tenha a pasta na sua maquina, antes de começar a trabalhar, certifique-se de que está na `main`, faça um Pull do repositório:

```bash
git pull
```

Assim irá atualizar o seu repositório local com o repositótio no GitHub

4. Criar uma branch para trabalhar na atualização. O nome da branch tem a ver com a tarefa que será feita

``` bash
git checkout -b <nome-da-sua-branch>
```

5. Faça as alterações necessárias. Após terminar, faça o commit 

```bash
git add .
git commit -m 'Nome da mensagem'
```

6. Fazer o push para o repositório, porém pela branch que foi criada. Não volte para `main`.

```bash
git push origin <nome-da-sua-branch>
```

7. Após **finalizar** o passo 8 do processo do **GitHub**. Volte para a `main` e pode apagar a branch onde estava trabalhando.

```bash
git checkout main
git branch -D <nome-da-sua-branch>
```
<br>

---

### No GitHub

1. Acesse o repositório no GitHub. Após fazer o push verá a tela abaixo. Clique em **Compare & pull request**.

![alt text](image.png)

2. Prencha o título e adicione uma descrição se achar necessário

3. Solicite a revisão de um dos responsáveis

![alt text](image-1.png)

4. Só clicar em **Create pull request**.

5. Aguarde a aprovação do PR (Pull Request):

![alt text](image-4.png)

6. Clique em **Squash and merge** para fazer o Merge.

![alt text](image-2.png)

![alt text](image-3.png)

7. Caso queira, pode alterar a mensagem do commit do merge ou adicionar um descrição. Após isso, só confirmar o merge.

![alt text](image-5.png)

8. Se tudo der certo, verá uma tela parecida com a que está abaixo. Significa que deu tudo certo. Pode clicar em **Deletar branch**.

![alt text](image-6.png)

