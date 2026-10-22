
<div align="center">

# 🔴 VICTOR PORTSCAN

### Fast & Powerful TCP Port Scanner

**Desenvolvido e personalizado por VICTOR**

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Platform](https://img.shields.io/badge/Platform-Windows-red)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

---

Scanner de portas TCP desenvolvido em Python,
com execução multithread, terminal personalizado
e identificação de portas abertas

</div>

## 📌 Sobre o projeto

O **Victor PortScan** é uma ferramenta de
análise de portas TCP, desenvolvida para
testes de conectividade e auditorias
autorizadas de redes

Possui interface no terminal personalizada,
com arte ASCII e sistema de verificação
simultânea de portas

## 🚀 Funcionalidades

- ⚡ Escaneamento de portas TCP
- 🔍 Identificação de portas abertas
- 🌐 Suporte a IPs e domínios
- 🧵 Escaneamento com múltiplas threads
- ⏱️ Timeout configurável
- 📂 Exportação dos resultados
- 🔥 Modo de varredura Top 10K
- 🎨 Interface personalizada by VICTOR

## 📥 Instalação

Clone o repositório:

    git clone https://github.com/vrntv177/Portscan.git

Entre na pasta:

    cd Portscan

Instale a dependência, caso sua versão a utilize:

    pip install pythonping

## 💻 Como utilizar

**Escaneamento básico:**

    py portscan.py -t 127.0.0.1

**Verificação de portas Top 10K:**

    py portscan.py -t 127.0.0.1 --top-10k

**Configurar timeout:**

    py portscan.py -t 127.0.0.1 --timeout 240

**Configurar threads:**

    py portscan.py -t 127.0.0.1 --threads 50

**Salvar resultados:**

    py portscan.py -t 127.0.0.1 -o resultado.txt

**Visualizar todos os comandos:**

    py portscan.py --help

## ⚙️ Parâmetros

| Comando | Descrição |
|---------|-----------|
| `-t` | IP ou domínio alvo |
| `--timeout` | Timeout em milissegundos |
| `--threads` | Quantidade de threads |
| `-o` | Salvar resultados |
| `--top-10k` | Verificar portas da lista Top 10K |
| `-h` | Mostrar ajuda |

## 🖥️ Exemplo de resultado

    [ PINGING ON DOMAIN... ]

    Domain  = 127.0.0.1
    Timeout = 118.72 ms
    Threads = 30

    [ RESULTS ]

    [+] 80    → Open
    [+] 443   → Open
    [+] 8080  → Open

    [#] 3 Open ports

*Exemplo ilustrativo: os resultados dependem
dos serviços disponíveis no alvo*

## ⚠️ Aviso legal

Esta ferramenta foi disponibilizada para
fins educacionais, testes de conectividade
e auditorias de segurança autorizadas

Utilize somente em sistemas próprios ou
com permissão explícita do responsável

O desenvolvedor não se responsabiliza
pelo uso indevido da ferramenta

## 👨‍💻 Créditos

**Personalização e interface:** VICTOR

**Linguagem:** Python

**Projeto:** Victor PortScan

Caso utilize código de terceiros, mantenha
os créditos e respeite a licença original

---

<div align="center">

### 🔴 VICTOR PORTSCAN

**Developed with Python | by VICTOR**

</div>
