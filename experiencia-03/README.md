# ⚔️ Experiência 03: Batalha de Modelos & Engenharia de Prompt (XML)

## 📝 Descrição do Projeto
Nesta atividade, o desafio foi elevar o nível da Engenharia de Prompt utilizando a formatação em **XML** para estruturar comandos complexos. O objetivo foi criar um prompt detalhado para gerar o código de uma página web completa (HTML5 Single Page com CSS3 interno) com o tema "Melhores Jogadores de Futebol no Mundo em Atividade (e próximos da aposentadoria)". Após criar o prompt, testamos e comparamos o desempenho de diversos modelos de Inteligência Artificial (ChatGPT, Gemini, Claude, Qwen, DeepSeek, Grok, Maritaca) para descobrir qual entregava o melhor código e design.

## 🚀 Tecnologias e Conceitos Utilizados
* **Modelos Avaliados:** Múltiplos LLMs do mercado.
* **Conceitos:** Engenharia de Prompt Avançada, Estruturação de Comandos com tags `<XML>`, Benchmarking (Comparativo) de IA.
* **Linguagens (Geradas pela IA):** HTML5 e CSS3.

## 💻 O Prompt Estruturado (Trecho)
Para garantir que a IA não ignorasse as regras, envelopamos as instruções usando a lógica XML. Um trecho da estrutura utilizada:
```xml
<tarefa>
  <objetivo>Criar uma página HTML5 única com CSS3 interno (single page).</objetivo>
  <tema>[Melhores Jogadores de futebol no mundo em atividade]</tema>
  <diretrizes_design>
    <layout>Responsivo e minimalista.</layout>
    <paleta_cores>[Azul, vermelho e roxo]</paleta_cores>
    <tipografia>Sans-serif para títulos, Serif para corpo.</tipografia>
  </diretrizes_design>
  </tarefa>
