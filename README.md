# Sistema de Gerenciamento de Produtos 🛠️

Este projeto é um sistema completo para o gerenciamento de produtos. Desenvolvido com **Java Spring Boot** no backend e **HTML, CSS e JavaScript** no frontend, permite realizar operações CRUD (criar, ler, atualizar e deletar produtos) com funcionalidades adicionais, como mensagens de sucesso e validação. A aplicação foi projetada para ser escalável e modular.

## Funcionalidades Principais 🚀

- **Adicionar Produto**: Cadastro de novos produtos, incluindo nome, quantidade, preço e descrição.
- **Listar Produtos**: Exibição de uma tabela com todos os produtos cadastrados.
- **Editar Produto**: Alteração de informações de produtos existentes.
- **Excluir Produto**: Remoção de produtos, com confirmação por modal.
- **Integração Frontend-Backend**: Comunicação direta entre o frontend e o backend usando **Fetch API**.

## Demonstração em Vídeo 🎥

https://github.com/arthur810FR/backend-almoxarifado/issues/1#issue-2754835461

## Tecnologias Utilizadas 🛠️

### Backend:
- **Java 17**
- **Spring Boot 3.2.1**
- **MySQL**

### Frontend:
- **HTML5**
- **CSS3**
- **JavaScript**

## Estrutura do Projeto 📁
### Backend:
```plaintext
src/
├── main/
│   ├── java/
│   │   └── com.inc.almoxarifado/
│   │       ├── controller/
│   │       │   └── ProdutoController.java
│   │       ├── exceptions/
│   │       │   ├── GlobalExceptionHandler.java
│   │       │   └── ResourceNotFoundException.java
│   │       ├── model/
│   │       │   └── Product.java
│   │       ├── repository/
│   │       │   └── ProductRepository.java
│   │       └── service/
│   │           ├── ProductService.java
│   │           └── impl/
│   │               └── ProductServiceImpl.java
│   ├── resources/
│   │   ├── application.properties
│   │   ├── data.sql
│   │   └── schema.sql
└── pom.xml
```
### Frontend:
```plaintext
├── index.html
├── style.css
└── app.js
```
## Executando o Projeto ▶️

### Backend:
1. Clone este repositório:
   ```bash
   git clone https://github.com/arthur810FR/almoxarifado--api.git
   ```
2. **Navegue até o diretório do projeto**

3. **Abra o projeto na sua IDE e execute as classe AlmoxarifadoApplication para o projeto rodar.**

4. **A API estará disponível na porta configurada no VScode, seja padrão ou definida a gosto, como por exemplo: "http://127.0.0.1:5500", "http://localhost:5500".**

### Frontend:

1. Clone o repositório do frontend:
   ```bash
   git clone https://github.com/arthur810FR/front-almoxarifado.git
   ```
2. Abra o arquivo index.html no VSCode e clique com um botão direito e selecione a opção Live Server(Instale a dependência no VSCode).

3. O repositório frontend pode ser acessado diretamente através do link:

[Frontend - Sistema de Gerenciamento de Produtos](https://github.com/arthur810FR/front-almoxarifado)

## Validações e Tratamento de Exceções ⚠️

O backend utiliza validações robustas para garantir a integridade dos dados:

- **Campos obrigatórios**: Nome, quantidade, preço e descrição devem ser fornecidos.
- **Mensagens amigáveis**: Exibição de mensagens claras para o usuário em caso de erros.
- **CORS configurado**: Permite comunicação entre frontend e backend.

## Exemplo de Uso 🖥️

### Adicionar Produto:
1. Preencha os campos no formulário e clique em **"Salvar"**.
2. O produto será exibido na tabela.

### Editar Produto:
1. Clique em **"Editar"** no produto desejado.
2. Atualize as informações e clique em **"Salvar"**.

### Excluir Produto:
1. Clique em **"Deletar"**.
2. Confirme a exclusão no modal.

## Melhorias Futuras 💡

- Implementação de autenticação e autorização.
- Adicionar paginação na listagem de produtos.
- Melhorias no design responsivo.

## 📞 Contato
**Arthur Francisco Guedes Azevedo**

- [LinkedIn](https://www.linkedin.com/in/arthur-azevedo-desenvolvedor/)
- [Email](mailto:arthurfranciscoazevedo@gmail.com)
