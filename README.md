# Projeto X Clone - 1/42% do antigo Twitter

## Descrição

Este é um projeto de clone parcial da rede social **X** (anteriormente conhecida como Twitter), desenvolvido com **Spring Boot**. O objetivo é implementar funcionalidades básicas da plataforma, representando 1/42% da experiência completa da rede social. Este projeto tem fins educacionais e serve como um estudo de arquitetura de sistemas, design de APIs e integração de módulos.

---

## Funcionalidades Previstas

### Funcionalidades Implementadas (1/42%):
- **Postagem de Tweets:**
  - Permitir que usuários publiquem mensagens curtas ("tweets") de até 280 caracteres.
- **Visualização de Timeline:**
  - Exibir os tweets mais recentes postados pelos usuários seguidos.
- **Criação de Perfil de Usuário:**
  - Cadastro de usuário com nome, username, e-mail e senha.

### Funcionalidades Futuras:
- Retweets e Curtidas.
- Sistema de Seguidores e Seguindo.
- Notificações Simples.
- Hashtags e Mççoes.

---

## Tecnologias Utilizadas

- **Backend:** Spring Boot (versão mais recente)
- **Banco de Dados:** PostgreSQL
- **Segurança:** Spring Security com JWT
- **APIs:** RESTful APIs
- **Testes:** JUnit e Mockito
- **Documentação:** Swagger/OpenAPI

---

## Requisitos de Sistema

- **Java:** Versão 17 ou superior
- **Maven:** Versão 3.8+
- **PostgreSQL:** Versão 13+

---

## Instalação e Configuração

### 1. Clone o repositório:
```bash
$ git clone https://github.com/seu-usuario/x-clone.git
```

### 2. Configure o banco de dados:
Crie um banco de dados PostgreSQL com o nome `x_clone`.
Atualize o arquivo `application.properties` com suas credenciais:
```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/x_clone
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha
spring.jpa.hibernate.ddl-auto=update
```

### 3. Compile e rode o projeto:
```bash
$ mvn clean install
$ mvn spring-boot:run
```

### 4. Acesse a aplicação:
Abra o navegador e acesse: [http://localhost:8080](http://localhost:8080)

---

## Estrutura do Projeto

```plaintext
src/
├── main/
│   ├── java/
│   │   ├── com.example.xclone/
│   │       ├── controller/
│   │       ├── service/
│   │       ├── repository/
│   │       ├── model/
│   │       └── config/
│   └── resources/
│       ├── application.properties
│       └── data.sql
└── test/
```

---

## Contribuições

Contribuições são bem-vindas! Para colaborar:
1. Fork o repositório.
2. Crie uma branch para sua funcionalidade (`git checkout -b minha-funcionalidade`).
3. Submeta seu PR com uma descrição detalhada.

---

## Licença

Este projeto está licenciado sob a MIT License - veja o arquivo LICENSE para mais detalhes.

---

## Contato

Em caso de dúvidas ou sugestões, entre em contato:
- **Nome:** Seu Nome
- **E-mail:** seuemail@example.com
- **LinkedIn:** [linkedin.com/in/seu-perfil](https://linkedin.com/in/seu-perfil)
