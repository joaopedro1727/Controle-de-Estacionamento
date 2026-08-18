# 🚗 Sistema de Controle de Estacionamento

Sistema desenvolvido em **Python** com interface gráfica em **Tkinter** para gerenciar um estacionamento. O projeto permite cadastrar clientes, controlar entradas e saídas de veículos, realizar cobranças, gerar relatórios e exportar dados em PDF.

## Funcionalidades

- Cadastro de clientes
- Edição e exclusão de clientes
- Registro de entrada e saída de veículos
- Cálculo automático do valor da permanência
- Controle de pagamentos
- Relatórios de clientes e movimentações
- Ranking dos 5 clientes mais frequentes
- Geração de gráfico
- Exportação de relatórios em PDF
- Armazenamento dos dados em banco SQLite

## Tecnologias Utilizadas

- Python 3
- Tkinter
- SQLite3
- Matplotlib
- FPDF
- Datetime

## Instalação

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
```

2. Instale as dependências:

```bash
pip install matplotlib fpdf
```

3. Execute o projeto:

```bash
python main.py
```

> Caso o arquivo principal tenha outro nome, substitua `main.py` pelo nome correto.

## Estrutura do Projeto

```
📁 Projeto
│
├── main.py
├── estacionamento.db
├── README.md
└── demais arquivos
```

## Banco de Dados

O sistema cria automaticamente o arquivo **estacionamento.db**, contendo as tabelas:

- Clientes
- Movimentações

## Autor

João Pedro