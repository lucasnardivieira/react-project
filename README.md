# Gerenciador de Tarefas com React + Vite

Este projeto é um gerenciador de tarefas simples desenvolvido com React e Vite. Ele permite adicionar, visualizar, marcar como concluídas e excluir tarefas. O projeto utiliza conceitos fundamentais do React, como componentes, estado, propriedades, hooks e roteamento.

## Principais Tópicos de React Aplicados

- **Componentes Funcionais**: O projeto é estruturado em componentes reutilizáveis, como `AddTask`, `Tasks`, `Button`, `Input` e `Title`.
- **Gerenciamento de Estado**: Utilização do hook `useState` para gerenciar o estado das tarefas.
- **Efeitos Colaterais**: Uso do hook `useEffect` para sincronizar o estado das tarefas com o `localStorage`.
- **Roteamento**: Implementação de rotas com `react-router-dom` para navegar entre a página principal e a página de detalhes da tarefa.
- **Propriedades (Props)**: Comunicação entre componentes através de propriedades, como `onAddTaskSubmit`, `onTaskClick` e `onDeleteTaskClick`.
- **Estilização com Tailwind CSS**: Estilização dos componentes utilizando classes utilitárias do Tailwind CSS.

## Requisitos de Instalação

Certifique-se de ter o [Node.js](https://nodejs.org/) instalado em sua máquina.

### Passos para Instalação

1. **Clone o repositório**:
   ```bash
   git clone <URL_DO_REPOSITORIO>
   cd projeto-react
   ```
2. **Instale as dependências**:
   Após acessar o diretório do projeto, instale as dependências necessárias:
   ```bash
   npm install
   ```
3. **Inicie o servidor de desenvolvimento**:
   Para iniciar o servidor de desenvolvimento e visualizar o projeto no navegador:
   ```bash
   npm run dev
   ```

**Estrutura do Projeto**
Abaixo está uma visão geral da estrutura de pastas e arquivos principais do projeto:
projeto-react/

```bash
├── src/
│ ├── components/ # Componentes reutilizáveis
│ ├── pages/ # Páginas do aplicativo
│ ├── App.jsx # Componente principal
│ ├── main.jsx # Ponto de entrada do React
├── public/ # Arquivos estáticos
├── [package.json](http://_vscodecontentref_/0) # Dependências e scripts do projeto
├── [tailwind.config.js](http://_vscodecontentref_/1) # Configuração do Tailwind CSS
└── [vite.config.js](http://_vscodecontentref_/2) # Configuração do Vite
```

**Tecnologias Utilizadas**

- React: Biblioteca para construção de interfaces de usuário.
- Vite: Ferramenta de build rápida e moderna.
- Tailwind CSS: Framework de estilização baseado em classes utilitárias.
- React Router: Biblioteca para gerenciamento de rotas no React.
