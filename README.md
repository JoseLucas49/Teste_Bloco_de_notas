# Teste_Bloco_de_notas
projeto Teste de bloco de notas a espera de aprovação.

Sobre o Projeto Teste Bloco de Notas:

Este é um projeto simples de um bloco de notas feito em Python para um trabalho da faculdade. Ele permite criar e gerenciar notas, e tem testes para verificar se tudo funciona.
Regras de Negócio

Cada nota precisa ter um título e um texto.
Não pode ter duas notas com o mesmo título.
O texto da nota não pode estar vazio.
As notas ficam na memória enquanto o programa roda.

O que você precisa:

Python 3.13 ou mais novo.
Programas: pytest e pytest-cov (para os testes).

Como usar a aplicação

Crie um ambiente virtual:
textpython -m venv venv
.\venv\Scripts\activate

Instale o que precisa:
Crie um arquivo requirements.txt com:
textpytest
pytest-cov

Instale:
textpip install -r requirements.txt

Rode o programa (exemplo básico):
textpython src/notes.py
(Ajuste se precisar de um comando diferente.)

Como rodar os testes

Ative o ambiente virtual (se usou):
text.\venv\Scripts\activate

Rode os testes:
textpython -m pytest --cov=src tests/ --cov-report=term

Para ver um relatório colorido:
textpython -m pytest --cov=src tests/ --cov-report=html

Abra htmlcov/index.html no navegador.

Obs: como eu tive alguns problemas no meu Noteboock eu Compactei ele e enviei, Sinceramente terminei ficando com toque ao crialo.
