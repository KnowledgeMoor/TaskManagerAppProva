# Aplicativo de Gerenciamento de Tarefas

Um aplicativo simples e intuitivo para gerenciamento de tarefas criado com React Native que ajuda você a organizar suas tarefas diárias com níveis de prioridade.

## Funcionalidades

- Criar, editar e excluir tarefas
- Definir níveis de prioridade (Alta, Média, Baixa) para cada tarefa
- Ordenar tarefas por prioridade em ordem crescente ou decrescente
- Indicadores visuais de prioridade com código de cores
- Interface limpa e responsiva

## Instalação

1. Clone o repositório:
```bash
git clone https://github.com/seuusuario/gerenciador-de-tarefas.git
cd gerenciador-de-tarefas
```

2. Instale as dependências:
```bash
npm install
```

3. Inicie o servidor de desenvolvimento:
```bash
npm start
```

## Como Usar

### Adicionando uma Tarefa
1. Digite o nome e a descrição da tarefa
2. Selecione um nível de prioridade (Alta, Média, Baixa)
3. Toque em "Enviar" para adicionar a tarefa

### Editando uma Tarefa
1. Toque no botão "Editar" em qualquer tarefa
2. Modifique os detalhes da tarefa
3. Toque em "Enviar" para salvar as alterações

### Excluindo uma Tarefa
- Toque no botão "Excluir" em qualquer tarefa para removê-la

### Ordenando Tarefas
- Use os botões "Ordenar Crescente" ou "Ordenar Decrescente" para organizar as tarefas por prioridade

## Detalhes de Implementação

O aplicativo utiliza o gerenciamento de estado do React para manipular os dados das tarefas e oferece uma experiência de usuário fluida com elementos de interface intuitivos. O sistema de prioridade é codificado por cores:

- Prioridade alta: Vermelho
- Prioridade média: Amarelo
- Prioridade baixa: Verde
