# 🔍 Experiência 04: Engenharia Reversa Assistida por Inteligência Artificial

## 📝 Descrição do Projeto
Esta atividade técnica consistiu em assumir a posição de um Desenvolvedor de Software assistido por IA para realizar o processo de engenharia reversa de uma aplicação real. O desafio prático envolveu a reconstrução completa e funcional do aplicativo **"Markdown Live"** (baseado no StackEdit) estritamente através da observação de sua interface externa e comportamento lógico, sem qualquer tipo de acesso ao código-fonte original ou fornecimento de links estruturais para o modelo generativo.

## 🚀 Metodologia e Ferramentas Utilizadas
O procedimento seguiu um pipeline rigoroso de três etapas executadas na plataforma **Google AI Studio** utilizando o modelo **Gemini**:
1. **Análise e Mapeamento:** Exploração do webapp de referência para mapear todos os componentes de UI (interface do usuário) e fluxos da lógica de negócio.
2. **Configuração Estrutural:** Definição das *System Instructions* no AI Studio, instruindo o modelo a agir como Engenheiro Full-Stack Sênior e descrevendo as interações lógicas esperadas do usuário.
3. **Construção e Validação:** Geração iterativa do código, testes em ambiente local e refinamento das instruções até que o software final apresentasse a mesma estética e comportamento da referência original.

## 💻 Arquitetura e Engenharia de Prompt
O aplicativo foi consolidado em um arquivo HTML único e responsivo contendo CSS estruturado e JavaScript nativo para manipulação de eventos:
* **Prompt de Escopo:** Instruções exatas para criação de uma interface dividida verticalmente em duas colunas (50/50 na viewport), com um `textarea` de entrada de texto à esquerda e uma `div` de preview em tempo real à direita.
* **Integração Técnica:** Configuração de um *event listener* de `input` conectado via CDN à biblioteca externa `marked.js` para realizar o parse em tempo real do Markdown para HTML de forma otimizada.

## 📊 Reflexões Críticas e Éticas

### 1. O Impacto na Formação do Engenheiro Júnior
Com a automação da escrita sintática por ferramentas como o Gemini, o esforço do desenvolvedor migra da digitação de código para a descrição lógica e a capacidade arquitetural. Para não se tornarem obsoletos, os profissionais iniciantes devem desenvolver:
* **Competência Técnica (Arquitetura e Design Abstrato):** Capacidade de decompor problemas complexos em requisitos sistêmicos claros e assertivos.
* **Competência Comportamental (Pensamento Crítico e Validação Técnica):** Habilidade analítica para atuar como um auditor técnico e ético do código gerado, garantindo segurança e boas práticas.

### 2. O Limite entre Aprendizado e Plágio Digital
A engenharia reversa atua como ferramenta legítima de aprendizado e prototipagem quando o desenvolvedor estuda o comportamento para criar sua própria implementação lógica. O processo cruza a linha do plágio digital no momento em que busca a cópia idêntica da identidade visual proprietária e do modelo de negócios com o objetivo de comercialização direta ou concorrência desleal. 
* **Diretriz Ética Proposta:** Adoção de uma política de *Clean Room Design* assistida por IA, documentando que as especificações funcionais foram criadas de forma independente, além da obrigatoriedade de aplicar inovações ou melhorias substanciais ao MVP gerado, respeitando as licenças de software originais.

## 🔧 Como Visualizar
* O relatório técnico oficial e detalhado de engenharia reversa (**Relatorio_Engenharia_de_Prompt_Adriano_Marcal.pdf**) encontra-se anexado nesta pasta.
