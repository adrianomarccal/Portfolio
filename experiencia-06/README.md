# ⚙️ Experiência 06: Engenharia de Software e IA com Bubble.io

## 📝 Descrição do Projeto
O desafio final consistiu em sair do campo da ideação e ir para a execução prática. O objetivo foi desenvolver uma aplicação Web funcional utilizando a plataforma No-Code **Bubble.io**, integrada com uma Inteligência Artificial Generativa através de chamadas de API. Esta experiência serviu como prova de conceito de que é possível construir softwares completos e integrados com IA rapidamente, focando na arquitetura e nas regras de negócio.

## 🚀 Tecnologias e Ferramentas Utilizadas
* **Frontend e Backend:** Bubble.io (Plataforma No-Code).
* **Integração:** Plugin API Connector (Bubble).
* **Motor de IA:** Integração via API REST.

## ⚙️ Lógica do Workflow (Regra de Negócio)
A aplicação funciona baseada na seguinte estrutura lógica de eventos:
1. **Entrada de Dados:** O usuário digita o seu comando (prompt) em um campo de texto (`Multiline Input`).
2. **Gatilho (Trigger):** Ao clicar no botão de envio, um workflow é acionado no backend visual do Bubble.
3. **Chamada de API (POST):** O workflow dispara o plugin API Connector. Ele pega o texto dinâmico que o usuário digitou, insere dentro de um formato JSON, e envia para os servidores da IA de forma segura (utilizando chaves de autorização Bearer).
4. **Retorno e Exibição:** O aplicativo aguarda a resposta dos servidores da IA, extrai apenas o texto útil gerado e o projeta em um elemento de Texto (`Text`) na interface do usuário.

## 🔗 Link da Aplicação
* Acesse o Web App funcional aqui: **[COLE O LINK DO SEU APP NO BUBBLE AQUI]**

## 🔧 Como Visualizar
* As capturas de tela comprovando o desenvolvimento da aplicação — incluindo a construção da **Interface**, a configuração técnica do **API Connector** e a estrutura do **Workflow** — encontram-se anexadas nos arquivos desta pasta.
