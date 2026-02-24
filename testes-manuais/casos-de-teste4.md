# Casos de Teste

📌 Teste de API – Login inválido

📄 Identificação do Teste

Nome: CT-004 – Login inválido

Método: POST

Endpoint:
https://serverest.dev/login

---

**Objetivo:**

Validar que a API retorna o login e/ou senha inválidos e retorna status 401.



**Body da Requisição:**

<img width="348" height="87" alt="image" src="https://github.com/user-attachments/assets/6f97ae3e-241e-4bb3-88c4-64da9045372e" />




**🧪 Script de Teste (Postman – Tests):**

<img width="570" height="198" alt="image" src="https://github.com/user-attachments/assets/acf33dd3-8be9-4d9d-af47-a1c79a06af25" />


**✅ Validações Realizadas:**

- Mensagem de erro retornada corretamente

- Status code 401 – Unauthorized

- Validação de mensagem


**📤 Resposta:**

<img width="683" height="144" alt="image" src="https://github.com/user-attachments/assets/ff0e56e7-ef9f-4e95-970e-e6985ff22eb1" />


Status:

✔️ Aprovado
