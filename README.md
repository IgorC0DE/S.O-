# 🖥️ SysMonitor

### 🚀 Dashboard de Monitoramento de Sistema em Tempo Real

O **SysMonitor** é uma aplicação web desenvolvida para monitorar e visualizar informações importantes sobre o computador em tempo real.

Utilizando **Node.js** e **Express** no backend, juntamente com **HTML, CSS e JavaScript** no frontend, o projeto apresenta uma interface moderna, intuitiva e responsiva.

O objetivo do SysMonitor é oferecer uma visão geral dos recursos e das características do sistema operacional através de um dashboard organizado, permitindo acompanhar informações como memória RAM, processadores, arquitetura, hostname e tempo de atividade do computador.

---

## 📸 Sobre o Projeto

O SysMonitor possui uma interface inspirada em dashboards modernos de monitoramento, com tema escuro, efeitos visuais, cartões informativos e navegação por abas.

A aplicação utiliza uma API própria para obter informações do sistema operacional e atualizar automaticamente os dados apresentados na interface.

---

## ✨ Funcionalidades

### 📊 Dashboard Principal
- Visualização geral das informações do computador.
- Exibição do hostname da máquina.
- Identificação da plataforma do sistema operacional.
- Quantidade de processadores disponíveis.
- Tempo de atividade do sistema (Uptime).
- Painéis organizados para facilitar a leitura das informações.

### 🧠 Monitoramento de Memória RAM
- Memória RAM total disponível.
- Quantidade de memória utilizada.
- Quantidade de memória livre.
- Percentual de utilização da memória.
- Indicador gráfico circular de consumo de RAM.
- Atualização automática das informações.

### ⚡ Informações do Processador
- Quantidade de CPUs disponíveis.
- Modelo do processador.
- Identificação dos processadores através do módulo OS do Node.js.

### ⚙️ Informações do Sistema
- Hostname do computador.
- Sistema operacional utilizado.
- Arquitetura do sistema.
- Tempo de atividade do computador.
- Informações obtidas através das funcionalidades nativas do Node.js.

### 🔄 Atualização Automática
- Consulta automática à API a cada 3 segundos.
- Atualização dinâmica das informações.
- Comunicação entre frontend e backend utilizando Fetch API.
- Exibição dos dados sem precisar atualizar manualmente a página.

### 🎨 Interface e Design
- Tema escuro moderno.
- Gradientes e efeitos visuais.
- Cards com animações ao passar o mouse.
- Menu lateral com navegação por abas.
- Layout responsivo para diferentes tamanhos de tela.
- Indicador visual de status do sistema.

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Aplicação |
|---|---|
| Node.js | Ambiente de execução JavaScript no servidor |
| Express.js | Criação do servidor e das rotas HTTP |
| JavaScript | Lógica da aplicação e atualização dinâmica |
| HTML5 | Estrutura da interface |
| CSS3 | Estilização e responsividade |
| Fetch API | Comunicação entre frontend e backend |
| OS Module | Obtenção de informações do sistema operacional |

---

## 📁 Estrutura do Projeto

```text
SysMonitor/
│
├── server.js
├── package.json
├── package-lock.json
└── README.md
