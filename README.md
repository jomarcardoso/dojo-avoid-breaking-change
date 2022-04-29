# Como evitar uma breaking change

O desafio de depreciar de uma forma mais suave.

## Formas de evoluir mantendo ambas as implementações

Como avisar que uma forma ou versão está depreciada e que o usuário deve atualizar para a nova.

- crie versões: v1, v2...
- evolua a nomenclatura, aproveite quando é algo diferente
- trocar o nome do antigo, exemplo UNSAFE_ do react

### Versões

Discaradamente avise que existe uma nova versão e assim que puderem, atualizem para ela. Já deixa avisado que a versão anterior está depreciada e poderá ser removida.

### Novo nome

Muitas vezes o que é está sendo feito novo não é uma substituição exata do antigo, as vezes substitui, mas faz menos ou mais coisas, então da para aproveitar isso e dar um nome diferente e ambos coexistirem por um tempo.

### Renomear o antigo

Se o nome é muito bom e queremos manter ele para a nova implementação, então mudamos o nome do antigo com um prefixo ou sufixo "OLD" OU "DEPRECATED".

## Formas de ajudar

- criar ferramenta de atualizar
