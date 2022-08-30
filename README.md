# TDD Validação e Segurança
Implementação das funcionalidades necessárias para que os testes escritos utilizando o JUnit5 sejam cobertos. Este é um sistema de eventos e cidades com uma relação N-1.
Exercício desenvolvido durante o Bootcamp Spring React da [DevSuperior](https://devsuperior.com.br/) como requisito obrigatório para obtenção do certificado.

## Especificações
Neste sistema somente as rotas de leitura (GET) de eventos e cidades são públicas (não precisa de login). Usuários CLIENT podem também 
inserir (POST) novos eventos. Os demais acessos são permitidos apenas a usuários ADMIN.

## Competências

  - Modelo de dados de usuários e perfis
  - Validação com Bean Validation
      - Annotations
      - Customizando a resposta HTTP
      - Validações personalizadas com acesso a banco
  - Autenticação e autorização
      - Spring Security
      - OAuth 2.0
      - Token JWT
      - Autorização de rotas por perfil
  - Variáveis de ambiente no projeto com coalescência

## Requisitos para aprovação
  - Validações de City:
      - Nome não pode ser vazio
  - Validações de Event:
      - Nome não pode ser vazio
      - Data não pode ser passada
      - Cidade não pode ser nula
  - [Collection do Postman para teste](https://www.getpostman.com/collections/e1f59c905aeca84c1ebc)



### Modelo conceitual
![Modelo Conceitual](https://github.com/vanessa-maganhoto/assets/blob/main/bds-validacao-seguranca/modelo-conceitual.png)

## Tecnologias utilizadas
### Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven
- JUnit5
- Postman

## Como executar o projeto

### Back end
Pré-requisitos: Java 11

```bash
# clonar repositório
git clone git@github.com:vanessa-maganhoto/bds04-desafio-validacao-seguranca-TDD.git

# executar o projeto
./mvnw spring-boot:run
```

## Autor

Vanessa Matos

https://www.linkedin.com/in/vanessaammatos



