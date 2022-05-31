---
theme: apple-basic
layout: intro-image
image: 'https://unsplash.com/photos/XsP7GCLMWjM/download?force=true&w=1920'
---

<div class="absolute top-10">
  <span class="font-700">
    Valerio Como
  </span>
</div>

<div class="absolute bottom-10">
<h1>VSCode Remote Feature</h1>
<p>Devcontainer</p>
</div>

---
layout: image-right
image: 'https://unsplash.com/photos/uBe2mknURG4/download?force=true&w=1920'
---

# Overview

* Problema
* Soluzione
* Considerazioni

---
layout: section
---

# Problema

---
layout: statement
---

## A quanti progetti hai lavorato negli ultimi mesi?

---
layout: statement
---

# Tanti

---
layout: statement
---

## Quanti setup hai effettuato negli ultimi mesi?

---
layout: statement
---

# Troppi

---
layout: statement
---

## In cosa consiste fare il setup di un progetto?

---
layout: image-right
image: 'https://unsplash.com/photos/I7iJOE4fsYo/download?force=true&w=1920'
---

# Problema
## Setup di progetto

<v-clicks>

- Environment/Runtime (NodeJs, PHP, Docker)

- Versioni specifiche

- Registry locali (npm)

- Configurazione IDE

</v-clicks>
---
layout: statement
---
# Docker risolve questi problemi?

<v-click>

# NI

</v-click>

---
layout: statement
---

# Fatto realmente accaduto

---
layout: statement
---

# Domanda
## Quale versione di NodeJS stiamo utilizzando come target?

---
layout: statement
---

# Risposta
## 4 versioni diverse (di cui una era boh)

---
layout: image
image: 'https://c.tenor.com/KIZbS5cc12sAAAAC/sheldon-sheldon-cooper.gif?force=true'
---

---
layout: image-right
image: 'https://unsplash.com/photos/1K9T5YiZ2WU/download?force=true&w=1920'
---

# Problema
## Setup di progetto

<v-clicks>

- Processo articolato

- Time consuming

- Non automatizzato


</v-clicks>

---
layout: section
---

# Soluzione

---
layout: statement
---

# VSCode Remote Feature

---
layout: statement
---

Visual Studio Code Remote Development consente di utilizzare un container, oppure una macchina remota, oppure Windows Subsystem for Linux (WSL) come development environment.

---

# VSCode Remote Feature

<v-clicks>

- Sviluppo nello stesso environment di deploy

- Ambiente di sviluppo separato (NO configurazione)

- Onboarding rapido

- Gestione versioni runtime/environment

- Sviluppo per ambienti Linux su Windows (WSL) 

- Accesso remoto allo stesso environment da diversi PC

- Debugging remoto

</v-clicks>
---

# VSCode Remote Feature

<img src="https://code.visualstudio.com/assets/docs/remote/remote-overview/architecture.png?force=true">

---

# VSCode Remote Feature
## Remote Development Extension Pack

Include le tre estensioni

* Remote - SSH
* Remote - Containers
* Remote - WSL

---

# VSCode Remote Feature
## Remote - Containers

<img src="https://code.visualstudio.com/assets/docs/remote/containers/architecture-containers.png?force=true">

---

# VSCode Remote Feature
## Devcontainer

devcontainer.json

<v-clicks>

- setup (Dockerfile, Docker Compose, Docker Image)

- hook

- automazione

</v-clicks>

---
layout: section
---

# Considerazioni

---
layout: two-cols
---


<template v-slot:default>

# PROs

<v-clicks>

- Setup unico e replicabile 

- Configurazione automatizzata

- Isolamento

- Autoconsistenza

- Onboarding rapido

- Gestione delle versioni

- WSL 

- Estensioni VSCode relative al progetto

</v-clicks>

</template>
<template v-slot:right>

# CONs

<v-clicks>

- Setup complessi

- Performance con WSL

- Spazio sul disco

</v-clicks>

</template>

