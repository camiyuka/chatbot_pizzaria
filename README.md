# chatbot de uma pizzaria
OBS: não finalizado
Este projeto se concentra na criação de um Chatbot para atender clientes de uma pizzaria!

## Requisitos:
1. Ter alguma dessas versões de **Python** instaladas: versions: `3.7`, `3.8`,` 3.9` and `3.10.`

&nbsp;

OBS: `Python 3.10` é apenas aceito para versões `3.4.x` e acima, além disso, a instalação do Rasa pela Apple Silicon com Python `3.10` não é aceito em `3.4` mas poderá ser utilizado começando na versão `3.5.x`.

2. Instalar Rasa Open Source 


## Como rodar o código na sua máquina:
Instalar a última versão do pip:
```
pip3 install -U pip
```
Criar um ambiente virtual na sua máquina:
```
python -m venv .env
```
Ativar o ambiente virtual:
```
.\.env\Scripts\activate
```
Instalar Rasa Open Source:
```
pip install rasa
 ```
Iniciar Rasa:
```
rasa init
```
Iniciar o chat:
```
rasa shell
```
