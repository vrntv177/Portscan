
<div align="center">

<img src="./banner_cyberpunk_victor_portscan.png" width="100%" alt="VICTOR PORTSCAN">

# VICTOR PORTSCAN

### Fast & Powerful TCP Port Scanner

**Scanner de portas TCP desenvolvido em Python**

<p>
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Windows-Compatible-0078D6?style=for-the-badge&logo=windows&logoColor=white">
  <img src="https://img.shields.io/badge/Status-Active-00C853?style=for-the-badge">
</p>

**Developed & Customized by VICTOR**

[GitHub](https://github.com/vrntv177) • [Repository](https://github.com/vrntv177/Portscan)

</div>

---

## 📌 Overview

**Victor PortScan** é uma ferramenta de escaneamento de portas TCP desenvolvida em Python para análise de conectividade, estudos de redes e auditorias de segurança autorizadas

O projeto combina execução multithread, configurações personalizáveis e uma interface de terminal com identidade visual própria

### ✨ Destaques

- ⚡ Escaneamento de portas TCP
- 🔍 Identificação de portas abertas
- 🌐 Compatibilidade com IPs e domínios
- 🧵 Execução simultânea com múltiplas threads
- ⏱️ Timeout configurável
- 📁 Exportação de resultados
- 🔥 Modo de varredura Top 10K
- 🎨 Interface ASCII personalizada
- 💻 Suporte ao Windows PowerShell

---

## 🖥️ Interface

O Victor PortScan possui um banner exclusivo com arte ASCII em vermelho e branco, acompanhado da assinatura `by VICTOR`

<div align="center">

<img src="./banner_cyberpunk_victor_portscan.png" width="85%" alt="Interface Victor PortScan">

</div>

---

## 📦 Instalação

### 1. Clone o repositório

```bash
git clone https://github.com/vrntv177/Portscan.git
```

### 2. Entre na pasta

```bash
cd Portscan
```

### 3. Instale as dependências

Tenha o Python 3 instalado

Caso sua versão utilize a biblioteca `pythonping`, execute:

```bash
py -m pip install pythonping
```

---

## 🚀 Como utilizar

### Escaneamento básico

```bash
py portscan_victor.py -t 127.0.0.1
```

### Modo Top 10K

```bash
py portscan_victor.py -t 127.0.0.1 --top-10k
```

### Timeout personalizado

```bash
py portscan_victor.py -t 127.0.0.1 --timeout 240
```

### Configurar threads

```bash
py portscan_victor.py -t 127.0.0.1 --threads 50
```

### Salvar resultados

```bash
py portscan_victor.py -t 127.0.0.1 -o resultado.txt
```

### Exibir ajuda

```bash
py portscan_victor.py --help
```

---

## ⚙️ Parâmetros

| Parâmetro | Descrição |
|:---|:---|
| `-t, --target` | IP ou domínio de destino |
| `--timeout` | Tempo limite por porta em milissegundos |
| `--threads` | Número de threads simultâneas |
| `-o, --output` | Arquivo para salvar os resultados |
| `--top-10k` | Habilita a lista Top 10K |
| `-h, --help` | Exibe os comandos disponíveis |

---

## 📊 Exemplo de execução

```text
[ PINGING ON DOMAIN... ]

Domain  = 127.0.0.1
Timeout = 240 ms
Threads = 30

[ RESULTS ]

[+] 80    → Open
[+] 443   → Open
[+] 8080  → Open

[#] 3 Open ports
[i] Scan completed
```

> Exemplo ilustrativo. As portas identificadas dependem do alvo e dos serviços disponíveis

---

## 🗂️ Estrutura do projeto

```text
Portscan/
│
├── portscan_victor.py
├── banner_cyberpunk_victor_portscan.png
└── README.md
```

---

## 🛠️ Tecnologias

| Tecnologia | Finalidade |
|:---|:---|
| Python | Desenvolvimento |
| Socket | Conexões TCP |
| Threading | Processamento simultâneo |
| Argparse | Argumentos de linha de comando |
| ANSI / ASCII | Personalização do terminal |

---

## 🎯 Objetivos

O projeto tem como principais objetivos:

- Aprimorar conhecimentos em Python
- Estudar comunicação TCP/IP
- Explorar programação multithread
- Desenvolver ferramentas de diagnóstico de rede
- Criar uma interface de terminal personalizada

---

## 🔮 Futuras melhorias

- [ ] Identificação de serviços por porta
- [ ] Exportação em JSON e CSV
- [ ] Barra de progresso
- [ ] Interface interativa
- [ ] Relatórios de escaneamento
- [ ] Melhorias de desempenho
- [ ] Suporte multiplataforma

---

## ⚠️ Aviso legal

O Victor PortScan foi disponibilizado para fins educacionais, diagnósticos de conectividade e auditorias autorizadas

**Utilize esta ferramenta somente em sistemas próprios ou com autorização explícita dos responsáveis**

Uma porta aberta não representa necessariamente uma vulnerabilidade de segurança

---

## 👨‍💻 Desenvolvedor

<div align="center">

### VICTOR

**Python Developer | Networking & Cybersecurity Enthusiast**

[![GitHub](https://img.shields.io/badge/GitHub-vrntv177-181717?style=for-the-badge&logo=github)](https://github.com/vrntv177)

---

### 🔴 VICTOR PORTSCAN

**Fast • Powerful • TCP Scanner**

Made with Python

**© VICTOR**

</div>
