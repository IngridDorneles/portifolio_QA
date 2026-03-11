# Testes automatizados
Casos de teste e checklists.

### 1. Testes de API com Postman
- **Descrição:** Coleção de testes, com ID e resultados esperados.  
- **Ferramentas:** Postman, Cypress e Selenium.  

| ID | Caso de Teste | Resultado Esperado |
|----|---------------|--------------------|
| CT-001 | Criar usuário com sucesso | Usuário é registrado e criado ID |
| CT-002 | Criação de usuário com falha | Sistema deve impedir cadastro e exibir mensagem informando que o email já está em uso.|
| CT-003 | Login com sucesso | Login realizado com sucesso |
| CT-004 | Login inválido | erro e mensagem: "Email e/ou senha inválidos" |
