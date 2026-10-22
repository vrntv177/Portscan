 
<div align="center">

<img src="./banner_cyberpunk_victor_portscan.png" width="100%" alt="VICTOR PORTSCAN">

# 🔴 VICTOR PORTSCAN

**Fast & Powerful TCP Port Scanner**

Scanner de portas TCP em Python com interface personalizada

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Platform](https://img.shields.io/badge/Platform-Windows-red?logo=windows)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

**by VICTOR**

---

</div>

## 📌 Sobre o projeto

O **Victor PortScan** é uma ferramenta de análise de portas TCP desenvolvida em Python, voltada para testes de conectividade, estudos de redes e auditorias autorizadas de segurança

Possui interface de terminal personalizada, arte ASCII, suporte a múltiplas threads e identificação de portas abertas

## 🚀 Funcionalidades

- ⚡ Escaneamento rápido de portas TCP
- 🔍 Identificação de portas abertas
- 🌐 Suporte a endereços IP e domínios
- 🧵 Execução com múltiplas threads
- ⏱️ Timeout configurável
- 📂 Exportação de resultados para arquivo
- 🔥 Modo de varredura `--top-10k`
- 🎨 Banner ASCII personalizado com olhos vermelhos
- 💻 Compatível com Windows e PowerShell

## 📥 Instalação

Clone o repositório:

```bash
git clone https://github.com/vrntv177/Portscan.git
```

Acesse a pasta:

```bash
cd Portscan
```

Instale a biblioteca `pythonping` caso sua versão utilize essa dependência:

```bash
py -m pip install pythonping
```

## 💻 Como utilizar

**Escaneamento básico:**

```bash
py portscan_victor.py -t 127.0.0.1
```

**Varredura Top 10K:**

```bash
py portscan_victor.py -t 127.0.0.1 --top-10k
```

**Definir timeout de 240 ms:**

```bash
py portscan_victor.py -t 127.0.0.1 --timeout 240
```

**Utilizar 50 threads:**

```bash
py portscan_victor.py -t 127.0.0.1 --threads 50
```

**Salvar resultados em arquivo:**

```bash
py portscan_victor.py -t 127.0.0.1 -o resultado.txt
```

**Visualizar comandos disponíveis:**

```bash
py portscan_victor.py --help
```

## ⚙️ Parâmetros

| Comando | Descrição |
|---|---|
| `-t, --target` | IP ou domínio do alvo |
| `--timeout` | Tempo limite em milissegundos |
| `--threads` | Número de threads |
| `-o, --output` | Salvar portas abertas em arquivo |
| `--top-10k` | Ativar varredura Top 10K |
| `-h, --help` | Exibir ajuda |

## 📊 Exemplo de resultado

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
```

*Resultado meramente ilustrativo*

## 🔐 Segurança e responsabilidade

Esta ferramenta destina-se exclusivamente a fins educacionais, diagnósticos de conectividade e auditorias autorizadas


Utilize o scanner somente em sistemas próprios ou com autorização explícita de seus responsáveis

Uma porta aberta não significa necessariamente que exista uma vulnerabilidade

## 👨‍💻 Créditos

**Projeto:** Victor PortScan

**Personalização e interface:** VICTOR

**Linguagem:** Python

**Código-base:** Preserve os créditos dos autores originais, quando aplicável

---

<div align="center">

### 🔴 VICTOR PORTSCAN

**Fast • Powerful • TCP Port Scanner**

**Made with Python | by VICTOR**

</div>
