# ⚛️ Revisão dos Fundamentos do React

Este repositório foi criado com o objetivo de consolidar, revisar e praticar os conceitos fundamentais do **React**, servindo como um guia de referência prático para o desenvolvimento de aplicações modernas, performáticas e escaláveis.

## 🚀 Conceitos Abordados

O projeto engloba a implementação e revisão prática de pilares essenciais da biblioteca:

- **Componentização:** Divisão da interface em pedaços isolados, reutilizáveis e com escopo fechado.
- **JSX & Renderização Dinâmica:** Manipulação de estruturas XML/HTML diretamente no JavaScript.
- **Props (Propriedades):** Passagem de dados imutáveis de componentes pais para filhos.
- **Gerenciamento de Estado (`useState`):** Armazenamento de dados dinâmicos que reagem e disparam a renderização da interface quando atualizados.
- **Efeitos Colaterais (`useEffect`):** Sincronização da aplicação com APIs externas, escutadores de eventos globais e gerenciamento de ciclo de vida do componente.
- **Custom Hooks (Hooks Customizados):** Extração e desacoplamento da lógica de negócios da camada visual (UI), permitindo o reaproveitamento máximo de código.

---

## 🧠 Boas Práticas de Arquitetura Revisadas

Durante o desenvolvimento e revisão deste projeto, foram aplicados padrões recomendados pela comunidade, tais como:

1. **Separação de Responsabilidades:** Componentes visuais devem focar na renderização da UI, delegando lógicas complexas de estado para *Custom Hooks*.
2. **Desacoplamento de Eventos:** *Hooks* customizados devem expor funções e estados genéricos. Sempre que um evento nativo do navegador (como `onClick` ou `onChange`) for necessário dentro de um hook, o `event` deve ser injetado como parâmetro pelo componente que consome a função, preservando a reusabilidade do código.
3. **Imutabilidade:** Atualização correta de estados complexos (objetos e arrays) utilizando o operador *spread* (`...`).

---

## 🛠️ Tecnologias Utilizadas

- **React** (Biblioteca principal)
- **JavaScript (ES6+) / TypeScript**
- **Vite** (Ferramenta de build rápida para o ambiente de desenvolvimento)
- **CSS Modules / TailwindCSS** (Estilização isolada)

---

## 🔧 Como Executar o Projeto

Para rodar este projeto localmente, siga os passos abaixo:

### 1. Clonar o repositório
```bash
git clone [https://github.com/leandromarqueti/Revisao-Fundamentos-React.git](https://github.com/leandromarqueti/Revisao-Fundamentos-React.git)
