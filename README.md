# Curso de Django Web Framework e Django Rest Framework (DRF)

Django Web Framework e Django Rest Framework com Python, HTML e CSS.<br>
Este repositório é uma extensão do [Curso de Python](https://github.com/luisitcho/curso-python-otavio-2023)

## 📌 Gerenciando Dependências com ```requirements.txt```
O arquivo ```requirements.txt``` lista todas as bibliotecas necessárias para o projeto. Para garantir que todos os pacotes corretos sejam instalados, siga os passos abaixo.

### 🔹 Como Criar o ```requirements.txt```
Para gerar um ```requirements.txt``` com todas as dependências instaladas no ambiente, execute:
```
pip freeze > requirements.txt
```
Isso salvará a lista de pacotes e suas versões no arquivo.


### 🔹 Como Instalar as Dependências
Para instalar todas as bibliotecas listadas no ```requirements.txt```, use:
```
pip install -r requirements.txt
```

### 🔹 Exemplo de ```requirements.txt```
Um ```requirements.txt``` pode conter pacotes com ou sem versões fixas:
```
Django
requests==2.31.0
numpy>=1.21.0,<1.25
```

* Sem versão: Instala sempre a versão mais recente (```Django```).
* Versão fixa: Garante que a instalação seja exatamente aquela (```requests==2.31.0```).
* Faixa de versões: Permite atualizações dentro de um intervalo (```numpy>=1.21.0,<1.25```).