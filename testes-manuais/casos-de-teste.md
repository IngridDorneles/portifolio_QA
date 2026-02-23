# Casos de Teste

📌 Teste de API – Criar Usuário (POST)

📄 Identificação do Teste

Nome: CT01 – Criar usuário com sucesso

Método: POST

Endpoint:
https://serverest.dev/usuarios

---

**Objetivo**

Validar que a API cria um usuário com sucesso e retorna status 201, mensagem correta e ID válido.



**Body da Requisição:**

<img width="313" height="122" alt="image" src="https://github.com/user-attachments/assets/e754b672-2b70-4207-b63d-082cd07fd22c" />



**✅ Validações Realizadas:**

- Mensagem de sucesso retornada corretamente

- Status code 201 – Created

- ID do usuário gerado e não nulo

- ID salvo em variável de ambiente para reutilização em outros testes


**🧪 Script de Teste (Postman – Tests):**

<img width="597" height="283" alt="image" src="https://github.com/user-attachments/assets/39ecf4d8-fec8-44b7-abbb-d222f1c021d8" />



**📤 Resposta Esperada:**

<img width="422" height="160" alt="image" src="https://github.com/user-attachments/assets/99b9c0de-b99f-466a-a898-5ac7c5488822" />



**Observações**

O ID do usuário é armazenado na variável de ambiente user_id, permitindo reutilização em cenários de:

- Buscar usuário

- Atualizar usuário

- Deletar usuário

- Teste executado com sucesso no Postman.

---
