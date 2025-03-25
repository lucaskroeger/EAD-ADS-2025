# Documentação de Modificações no Projeto

Este documento descreve as modificações realizadas no projeto, desde renomeações de arquivos até ajustes no código.

---

## **Alterações no Projeto**

### **1. Renomeação de Arquivos e Pastas**
- **index.HTML** renomeado para **index.html** (removendo a extensão em maiúsculo).
- **styles.CSS** renomeado para **styles.css** (removendo a extensão em maiúsculo).
- **assets/Img** renomeado para **assets/img** (removendo a inicial maiúscula).
- **paginas** renomeada para **pages**.
- **REDMIR.md** renomeado para **README.md**.
- **contato.html** renomeado para **contact.html**.

### **2. Alterações no Estrutural de Pastas**
- **scripts2** foi apagada junto com o arquivo **scriptExtra.js**, pois não era utilizado no projeto.
- **js/scripts1.js** foi movido para a pasta **scripts** e renomeado para **userManagement.js**.
- **js** foi apagada, pois já estava vazia.

---

## **Alterações nos Arquivos HTML**

### **1. index.html**
- **Remoção da tag `<center>`**: A tag `<center>` foi removida, pois não existe mais em HTML5.
- **Movimento de scripts**: O script foi movido para dentro da tag `<body>`, seguindo boas práticas de carregamento de scripts.
- **Adição de `<label>` para o formulário**: A tag `<label>` foi corretamente adicionada para melhorar a acessibilidade.
- **Estruturação com `<section>` e `container`**: A página foi colocada dentro de uma `section` com a classe `container` para melhor organização e estilo.
- **Remoção de botão redundante**: O botão "Adicionar" que estava sobrando foi removido.
- **Alteração da tag de "Usuários Cadastrados"**: A tag foi alterada de `<h6>` para `<h1>`.
- **Correção de maiúsculas e acentuação**: Ajustes realizados para garantir uma melhor legibilidade e consistência no texto.
- **Troca do script de troca de página**: O script foi substituído por uma tag `<a>` para navegação.

### **2. contact.html**
- **Troca do script de troca de página por uma tag `<a>`**: O script foi substituído por uma tag `<a>` para facilitar a navegação entre páginas.
- **Alteração da página de destino do botão**: O botão agora leva corretamente para **index.html**.
- **Adição de `<label>` para mensagem**: A tag `<label>` foi adicionada ao campo de mensagem para garantir a acessibilidade.

### **3. Remoção do Arquivo Sobre.html**
- O arquivo **Sobre.html** foi removido, pois não havia rota para ele no projeto.

---

## **Alterações no Arquivo CSS (styles.css)**

- **Adição de margem nos botões**: Foi adicionada uma margem nos botões para melhorar a estética e o espaçamento.
- **Ajuste na margem do container**: A margem do container foi ajustada para melhorar o layout da página.

---

## **Alterações no Arquivo `utilsScript.js`**

- **Ajuste de identação**: A identação do código foi corrigida para melhorar a legibilidade e facilitar a manutenção.
- **Remoção da variável `const form = document.getElementById("myForm");`**: Essa variável foi removida, pois não estava sendo utilizada no código.

---

## **Alterações no Arquivo `userManagement.js`**

- **Remoção de comentário**: O comentário de advertência que estava no código foi removido, pois não era necessário.

---

## **Adições**

- **Adição da imagem `jec-logo.png`**: A imagem foi adicionada ao projeto para ser usada como ícone da página.

---

## **Resumo das Alterações**

1. **Arquivos renomeados** para melhorar a consistência (com extensão em minúsculo).
2. **Pasta `scripts2` foi apagada**, removendo código não utilizado.
3. **Refatoração de código HTML** para melhorar a estrutura, acessibilidade e a navegação.
4. **Ajustes no CSS** para melhorar a estética, como margens e ajustes nos botões.
5. **Refatoração de JavaScript** para melhorar a organização e eliminar código desnecessário.
6. **Remoção de arquivos não utilizados**, como o **Sobre.html**.

---

Essa documentação descreve as alterações realizadas no código-fonte do projeto, com o objetivo de melhorar a organização, a manutenção e a consistência do código.

Se precisar de mais ajustes ou explicações, estou à disposição!
