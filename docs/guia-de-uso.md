# 📘 Guia de Uso – Avaí Social Chatbot (Português)

Este guia descreve o processo de uso, personalização e integração do chatbot dos projetos sociais do Avaí Futebol Clube, criado na plataforma Dify.

---

## 🧠 O que é o Dify?

O [Dify](https://dify.ai) é uma plataforma no-code/low-code para desenvolvimento de agentes conversacionais com IA generativa. Permite que profissionais de diferentes áreas criem assistentes inteligentes com fluxos estruturados, sem necessidade de programação.

---

## 🛠️ Etapas de uso

### 1. Importar o YAML no Dify

1. Acesse [https://dify.ai](https://dify.ai)
2. Faça login e clique em “Create App”
3. Escolha “Import YAML”
4. Selecione o arquivo `agente-projetos-sociais.yml` localizado em `chatbot-config/`

---

### 2. Ajustar configurações

- Dê um nome ao agente
- Edite a mensagem de abertura, caso deseje
- Ative plugins como: Wikipedia, Tradutor, Avaliador Matemático
- Habilite o modo agente (Agent mode) com estratégias de ferramentas

---

### 3. Testar localmente

- Use o modo de chat interno do Dify para simular atendimentos
- Teste interações variadas: visitas, dúvidas, agendamento, etc.

---

### 4. Publicar o chatbot

- Gere o link público para testes (exemplo: [https://udify.app/chat/...](https://udify.app/chat/...))
- Incorpore em sites ou integre a outros canais via API

---

### 5. Conectar com WhatsApp (via DatafyChats)

Consulte o documento [`docs/integracao-whatsapp.md`](integracao-whatsapp.md)

---

## 💡 Considerações finais

Este chatbot é uma aplicação real de IA voltada à educação, inclusão social e cidadania, mostrando como tecnologias emergentes podem ser aplicadas em ambientes institucionais de forma ética, acessível e eficaz.
