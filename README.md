# Fórum Hub
<p align= "center">
  <img src="https://github.com/haimonvieira/challenge-forum-hub/assets/81303638/8629d122-2b74-4064-a71c-722fcb2a4f01" alt="Badge-Spring">
</p>

<img src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/>
<div>
  <img src="https://img.shields.io/badge/maven--central-v4.0.0-blue"/>
  <img src="https://img.shields.io/badge/spring--boot-v3.3.1-blue"/>
  <img src="https://img.shields.io/badge/java--jwt-v4.2.1-blue"/>
  <img src="https://img.shields.io/badge/springdoc-v2.6.0-blue"/>
</div>

Mais um desafio do programa ONE, um programa com parceria entre Alura e Oracle para fazer ser possível o programa Oracle Next Education(ONE). Neste challenge final da especialização de backend foi passado para que façamos uma API REST de um fórum, mais especificamente da parte de tópicos.

## Funcionalidades
-  Operações **CRUD(CREATE, READ, UPDATE, DELETE)** de Tópico, Curso e Usuário;
  ![Vídeo demonstrativo das operações CRUD](https://github.com/user-attachments/assets/164875a3-70f5-4cf1-8725-58fb2c769ed2)
-  Gerar documentação por meio do Swagger;
-  Validações conforme as regras de negócios;
-  Banco de dados para a persistência dos dados;
-  Autenticação do usuário por meio de token e;
-  Tratamento do código http.


## Tecnologias utilizadas
-  `Java 17`: Versão do Java utilizado
-  `IntelliJ IDEA CE`: IDE utilizada
-  `PostgreSQL`: Conexão com o banco de dados para a persistência dos dados
-  `Spring Boot`: Facilita a aplicação de dependências mais facilmente
-  `Spring Security`: Implementação de segurança no projeto
-  `Flyway Migration`: Controle de versionamento de SGBD
-  `Devtools`: LiveReload para não ter que reinicair manualmente o projeto
-  `Lombok`: Ajuda a fazer os codigos padrões
-  `JWT`: Utilizado para autenticação

## 🗂 Acesso ao projeto
Você pode baixar este projeto **[clicando aqui](https://github.com/haimonvieira/challenge-forum-hub/archive/refs/heads/main.zip)**.

## 🛠️ Rodando o projeto
-  Descompacte o arquivo .zip
-  Abra o **IntelliJ -> Open**
-  Procure o local onde o arquivo foi extraido e selecione-o
-  Aguarde as dependências do Maven serem baixadas
-  Configure as variáveis de ambientes no arquivo `application.properties` em **src -> main -> resources**
  -  Caso não tenha as variáveis de ambiente configuradas, recomendo que veja este artigo da Alura de como configurar: [Como configurar variáveis de ambiente no Windows, Linux e macOS](https://www.google.com/search?client=safari&rls=en&q=variaveis+de+amviente+alura&ie=UTF-8&oe=UTF-8)
- Não se esqueca de criar o DB com o mesmo nome que está no arquivo ou mudar `jdbc:postgresql://${DB_HOST}/{SEU_BANCO_DE_DADOS}`
- Após feitas as mudanças, selecione o `ForumHubApplication` e inicie a aplicação


## Útil
Não esqueca de ter o Java e o JDK instalados em sua máquina com as versões compatíveis.
