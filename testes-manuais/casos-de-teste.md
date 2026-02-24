# Casos de Teste

📌 Teste de API – Criar Usuário (POST)

📄 Identificação do Teste

Nome: CT-001 – Criar usuário com sucesso

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

<img width="698" height="193" alt="image" src="https://github.com/user-attachments/assets/16e0533f-4b4c-445b-8eae-975ffd55db46" />




**Observações**

O ID do usuário é armazenado na variável de ambiente user_id, permitindo reutilização em cenários de:

- Buscar usuário

- Atualizar usuário

- Deletar usuário

- Teste executado com sucesso no Postman.

