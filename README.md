# 🚀 Agente da DIO

## 🔹 Sobre o Projeto
Agente responsável por buscar conteúdos sobre Copilot Studio dentro da documentação oficial da Microsoft.  
Este projeto foi desenvolvido usando **Microsoft Copilot Studio** para fornecer respostas formais e precisas.

## 🛠️ Funcionalidades
✅ Buscar informações no Microsoft Learn  
✅ Retornar respostas formais e amigáveis  
✅ Incluir citações da documentação oficial  

---

## 🏗️ Passo a Passo da Configuração  

### **1️⃣ Criar um Copiloto em Branco**
- Acesse o **[Microsoft Copilot Studio](https://learn.microsoft.com/pt-br/microsoft-copilot-studio/fundamentals-get-started)**.
- Faça login com sua conta da Microsoft.
- Clique em **"Criar novo copiloto"**.
- Escolha a opção **"Em branco"**.
- Nomeie seu copiloto como **"Agente da DIO"**.
- Defina o idioma como **Português**.
- Escolha o ambiente de publicação (**Produção**).
- Clique em **"Salvar e continuar"**.

---

### **2️⃣ Customizar um Tópico**
- No menu lateral, vá até **"Tópicos"**.
- Clique em **"Novo tópico"** e selecione **"Criar manualmente"**.
- Nomeie o tópico como **"Buscar Documentação"**.
- Adicione uma descrição:  
  📌 *"Retorna informações relevantes do Microsoft Learn sobre Copilot Studio"*.  
- Adicione **nós de conversação**:
  - **Pergunta do usuário**: "O que é Copilot Studio?"
  - **Resposta do agente**: "Copilot Studio é uma plataforma da Microsoft para criar copilotos personalizados."
- Teste o tópico clicando em **"Testar"**.

---

### **3️⃣ Personalizar uma Mensagem de Erro de Tópico**
- No menu de tópicos, selecione **"Buscar Documentação"**.
- Adicione um **nó de erro**.
- Defina a mensagem de erro personalizada:  
  ⚠️ *"Desculpe, não encontrei informações sobre isso na documentação oficial. Tente reformular sua pergunta."*
- Teste a mensagem de erro simulando um erro na conversa.

---

### **4️⃣ Ajustar a Qualidade da Resposta com GenAI**
- No menu lateral, vá até **"Configurações"**.
- Selecione **"GenAI"**.
- Ajuste a qualidade da resposta:
  - **Para aumentar a qualidade**, ajuste o parâmetro **"Nível de detalhe"** para **"Alto"**.
  - **Para diminuir a qualidade**, ajuste o parâmetro **"Nível de detalhe"** para **"Baixo"**.
- Teste as alterações simulando diferentes conversas.

---

### **5️⃣ Implementar Citações da Documentação**
- No fluxo de resposta, adicione um nó de **busca na documentação**.
- Configure o agente para incluir **citações** do **Microsoft Learn**.
- Exemplo de resposta com citação:  
  🔗 *"Copilot Studio permite criar copilotos personalizados. Saiba mais [aqui](https://learn.microsoft.com/pt-br/microsoft-copilot-studio/nlu-gpt-quickstart)."*

---

## 🔗 Links Úteis  
- [Microsoft Copilot Studio - Documentação Oficial](https://learn.microsoft.com/pt-br/microsoft-copilot-studio)  
- [Repositório no GitHub](https://github.com/seu-repositorio)  

## 📄 Licença  
Este projeto segue a licença **MIT**.  

---
_Desenvolvido com 💙 por [Joellmir Uchoa](https://github.com/JoelmirUchoa)_  
