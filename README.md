# Página de Atendimento Escolar – E.E. Caetano de Campos

Este projeto é uma página HTML com informações e serviços online/presenciais para estudantes e responsáveis da Escola Estadual Caetano de Campos – Aclimação. A página oferece links úteis para solicitações de documentos, acesso à SED (Secretaria Escolar Digital), boletim escolar e contato direto com a secretaria da escola por e-mail.

## 🧩 Funcionalidades

- Solicitação online de documentos (Histórico Escolar, Bilhete Único, Matrícula etc.)
- Links úteis da SED e da SPTrans
- Informações sobre atendimento presencial
- Envio de e-mails por meio de `SMTP.js`

## ⚠️ Avisos importantes

> ⚠️ **Não é recomendado armazenar credenciais de e-mail diretamente no código-fonte.**  
> Utilize variáveis de ambiente ou back-end seguro para dados sensíveis.

## 💡 Como usar

1. Edite o HTML conforme necessário (e.g., altere os e-mails e caminhos dos links).
2. Hospede o arquivo em um servidor web ou plataforma como GitHub Pages.
3. Para uso do `SMTP.js`, configure as credenciais de forma segura.

## 📂 Estrutura do código

- HTML puro com CSS embutido
- Uso de `SMTP.js` para envio de e-mails
- Estilo baseado em Bootstrap-like

## 🔐 Segurança

Este projeto **não deve ser usado em produção com credenciais reais de e-mail** diretamente no cliente. Para produção, recomenda-se o uso de um back-end para gerenciar o envio seguro de e-mails.

---

## 📝 Licença

Distribuído sob a Licença MIT. Veja o arquivo `LICENSE` para mais detalhes.
