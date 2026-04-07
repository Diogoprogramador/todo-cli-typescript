# 📝 Todo CLI TypeScript

Um gerenciador de tarefas simples e funcional feito com TypeScript para linha de comando.

## ✨ Funcionalidades

- ➕ Adicionar tarefas com título e descrição
- 📋 Listar tarefas (todas, pendentes ou concluídas)
- ✅ Marcar tarefas como concluídas
- ⏳ Desmarcar tarefas concluídas
- 🗑️ Remover tarefas individualmente
- 🧹 Limpar todas as tarefas
- 💾 Persistência automática em JSON

## 🚀 Instalação

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/todo-cli-typescript.git
cd todo-cli-typescript

# Instale as dependências
npm install

# Compile o TypeScript
npm run build

# (Opcional) Link global para usar o comando 'todo' em qualquer lugar
npm link
```

## 📖 Uso

```bash
# Adicionar tarefa
todo add "Comprar leite" "Ir ao mercado depois do trabalho"

# Listar todas as tarefas
todo list

# Listar apenas pendentes
todo list pending

# Listar apenas concluídas
todo list completed

# Marcar tarefa como concluída
todo complete 1

# Desmarcar tarefa
todo uncomplete 1

# Remover tarefa
todo delete 1

# Limpar todas as tarefas
todo clear

# Ajuda
todo help
```

## 🛠️ Desenvolvimento

```bash
# Executar em modo desenvolvimento
npm run dev

# Compilar
npm run build

# Executar versão compilada
npm start
```

## 📁 Estrutura do Projeto

```
todo-cli-typescript/
├── src/
│   ├── types.ts         # Interfaces e tipos
│   ├── TaskManager.ts   # Lógica de negócio
│   └── index.ts         # CLI e interface
├── dist/                # Código compilado
├── package.json
├── tsconfig.json
└── README.md
```

## 📝 Tecnologias

- **TypeScript** - Tipagem estática
- **Node.js** - Runtime JavaScript
- **FS/Promises** - Persistência de dados

## 📄 Licença

MIT
