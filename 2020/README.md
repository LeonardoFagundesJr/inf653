# Atividades nos Colabs

## [1. Hello World, Blocos e Threads](https://colab.research.google.com/drive/1INsl6NddQSyR-O8I2ivKWB3bmP1T20NN?usp=sharing)

1. Lucas - Tabela Placas, Codigo Multiplos Threads e Blocos (não tem limite blocos, ao usar um int para random limita maximo Blk*thr) - Feito.

## [2.Alocacao Memoria e Soma de Vetores](https://colab.research.google.com/drive/1R_DOeVF2_N_Fjrry-cK7WVifVw3a37xE?usp=sharing#scrollTo=bhp-cmJnyI1c)

1. Leonardo transferencia GPU-CPU tabela - Feito. 
1. Ruan - Tempo de execução tabela - ???

## [3. Intensidade Aritmetica (Polinomios)](https://colab.research.google.com/drive/1w_G16IwUZVhMzvU-uWpjGx965gkzByoO?usp=sharing) [Video](https://youtu.be/0Upfm1wktRE) - [Ler seçao 1.1 do capitulo do Mini-Curso do WSCAD 2019](https://sol.sbc.org.br/livros/index.php/sbc/catalog/view/46/200/414-2)

1. Ruan - Exercicio 1,2,
1. Leonardo - Exercicio 4

Caso não seja uma T4, aproveitar para fazer o exercicio 3 e 5.

## [4. Mais trabalho por Thread](https://colab.research.google.com/drive/1CgR9VjmzA_9RLtTaRk1NhHlkJatqTl_f?usp=sharing)

1. Leonardo - Exercicio 1 T3 e T4
2. Ruan -  Exercicio 1 T5 e T6
3. Lucas - Exercicio 1 a parte do FOR.

[Ruan e Leonardo _ Video para Mais trabalho, latencia e Multiplicacao Matrizes](https://www.youtube.com/playlist?list=PLcvOyD_LMr6l2OmlneylIx8OR9MbpQ-jM)

### latencia
1. Leonardo - Exercicio 3 - L1 e L2 para T1 e T2 
2. Ruan - Exercicio 3 - L3 e L4 para T1 e T2 
3. L3 e L4 para T3 e T4 Lucas
4. L5 e T2,T4 e T6 Westerley

## [5. Multiplicação de Matrizes](https://colab.research.google.com/drive/11PgsBNA-5Q8A3Kuy6QQINzoiKJKrYX_y?usp=sharing)

1. Ruan - versão CPU com ladrilhos, exercicio 1. Na GPU memcpy Exercicio 2. [memcpy Volvok](https://bitbucket.org/rvuduc/volkov-gtc10/src/master/memcpy_k.cu)
2. Leonardo - exercicio 3 com 2 threads (compilar com nvcc -arch=sm_XX -Xptxas -v, para ver qtos registros para 1 ponto e 2 pontos por thread)
3. Lucas - exercicio 3 com 4 threads
4. Westerley - exercicio 3 com 8 threads

## [6. Capitulo 2 - Cuda C Professional Programming - Soma de Matrizes](https://colab.research.google.com/drive/12gSlJmMHrUOQyZDg8Io9gptJ2_dckSNp?usp=sharing#scrollTo=esfCfLsZ5QRV)

1. Leonardo - Exercicio 1 (cap2) [video](https://www.youtube.com/watch?v=uzE6ztaVjTw&list=PLcvOyD_LMr6lZ35IJrqjeF1bUex6Jd7Rh&index=1)

## [7. Capitulo 3 - Cuda C Professional Programming - Redução ](https://colab.research.google.com/drive/12gSlJmMHrUOQyZDg8Io9gptJ2_dckSNp?usp=sharing#scrollTo=esfCfLsZ5QRV)

1. Ruan- Exercicio 2 (cap3) [video](https://www.youtube.com/watch?v=OuMY259rXW4&list=PLcvOyD_LMr6lZ35IJrqjeF1bUex6Jd7Rh&index=3)

## 8. Explorando exemplos do Github da Nvidia

### Objetivo executar os codigos no Colab.
Sugestão é baixar os codigos com git para o colab. Navegar na pasta, compilar os exemplos e ver quais sao os parametros que podem ser explorados e dizer quais sao os exemplos que sua pasta tem.

### Alocacao das Pastas do Git Nvidia

1. Westerley [00_basic_gemm, 08 e 09](https://github.com/NVIDIA/cutlass/tree/master/examples)

2. Leonardo [biblioteca CuBLASLt](https://github.com/NVIDIA/CUDALibrarySamples/tree/master/cuBLASLt)

3. Ruan - [biblioteca Thrust](Ruan - https://github.com/NVIDIA/thrust)

4. Lucas  [Hash Tables](https://github.com/NVIDIA/cuCollections/tree/dev/benchmarks/hash_table)

5.  Mateus [Processamento de imagens](https://github.com/NVIDIA/CUDALibrarySamples/tree/master/NPP)

## 9. Geração de Código - Kmeans

* [Nvidia](https://github.com/NVIDIA/kmeans)
* [Ver com Michael o geradores do WSCAD 2018](....)









