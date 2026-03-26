# Exercício de CI

Este repositório contem um exercício para implementação de um pipeline de CI.

## Tarefas

1. Faça um fork do repositório e clone-o na sua máquina.

2. Rode os testes usando o unnitest do Python.
```
$python -m unittest -v
```
3. Crie um pipeline de CI (GitHub Action) que inclua o download das dependências, o uso de um linter (ex.: flake8) e a execução dos testes. Isso tudo em duas versões do Python (ex.: 3.11 e 3.12).

Documentação: [GitHub Actions Docs](https://docs.github.com/en/actions/get-started/quickstart)

4. Faça o push para o repositório remoto e certifique-se de que a action rodou com sucesso.

5. Adicione um teste para verificar se o método `list_users` retorna a lista ordenada por e-mail. Isso deve falhar... 

6. Faça outro push para o repositório e verifique a action rodando com falha.

7. Então, implemente essa ordenação até que o novo teste passe localmente. Em seguida, faça um push final e veja a action rodando com sucesso.


