# PortScan

![Python](https://img.shields.io/badge/Python-3.x-blue)
![License](https://img.shields.io/badge/License-MIT-green)

O **PortScan** é uma ferramenta de verificação de hosts e portas escrita em Python. Ele permite verificar se os hosts listados em uma planilha Excel estão ativos (respondem ao comando `ping`) e verifica se portas específicas (22, 80, 443, 3040, 5001) estão abertas nesses hosts. O uso de threads torna o processo rápido e eficiente.

---

## Funcionalidades

- Verifica a disponibilidade de hosts usando o comando `ping`.
- Verifica se as portas específicas (22, 80, 443, 3040, 5001) estão abertas.
- Utiliza threads para acelerar a verificação de hosts e portas.
- Exibe os resultados de forma organizada, com cores para facilitar a leitura.
- Suporta arquivos Excel como entrada para a lista de hosts.

---

## Requisitos

- **Python 3.x**: O script foi desenvolvido para Python 3.
- **Bibliotecas Necessárias**:
  - `openpyxl`: Para ler arquivos Excel.
  - `colorama`: Para adicionar cores ao terminal.
  - `socket`: Para verificar portas e resolver DNS.
  - `subprocess`: Para executar o comando `ping`.
  - `threading`: Para executar tarefas em paralelo.

Instale as bibliotecas necessárias com o comando:

```bash
pip install openpyxl colorama
