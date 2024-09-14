# Git e GitHub: um guia de sobrevivência básico	
👀 Hey, aqui temos um resumo do básico para sua sobrevivência como developer!

* [🚀Comandos básicos](#-comandos-básicos)
* [💻Links Úteis](#links-úteis)

## 🚀 Comandos básicos

1. Para instalar o repositório, digite em seu GIT BASH:

```
git init
```

2. Para ver quais **arquivos foram modificados**:

```
git status
```

3. Para **adicionar arquivos** para um futuro commit:

```
git add nome-do-arquivo.ext
```

- Para adicionar todos os arquivos modificados a um commit:

```
git add .
```

4. Para **commitar** seus arquivos:

```
git commit -m "sua-mensagem"
```
- Commits semânticos: https://github.com/iuricode/padroes-de-commits
  

5. Para criar sua **branch** main
```
git branch -M main
```

6. Para **ligar** seu repositório local ao **remoto**
```
git remote add origin https://github.com/seu-user/seu-repositorio
```

7. Clonar um repositório:
```
git clone url-do-repositorio
```

8. Atualizar seu repositório das modificações:
```
git pull origin main
git pull
```

9. Subir as modificações realizadas em seu repositório para o github:
```
git push origin main
git push
```

8. Criar/Ir pra uma branch
```
git branch -M main
git checkout nome
git checkout -b nome
```

## 💻 Links Úteis
### Prática 01
```
https://github.com/new

https://github.com/leticiazlopes/guia-basico-git.git

git commit -m ":sparkles: feat: Página de Currículo"

git commit -m ":books: docs: Atualização do README"

```

### Prática 02
```
https://github.com/ifpb/projects

https://github.com/ifpb/projects/tree/main/src/content/people

```