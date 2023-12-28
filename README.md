# Python - Project with study and improvement goals
    Python project, to seek improvement and cadence in the language. The idea is to evolve project structuring and API concepts.

## some tips
Generate requirements.txt, more: (https://www.dataside.com.br/dataside-community/linguagem-de-programacao/metodos-para-gerar-o-requirements-txt-do-seu-projeto-em-python)

pip freeze > requirements.txt


## general installs (requirements.txt)
pip3 install -r requirements.txt 

### envs
    python3 -m venv env
    source ./env/bin/activate

## start
uvicorn run:app --reload

### TODO - checklist

- [x] implement first get endpoint with Hello World
- [ ] Implement service with Hello World
- [ ] Implement tests on the endpoint and service
- [ ] configure database connection
- [ ] implement user CRUD module



#### Referências:
https://fastapi.tiangolo.com/tutorial/first-steps/
https://github.com/zhanymkanov/fastapi-best-practices