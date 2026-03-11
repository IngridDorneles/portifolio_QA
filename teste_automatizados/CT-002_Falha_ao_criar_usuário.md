# Casos de Teste

📌 Teste de API – Falha ao Criar Usuário (POST)

📄 Identificação do Teste

Nome: CT-002 – Falha ao criar usuário

Método: POST

Endpoint: https://serverest.dev/usuarios

---

**Objetivo**

Validar que a API apresenta erro ao tentar criar um usuário com mesmo e-mail (e-mail duplicado) e retorna status 400.



**Body da Requisição:**

<img width="313" height="122" alt="image" src="https://github.com/user-attachments/assets/e754b672-2b70-4207-b63d-082cd07fd22c" />



**✅ Validações Realizadas:**

- Mensagem de erro retornada corretamente

- Status code 400 – Fail

- ID do usuário não gerado



**🧪 Script de Teste (Postman – Tests):**

<img width="597" height="283" alt="image" src="https://github.com/user-attachments/assets/39ecf4d8-fec8-44b7-abbb-d222f1c021d8" />
<img width="594" height="128" alt="image" src="https://github.com/user-attachments/assets/2fbd0e8a-2ba6-4f1f-b1fc-201c6002bad3" />



**📤 Resposta Esperada:**

<img width="725" height="142" alt="image" src="https://github.com/user-attachments/assets/71007cab-ac57-4f84-b27f-329f4c7e7410" />




**Observações**

O ID do usuário é armazenado na variável de ambiente user_id, permitindo reutilização em cenários de:

- Buscar usuário

- Atualizar usuário

- Deletar usuário

- Teste executado com sucesso no Postman.
