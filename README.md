# hello-world!

#### This is "Cido" from my first git project!

    alias = 'ls -lrt'


# Programa ASTERISCO

 Programa criado para fins de estudo pessoal sobre a linguagem de programaÃ§Ã£o C. 
 
 Baseado no Livro **"Primeiro Curso de Programação em C " ** - Editora Visual Books - Autor:  ** Edson Luiz França Senne **.
 
 ![Alt text](img/livroCapa.jpeg) ![Alt text](img/livroContracapa.jpeg)
 
 Criei dois códigos fontes para a mesma finalidade porém por caminhos diferentes.
 
 Este programa foi criado para resolver o seguinte problema:
 
 Exercício 7 (Página 94) - Exibir os seguintes padrões, onde todos os asteriscos (\*) devem ser impressos por uma Ãºnica instrução da forma printf("\*"):


A) 
```
*
**
***
****
*****
******
*******
********
*********
**********
```

B)
```
**********
*********
********
*******
******
*****
****
***
**
*
```

C)
```
**********
 *********
  ********
   *******
    ******
     *****
      ****
       ***
	**
	 *
```

D)
```
         *
	**
       ***
      ****
     *****
    ******
   *******
  ********
 *********
**********
```

# Instruções de como compilar este programa

## Pré-requisitos

 * Ter o GCC instalado
 * Sistema operacional Windows / Linux / MacOSX

 Via linha de comando, entrar no diretorio onde estÃ£o localizados os códigos fontes e executar o comando abaixo:

    gcc asterisco.c -o asterisco1
    gcc asterisco2.c -o asterisco2


OBS: Caso prefira, utilize sua IDE de preferencia, ** lembrando que todos os códigos fontes devem estar no mesmo diretório **.


# Instruções para execução do programa depois de compilado

  Executar o comando seguido de um sinal de menos (-) e a letra do exercício.

## Windows

    ASTERISCO1.EXE <-a -b -c -d>
    
    ASTERISCO2.EXE <-a -b -c -d>

## Linux / Mac

    ./asterisco1 <-a -b -c -d>
   
    ./asterisco2 <-a -b -c -d>

## Exemplos de execução

  Para exibir o resultado do exercício (a):

 * **Windows**
 
 1. Abrir um terminal de comamndo (**CMD**);
 2. Entrar no diretorio onde os programas foram compilados;
 3. Executar o comando abaixo:

         ASTERISCO1 -a

 * **Linux / Mac**
 
 1. Abrir um terminal de comamndo;
 2. Entrar no diretorio onde os programas foram compilados;
 3. Executar o comando abaixo:


        ./asterisco1 -a

## Executáveis pré-compilados

  Se quiser somente executar o programa para ver os resultados, já¡ disponibilizei junto com os códigos fontes os executáveis compilados para Windows, Linux e MacOSX conforme lista abaixo, basta baixar e executar:

*  **Windows**

       ASTERISCO.EXE
       ASTERISCO2.EXE

* **Linux**

      asterisco1-linux
      asterisco2-linux
 
*  **MacOSX**

       asterisco1-mac
       asterisco2-mac

