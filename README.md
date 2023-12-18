# Projeto Bolt

## Descrição

Bolt é um Robô Assistente Inteligente desenvolvido para realizar uma variedade de tarefas automatizadas, interagindo com o ambiente por meio de um Arduino e um sistema de reconhecimento de voz.

## Pré-requisitos

Antes de iniciar, certifique-se de que os seguintes requisitos estão atendidos:

- Python 3.x instalado
- Pip (gerenciador de pacotes do Python) instalado
- Arduino IDE instalado (para monitoramento de portas)

## Configuração do Ambiente

### Clonando o Projeto

Clone o repositório do projeto para sua máquina local usando o comando:

```bash
git clone https://github.com/Gustavo-LabzStudio/intelirobot/tree/main
```

### Configurando a Virtual Environment (venv)

A virtual environment (venv) permite gerenciar separadamente as dependências do projeto.

1. Navegue até a pasta do projeto:
   ```bash
   cd src
   ```
2. Crie a venv dentro da pasta `src`:
   ```bash
    python3 -m venv .
   ```
3. Ative a venv:
   ```bash
   source Scripts/activate
   ```

### Instalando Dependências

As dependências são necessárias para o funcionamento do projeto.

1. Certifique-se de que a venv esteja ativada e você esteja na pasta `src`.
2. Instale as dependências utilizando o pip:
   ```bash
   pip install -r requirements.txt
   ```

   Em caso de falha na instalação de alguma dependência, tente instalá-la manualmente.

## Executando o Projeto

### Preparação do Hardware

Antes de executar o software, conecte o Arduino e o microfone do robô às portas USB do computador.

1. Verifique e anote a porta USB na qual o Arduino está conectado. Isso pode ser feito através do Arduino IDE, em `Ferramentas -> Porta`.
2. No código, confira e ajuste a porta no construtor do monitor serial, por exemplo: `COM3`, `COM4`.

### Executando o Software

Com o ambiente configurado e o hardware conectado, execute o projeto:

```bash
python main.py
```

## Contribuições

- **Gustavo Ferreira** - Técnico em Informática - Estudante de Engenharia de Computação no INTELI - @gustavofdeoliveira
