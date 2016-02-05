Weekly Intake - controle semanal de calorias
============================================

Layout
------
Header + duas colunas, uma mais estreita que a outra.

### Header
Um logotipo legal, nome do projeto e subtítulo. Por enquanto, não há necessidade de menu

### Coluna da esquerda
Um formulário pequeno, com um campo de data e um input numérico, além do botão de submit.

### Área principal
Uma tabela onde serão exibidos os registros armazenados.

Funcionalidades
---------------

- o usuário poderá armazenar diversos registros, diários, contabilizando quantas calorias ele consumiu naquele dia;
- o armazenamento será feito, inicialmente, na sessão do usuário (`session_start()` + `$_SESSION`)
- a tabela exibirá todos os registros armazenados:
  - ordenados por data, da mais recente para a mais antiga
  - a cada semana (entre o domingo e a segunda) deve haver uma linha adicional, com o sumário da semana, indicando a média de calorias consumidas por dia naquele intervalo
