# 🚀 Galeria da Nossa Comunidade | Turma de Git & GitHub

Seja bem-vindo(a) ao repositório colaborativo da nossa turma! 

Este projeto foi criado para você colocar em prática os primeiros comandos de **Git** e **GitHub**, aprendendo como contribuir em um projeto real através de branches e *Pull Requests*.

---

## 💻 Sobre o Projetinho

Uma página web simples e estilosa onde cada estudante tem o seu próprio "card" de perfil. O objetivo é que **cada aluno adicione o seu nome e uma mensagem** no arquivo `index.html`.

---

## 🛠️ Como Contribuir (Passo a Passo)

Siga as instruções abaixo no seu terminal para adicionar seu card na galeria:

### 1. Clonar o projeto na sua máquina
Se você ainda não clonou o repositório, rode:
```bash
git clone <URL_DO_NOSSO_REPOSITORIO>
cd aula-git-turma-58
```

### 2. Criar uma nova branch
Nunca faça alterações diretamente na branch principal! Crie uma branch com o seu nome:

```bash
git checkout -b minha-branch-seu-nome
```
### 3. Adicionar o seu card no index.html
Abra o arquivo index.html no seu editor de código (VS Code).

Vá até o final do bloco ```<main class="container">. ```

Copie o trecho abaixo, cole no final da lista e preencha com as suas informações:

```HTML
<!-- Copie a partir daqui -->
<article class="card">
    <div class="profile-header">
        <div class="avatar">S</div> <!-- Primeira letra do seu nome -->
        <h2 class="user-name">Seu Nome</h2>
    </div>
    <p>Sua frase ou mensagem motivacional aqui!</p>
</article>
```
Salve o arquivo (Ctrl + S ou Cmd + S).

### 4. Enviar suas alterações
No terminal, digite os seguintes comandos:


#### 1. Prepara os arquivos alterados
```bash
git add index.html
```

#### 2. Registra o que foi feito
```
git commit -m "feat: adiciona card de [Seu Nome]"
```

#### 3. Envia a sua branch para o GitHub
``` git push origin minha-branch-seu-nome ```

### 5. Abrir o Pull Request (PR)
- Acesse a página do repositório no GitHub.

- Clique no botão verde "Compare & pull request" que aparecerá no topo.

- Adicione um título legível e clique em "Create pull request".

- Aguarde a validação e o aceite da professora! 🎉

# 🎓 Tecnologias Utilizadas
- HTML5

- CSS3

- Git & GitHub
