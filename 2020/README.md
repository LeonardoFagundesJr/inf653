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

## 10. Testes com thrust

[Video da Aula](https://www.youtube.com/playlist?list=PLcvOyD_LMr6n1wZQe3m37o5qnrtwwd-9u)

[Doc Nvidia](https://docs.nvidia.com/cuda/thrust/index.html)

[Secao Thrust do MiniCurso WSCAD 2019](https://colab.research.google.com/drive/17IslqFWtsMhYXqOaeA8vP6cRgmDpkJGM?usp=sharing)
Ir na secao Thrust.

1. Leonardo - Criar um colab separado. Fazer a tabela SORT (executar 3 vezes) com os campos: tamanho vetor, tempo, tempo transfer, Sort/s, GPU. Se possivel executar em 2 GPU com os tamanhos: 1M,2M, ....ate' maximo que a GPU e Thrust permitir.  Fazer o teste para INT, FLOAT e DOUBLE. 

2. Lucas - Buscar um Sort em CPU (codigo Radix ou Quicksort) para comparar  - [link](https://cs.stackexchange.com/questions/3/why-is-quicksort-better-than-other-sorting-algorithms-in-practice)

3. Westerley - Comparar o Thrust Transformer com um kernel de polinomio para equacoes com 10, 15 e 20 ops.

4. Leonardo - fazer um colab para comparar a REDUCAO do Thrust com o codigo do Capitulo 4 do reduction com Unroll. vetores de tamanho 16M-64M

5. Lucas - fazer uma funcao Count em CUDA e comparar com o desempenho do [Thrust](https://docs.nvidia.com/cuda/thrust/index.html)

6. Westerley - fazer codigo em CUDA para thrust::is_sorted e comparar com thrust. 





## 11. Testes com Convolução

1. Ler a seção de convolução do Livro Cuda Beginner Guide Pagina 277.
2. [slide do curso de Stanford cs231n](http://cs231n.stanford.edu/slides/2020/lecture_5.pdf)
3. [apostila do curso Cs231n](https://cs231n.github.io/convolutional-networks/)
4. [Alexnet](https://github.com/pratikpv/alexnet/blob/master/GPU/cuda/alexnet_host.cu)
5. [Alexnet pytorch](https://github.com/dansuh17/alexnet-pytorch/blob/d0c1b1c52296ffcbecfbf5b17e1d1685b4ca6744/model.py#L40)

### Tarefas 
 1. Colab: Versão CPU versus versão GPU v1 (pagina 278) versus v3 (pagina 282-84), 
 2. Colab: versao naive matriz 227x227x3 com 96 chamadas de filtros 11x11x3 (camada 1 da alexnext) usando "v3"
 


## 12. Stencil Registros e Memoria Compartilhada

[Video da Aula](https://www.youtube.com/playlist?list=PLcvOyD_LMr6n1wZQe3m37o5qnrtwwd-9u)

[Artigo clássico](http://developer.download.nvidia.com/CUDA/CUDA_Zone/papers/gpu_3dfd_rev.pdf)

1. Leonardo - Fazer este problema no Matlab e medir o tempo. Stencil 3D. Sequencial 0, 1, 2..  256\*256\*256 = 16M
2. Lucas - Versao em CPU com FOR e usar flag vetorizacao (AVX) e OpenMP (k40) para ver ser paraleliza automatico
3. Westerley - Versao em GPU naive com FOR em "z" e comparar com a versao do artigo

Fazer o calculo de Stencil 25p/s.



[Seleção de artigos](https://docs.google.com/presentation/d/1UzVE37XMght3-beY0wmbBvZjbMtJp50diNAI3FssW8I/edit?usp=sharing)


1. Comparar com uma implementação naive, mudar janela, adaptar para convolução.









