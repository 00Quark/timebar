# ⏳ TimeBar

[![Acessar TimeBar](https://img.shields.io/badge/Acessar%20Site-TimeBar-00bfff?style=for-the-badge&logo=vercel&logoColor=white)](https://delta-os-site.vercel.app/) 

> *"O tempo passa de qualquer forma. Pelo menos agora você pode assistir."*

O **TimeBar** é uma aplicação web de visualização de progresso temporal. Desenvolvida como uma Single-Page Application sem dependências externas, ela transforma qualquer intervalo de tempo — uma data, uma duração ou o próprio dia — em uma barra de carregamento viva, com temas visuais radicalmente distintos entre si.

---

## 🚀 Funcionalidades Principais

* 📅 **3 Modos de Rastreamento**
  * **Data/Hora** — defina um intervalo entre duas datas e horários específicos
  * **Duração** — temporizador regressivo de segundos até horas
  * **Dia de Hoje** — acompanha em tempo real quanto do período configurado já passou

* ⚡ **Presets de Um Clique** — Ano, Mês, Semana e Dia atual com percentual já calculado na tela

* 🎚️ **Slider de Tempo Rápido** — atalhos de 0 → 1m → 2m → 5m → 10m → 20m → 30m → 40m → 1h para o modo Duração

* 🎨 **10 Temas Visuais Distintos**

  | Tema | Descrição |
  |---|---|
  | **Minimal** | Tipografia serifada, paleta neutra, barra fina |
  | **Frutiger Aero** | Glassmorphism azulado estilo Windows Vista |
  | **Tech** | Terminal verde com scanlines e glow neon |
  | **Retro** | Laranja queimado com listras animadas |
  | **Soft** | Rosa pastel com gradiente lilás |
  | **Dark** | Gradiente roxo/rosa com Orbitron |
  | **Scene** | Neon magenta/ciano, estética MySpace/2008 |
  | **Y2K** | Chrome metálico com orbs de vidro e arco-íris |
  | **Medieval** | UnifrakturMaguntia, pergaminho escuro, dourado |
  | **Gótico** | Carmesim pulsante, névoa sanguínea, cruz decorativa |

* 🔔 **Celebração ao Concluir** — confetes em canvas com física real + Westminster Chimes sintetizado via Web Audio API (5 parciais de sino)

* 🔄 **Favicon Animado** — anel de progresso SVG na aba do navegador: spinning idle → arco roxo preenchendo → anel verde ao concluir

---

## 🎮 Como Usar

### Passo 1 — Escolher um Preset ou Configurar Manualmente
Clique em **Ano**, **Mês**, **Semana** ou **Dia** para iniciar imediatamente com o período atual — o percentual já aparece em tempo real em cada botão. Para configurar manualmente, use o card **Configurar** abaixo.

### Passo 2 — Selecionar o Modo
- **📅 Data/Hora** → preencha início e fim com datas e horários
- **⏱ Duração** → arraste o slider rápido ou preencha horas/minutos/segundos
- **🕐 Dia de Hoje** → defina o intervalo de horas do seu dia

### Passo 3 — Iniciar
Clique em **▶ INICIAR** e acompanhe a barra progredir em tempo real. Ao atingir 100%, confetes explodem na tela e os Westminster Chimes tocam.

### Passo 4 — Trocar o Tema
Use o seletor de temas no topo — cada card mostra um preview de cores do tema antes de clicar.

---

## ⚙️ Acesso e Execução

Você pode acessar o sistema diretamente pelo navegador através do link oficial hospedado na Vercel, ou rodar localmente na sua máquina.

### 🌐 Acesso Direto (Live)
Clique no botão no topo da página ou acesse: **[timebar-site.vercel.app](https://timebar.vercel.app/)**

### 🖥️ Rodando Localmente
Caso queira testar o código na sua máquina, não é necessária nenhuma instalação complexa de servidores.

1. Clone este repositório:
   ```bash
   git clone [https://github.com/00Quark/timebar.git](https://github.com/00Quark/timebar.git)

---
*tic-tac-tic-tac*
