# Tomate 🍅

Sistema web de gerenciamento de tarefas com temporizador Pomodoro.

🌐 **[Acessar o Tomate](https://ericklimagg.github.io/tasks-site/)**

## Sobre o projeto

O **Tomate** é uma aplicação web desenvolvida para combinar gerenciamento de tarefas e a técnica Pomodoro em uma interface simples e intuitiva.

A aplicação permite organizar tarefas por prazo e utilizar um temporizador para auxiliar na concentração e no gerenciamento do tempo.

## Funcionalidades

### 🍅 Temporizador Pomodoro

- Temporizador padrão de 25 minutos
- Pausas curtas e longas
- Início, pausa e controle do temporizador
- Configuração do tempo utilizando os controles disponíveis

### ✅ Gerenciamento de tarefas

- Criação de novas tarefas
- Definição de nome, descrição e prazo
- Organização automática por período
- Marcação de tarefas como concluídas
- Exclusão de tarefas

### 📅 Organização por prazo

As tarefas são organizadas nas seguintes categorias:

- Expiradas
- Próximos 6 dias
- Próximos 30 dias
- Mais de 30 dias

### 💾 Persistência

As tarefas são armazenadas no **LocalStorage** do navegador, permitindo que os dados permaneçam disponíveis entre sessões no mesmo dispositivo.

## Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript (Vanilla)
- LocalStorage
- GitHub Pages

## Estrutura do projeto

```text
tasks-site/
├── css/
│   ├── alarm.css
│   ├── footer.css
│   ├── header.css
│   ├── main.css
│   ├── newtask.css
│   ├── pause.css
│   ├── style.css
│   ├── taskdeadlline.css
│   └── tasksdisplay.css
│
├── js/
│   ├── alarm.js
│   ├── newtask.js
│   ├── pause.js
│   ├── taskdisplay.js
│   └── taskstorage.js
│
├── index.html
└── README.md
