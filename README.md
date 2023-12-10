# Sprint IV - Qualidade de Software, Segurança e Sistemas Inteligentes

Este projeto conciso é parte integrante do material de estudo da Sprint **Software de Excelência, Segurança e Sistemas Avançados**.
O projeto envolve o registro de informações pessoais de pessoas que realizaram o teste para covid. É possível obter detalhes sobre o paciente e o diagnóstico.
A intenção é demonstrar o conteúdo abordado na na Sprint IV.



## Backend -Procedimento de Execução

Instalar todas as libs python listadas no `requirements.txt`.
Copiar o repositório para uma pasta local e executar os comandos abaixo pelo terminal após entrar no diretório do repositório:

1- Criar uma virtualenv
```
python -m venv env
```

2- Ativar a virtualenv
```
env\Scripts\Activate
```

3- Instalar as bibliotecas do arquivo requirements.txt 
```
(env)$ pip install -r requirements.txt
```

4- Executar a API:

```
(env)$ flask run --host 0.0.0.0 --port 5000
```
5- Após uma mudança no código fonte:

```
(env)$ flask run --host 0.0.0.0 --port 5000 --reload
```

6 - Abrir o [http://localhost:5000/#/](http://localhost:5000/#/) no navegador para verificar o status da API em execução.

## Frontend - Procedimento de Execução

1- Rodar a API localmente de acordo com as instruções da API.

2- Abrir o arquivo index.html no seu browser.

