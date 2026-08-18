# Sistema de Controle de Estacionamento

Um sistema completo para gerenciamento de estacionamentos desenvolvido em Python, com interface gráfica construída em Tkinter, persistência de dados em SQLite3, suporte a geração de relatórios com gráficos (Matplotlib) e exportação em PDF.

## Funcionalidades

O sistema possui uma interface organizada por abas, facilitando a navegação e a gestão:


* Gestão de Clientes (CRUD): Cadastro de clientes (Nome, CPF e Placa), edição de dados cadastrais, exclusão de clientes e listagem de clientes cadastrados.


* Controle de Movimentação: Registro de entrada de veículos gravando data e hora automaticamente, registro de saída com cálculo automático de tempo de permanência e valor total baseado em taxa por hora, além de histórico de todas as movimentações.


* Cobrança: Visualização rápida de recebimentos em aberto e baixa com confirmação de pagamentos.


* Relatórios e Gráficos: Relatório de clientes cadastrados, relatório de recebimentos pendentes e efetuados (com cálculo do valor total recebido), e gráfico de barras dos Top 5 clientes frequentes.


* Exportação PDF: Emissão e download de relatórios detalhados com histórico de pagamentos em formato PDF.



## Tecnologias Utilizadas

* Linguagem: Python 3
* Interface Gráfica: Tkinter / ttk

* Banco de Dados: SQLite3

* Geração de Gráficos: Matplotlib

* Geração de Documentos: FPDF

* Empacotamento: PyInstaller (arquivo de especificação incluso)


## Estrutura do Projeto

sistema_estacionamento.py
sistema_estacionamento.spec
estacionamento.db (gerado automaticamente)
README.md

## Como Executar o Projeto

### Pré-requisitos


Certifique-se de ter o Python 3.x instalado em sua máquina.

### 1. Clonar o repositório

git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)
cd seu-repositorio

### 2. Instalar as dependências

pip install matplotlib fpdf

### 3. Executar a aplicação

python sistema_estacionamento.py

## Como Gerar o Executável (.exe)

Para compilar o projeto em um arquivo executável para Windows usando o PyInstaller:

1. Instale o PyInstaller:
pip install pyinstaller
2. Execute a compilação utilizando o arquivo de especificação existente no repositório:
pyinstaller sistema_estacionamento.spec


3. O executável será gerado na pasta dist.

## Autor

Desenvolvido por João Pedro.