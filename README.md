# AT

Calculadora de arcos de transição desenvolvida em C. Inclui um parser e um avaliador de expressão booleana.
A entrada deve ser dada em forma de soma de produtos. Exemplo: `'a*b + !a*c'`

## Como utilizar

### No Linux
é necessário ter o `git` e o `gcc` instalados
1) faça `clone` do repositório e acesse o diretório `AT`
```
$ git clone https://github.com/gckneip/AT.git
$ cd AT
```
2) compile
```
$ make
```
3) execute o programa, passando a expressão booleana como argumento de execução

**OBS:** utilize aspas simples para evitar o processamento indevido do caracter "!"
```
$ ./AT 'a*b+!a*c'
```

### No Windows
é necessário ter o `git` e o `minGW` instalados e configurados na variavel `PATH` do sistema
1) faça `clone` do repositório e acesse a pasta `AT`
```
$ git clone https://github.com/gckneip/AT.git
$ cd AT
```
2) compile
```
$ mingw32-make
```
3) execute o programa, passando a expressão booleana como argumento de execução

**OBS:** utilize aspas simples para evitar o processamento indevido do caracter "!"
```
$ ./AT 'a*b+!a*c'
```
