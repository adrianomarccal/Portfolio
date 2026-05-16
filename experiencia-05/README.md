# 🌀 AuraSync Design Intelligence v2.0

**Engine de alta fidelidade para geração de Design Tokens e Glassmorfismo assistido por IA.**

## 💎 Visão Geral
O AuraSync é uma plataforma avançada de engenharia de design que funde estética neubrutalista com inteligência artificial. Projetado para desenvolvedores e designers modernos, o ecossistema permite a criação, compartilhamento e exportação de interfaces glassmórficas com precisão técnica absoluta.

## 🚀 Funcionalidades Chave

### 🧠 Inteli-Design (Powered by Gemini)
* **Insight AI:** Análise preditiva de tokens de design com recomendações técnicas.
* **Harmonização de Cores:** Sugestão algorítmica de paletas acessíveis e modernas via IA.

### 🏢 Ecossistema Colaborativo
* **Biblioteca Pessoal:** Sincronização em nuvem de blueprints privados via Firebase.
* **Community Showcase:** Galeria global para compartilhamento e remixagem de presets.
* **Auth Social:** Integração nativa com Google Login para persistência de dados.

### ⚡ Engenharia de Exportação
Multi-Framework: Geração instantânea de código para:
* **CSS Puro** (Legacy support)
* **Tailwind CSS** (Utility-first syntax)
* **SwiftUI** (Apple Native components)

### 🛠️ Admin Terminal
* **Controle de Sistema:** Gestão de critérios de avaliação e permissões administrativas em tempo real.

---

## 🏗️ Arquitetura do Projeto
A organização do código segue os mais altos padrões de modularidade e escalabilidade:

```text
aurasync/
├── src/
│   ├── components/       # Interface modular e componentes Neubrutalistas
│   ├── lib/              # Configurações de serviços (Firebase, Gemini)
│   ├── types.ts          # Definições estritas de TypeScript
│   ├── App.tsx           # Orquestrador principal da UI e lógica de estado
│   └── index.css         # Design system via Tailwind CSS
├── public/               # Assets estáticos
├── firebase-blueprint.json # Definição da estrutura NoSQL (Firestore)
├── firestore.rules       # Regras de segurança e autorização
└── package.json          # Dependências do motor
