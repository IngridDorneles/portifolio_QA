# Testes manuais e automatizados
Casos de teste e checklists.

### 1. Testes de API com Postman
- **Descrição:** Coleção de testes, com ID e resultados esperados.  
- **Ferramentas:** Postman.  

| ID | Caso de Teste | Resultado Esperado |
|----|---------------|--------------------|
| CT-001 | Criar usuário com sucesso | Usuário é registrado e criado ID |
| CT-002 | Criação de usuário com falha | Sistema deve impedir cadastro e exibir mensagem informando que o email já está em uso.|
| CT-003 | Login com sucesso | Login realizado com sucesso |
| CT-004 | Login inválido | erro e mensagem: "Email e/ou senha inválidos" |

### 2. Testes manuais
- **Descrição:** Coleção de testes, com ID e resultados esperados.  

| ID | Caso de Teste | Resultado Esperado |
|----|---------------|--------------------|
| CT-005 | Busca de produto existente | Sistema deve exibir lista de produtos relacionados à busca. |
| CT-006 | Busca de produto inexistente | Sistema deve exibir mensagem informando que nenhum resultado foi encontrado.|
| CT-007 | Cadastro com email já existente | Sistema deve impedir cadastro e exibir mensagem informando que o email já está em uso.|
