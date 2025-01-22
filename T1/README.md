# Projeto e Implementação de um Compilador.


## Trabalho 1 (T1): Análise Léxica

## Como gerar o seu analisador léxico executável

Assume-se que os arquivos necessários estão na pasta T1/_src_ do repositório: 
```comp.l``` e ```main.c```.
O arquivo _compl.l_ deve especificar tokens, padrões regulares e ações para
a análise léxica. 

O script ```compile.sh``` roda o flex e gera o executável na pasta acima de```src```.
Bastar rodar:

```
./compile.sh
```
ou
```
make compile
```

## Como executar

Assume-se que o nome do analisador léxico executável) é  _compl_.
O programa _compl_ deve ler a entrada a partir de um arquivo com  extensão _.in_ 
e escrever a saída em outro arquivo, com extensão _.out_.


```
$ ./compl <arquivo>.in <arquivo>.out
```

## Como testar

Use o script ```run_tests.sh``` para testar seu analisador léxico.
Colocar os programas de entrada, com extensão ```.in``` na 
pasta ```tests/inputs```, 
e o oráculo, arquivos com extensão ```.out```,  na pasta ```tests/oracle```.

A saída gerada por seu analisador léxico deve ser colocada em ```tests/outputs```.

```
$ ./run_tests.sh  # comando para rodar os casos de testes em /tests
```


