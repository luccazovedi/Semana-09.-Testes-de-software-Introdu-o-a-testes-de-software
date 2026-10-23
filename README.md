# Testes de software

## Arquivos

- `aluno.py`: define a classe `Aluno`.
- `turma.py`: cadastra alunos e calcula as notas maior e menor.
- `main.py`: executa um exemplo do programa.
- `testes.py`: contém os testes automatizados.

## Como executar

Tenha o Python 3 instalado e execute:

```bash
python main.py
```

Para executar os testes:

```bash
python -m unittest testes.py
```

Notas menores que 0 ou maiores que 10 são ignoradas no cálculo da maior e da
menor nota.
