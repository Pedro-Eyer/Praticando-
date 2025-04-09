# 📋 Forms and Validations - HTML5 + Acessibilidade

Este projeto demonstra a criação de um formulário HTML5 moderno com validações nativas e recursos de **acessibilidade web**, seguindo boas práticas semânticas e de usabilidade.

---

## 🧩 Funcionalidades

- Campos obrigatórios com validação automática:
  - Nome, E-mail, Senha (mínimo 6 caracteres), Idade (entre 18 e 99).
- Inputs diversos:
  - Texto, E-mail, Password, Número, Radio, Checkbox, Select e Textarea.
- Agrupamento lógico dos campos com `fieldset` e `legend`.
- Mensagens auxiliares com `placeholder`.
- Botão de envio estilizado e funcional.

---

## ♿ Acessibilidade Implementada

Este formulário foi projetado para ser **acessível para todos os usuários**, incluindo pessoas com deficiências. Foram aplicados os seguintes recursos:

### ✅ Atributos ARIA

- `aria-label`: descrição do formulário.
- `aria-required="true"`: campos obrigatórios marcados para leitores de tela.
- `aria-describedby`: instrução complementar para o campo de senha.

### ✅ Boas práticas semânticas

- Uso correto das tags `label` associadas a inputs (`for` e `id`).
- Utilização de `fieldset` e `legend` para agrupar campos relacionados.
- Identificadores únicos e descritivos para cada campo de entrada.
- Textos claros e objetivos nos placeholders e nas legendas.

---

## 💡 Tecnologias

- **HTML5**
- **CSS3** (linkado via `styles.css`)
- Sem uso de JavaScript neste exemplo — apenas validações nativas e semântica HTML.

---

## 🚀 Como usar

1. Clone o repositório ou copie o código HTML.
2. Crie um arquivo `styles.css` para adicionar estilos personalizados.
3. Abra o arquivo `.html` no navegador.
4. Interaja com o formulário e veja as validações e acessibilidade em ação!

---

## 👨‍💻 Autor

Desenvolvido por Dev Eyer como parte de estudos sobre **Formulários HTML** e **Acessibilidade Web**.

---
