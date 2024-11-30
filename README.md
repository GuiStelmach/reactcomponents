# Atividade 7 - Componentes React

Este repositório contém uma coleção de componentes desenvolvidos em React. Cada componente foi criado para realizar uma tarefa específica e utiliza hooks como `useState` e `useEffect` para gerenciar estados e efeitos colaterais. Este projeto faz parte da **atividade 7** da formação **Desenvolvedor FullStack Junior** da **+praTi** em parceria com **Codifica Edu**.

## Navegação

Para facilitar a navegação entre os diferentes componentes, foi implementada uma **Navbar** que permite acessar cada um dos exemplos abaixo.

### 1. Contador Simples
- **Descrição**: Um componente que exibe um número na tela e possui dois botões: "Incrementar" e "Decrementar". O valor do contador não pode ser menor que zero.
- **Hooks Utilizados**: `useState`
- **Desafio**: Garantir que o valor não seja negativo.

### 2. Alteração de Cor de Fundo
- **Descrição**: Um componente que muda a cor de fundo da página sempre que o usuário clica em um botão. 
- **Hooks Utilizados**: `useState`, `useEffect`
- **Desafio**: Gerar cores aleatórias a cada clique no botão.

### 3. Lista de Tarefas (To-Do List)
- **Descrição**: Um aplicativo de lista de tarefas onde o usuário pode adicionar, remover e marcar tarefas como concluídas. Também é possível filtrar as tarefas para ver apenas as pendentes.
- **Hooks Utilizados**: `useState`
- **Desafio**: Permitir marcar as tarefas como concluídas e aplicar um filtro de tarefas pendentes.

### 4. Temporizador com `useEffect`
- **Descrição**: Um temporizador que conta o tempo em segundos. O tempo é exibido e atualizado na tela, com a possibilidade de pausar e reiniciar.
- **Hooks Utilizados**: `useState`, `useEffect`
- **Desafio**: Adicionar funcionalidade para pausar e reiniciar o temporizador.

### 5. Filtro de Lista
- **Descrição**: Um componente que renderiza uma lista de nomes e permite filtrar os itens com base no texto digitado no campo de entrada.
- **Hooks Utilizados**: `useState`
- **Desafio**: Ignorar maiúsculas e minúsculas ao filtrar os itens da lista.

### 6. Formulário de Registro Simples
- **Descrição**: Um formulário com campos de nome, e-mail e senha. Ao enviar o formulário, exibe uma mensagem de boas-vindas com as informações preenchidas.
- **Hooks Utilizados**: `useState`
- **Desafio**: Validar o preenchimento dos campos antes de enviar o formulário.

### 7. Aplicação de Requisição de Dados Simples
- **Descrição**: Um componente que faz uma requisição a uma API pública (ex.: JSONPlaceholder) para exibir uma lista de posts.
- **Hooks Utilizados**: `useState`, `useEffect`
- **Desafio**: Adicionar um botão para recarregar os dados e exibir um indicador de carregamento durante a requisição.

### 8. Galeria de Imagens com Visualização Detalhada
- **Descrição**: Uma galeria simples de imagens onde, ao clicar em uma imagem, ela é exibida em um modal. O modal pode ser fechado e navegado entre as imagens.
- **Hooks Utilizados**: `useState`
- **Desafio**: Implementar navegação entre as imagens no modal e adicionar um botão de "Fechar".

### 9. Timer com Intervalo e Alerta
- **Descrição**: Um timer que permite ao usuário definir um tempo de contagem regressiva em segundos. Ao chegar a zero, um alerta é exibido informando que o tempo acabou.
- **Hooks Utilizados**: `useState`, `useEffect`
- **Desafio**: Adicionar botões para pausar e reiniciar o timer.

### 10. Componentes com Tabs Navegáveis
- **Descrição**: Uma interface com abas ("tabs") que exibe conteúdo diferente conforme a aba selecionada.
- **Hooks Utilizados**: `useState`
- **Desafio**: Adicionar um efeito visual que destaque a aba ativa.

## Instalação

Para rodar este projeto localmente, siga as etapas abaixo:

1. Clone o repositório:
   ```bash
   git clone https://github.com/GuiStelmach/reactcomponents
   
2. Navegue até o diretório do projeto:
   ```bash
   cd reactcomponents

3. Instale as dependências:
   ```bash
   npm install

4. Execute o projeto:
   ```bash
   npm run dev

Agora, você pode acessar os componentes através da Navbar para visualizar e interagir com cada um dos exemplos.


