# Git e GitHub: um guia de sobrevivência básico	
Hey, aqui temos um resumo do básico para sua sobrevivência como developer!

* [Comandos básicos](#-comandos-básicos)

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