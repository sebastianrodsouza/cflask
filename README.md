# Script de Criação de Aplicação Flask MVC

O script "cflask" é um shell script escrito em zsh que tem como objetivo criar a estrutura básica de uma aplicação Flask no padrão mvc com alguns arquivos e diretórios pré-definidos.



# Requisitos
Para executar o script "cflask" é necessário ter o zsh instalado e configurado em seu ambiente. Além disso, é necessário ter o Flask instalado em sua máquina.

O script é chamado `cflask` e requer o nome da aplicação como argumento.


## Como usar

Para usar o script "cflask", siga os passos abaixo:

1. Abra o terminal e navegue até o diretório onde deseja criar a aplicação Flask.
2. Execute o comando `cflask <nome_da_aplicação>`, onde "nome_da_aplicação" é o nome que deseja dar à sua aplicação.
3. Após a execução do script, a seguinte estrutura básica da sua aplicação Flask será criada no diretório atual.

```
my_projeto/
├── myapp/
│   ├── controllers/
│   │   ├── __init__.py
│   │   ├── main_controller.py
│   │   └── user_controller.py
│   ├── models/
│   │   ├── __init__.py
│   │   ├── main_model.py
│   │   └── user_model.py
│   ├── templates/
│   │   ├── base.html
│   │   ├── index.html
│   │   ├── user_list.html
│   │   └── user_detail.html
│   └── __init__.py
├── config.py
├── run.py
└── requirements.txt
└── requirements-dev.txt
└── README.md
└── .gitignore
└── Makefile
```

# Autor
Sebastian Rodrigues

