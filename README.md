# 🧪 Validação de Formulário em JavaScript

Este projeto é uma implementação simples de validação de formulários usando JavaScript puro. A proposta é garantir que os dados inseridos pelo usuário estejam corretos antes do envio, melhorando a experiência do usuário e prevenindo erros no backend.

🚀 Funcionalidades
Validação de campos obrigatórios

Verificação de e-mail válido

Restrições de senha (mínimo de caracteres, caracteres especiais, etc.)

Feedback visual em tempo real para os usuários

Prevenção de envio com dados inválidos

📁 Estrutura
css
Copy
Edit
📦 form-validation-js
├── index.html
├── style.css
└── script.js
🛠 Tecnologias utilizadas
HTML5

CSS3

JavaScript (Vanilla JS)

💡 Como usar
Clone o repositório:

bash
Copy
Edit
git clone https://github.com/seu-usuario/form-validation-js.git
Abra o index.html em seu navegador.

Teste a validação preenchendo o formulário com diferentes tipos de dados.

✏️ Exemplo de validação
javascript
Copy
Edit
function validarEmail(email) {
  const regex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
  return regex.test(email);
}
A lógica pode ser facilmente adaptada para outras necessidades e formatos.

📌 Observações
O projeto não depende de bibliotecas externas.

Ideal para quem está aprendendo JavaScript e quer entender como validar formulários na prática.
