# Mineração de dados hidrológicos para a agricultura

Material da disciplina Mineração de dados hidrológicos para a agricultura
da Pós-Graduação em Recursos Hídricos da UFES (Lato Sensu).

## Instalação do ambiente de trabalho

Instalar o gerenciador de pacotes Python
[Miniconda](https://docs.anaconda.com/free/miniconda/) no computador. Depois de 
instalado, abrir o programa *Anaconda Prompt (miniconda3)*, e executar:

1. Primeira opção:

   `conda create -n gee`

   `conda activate gee`

   `conda install geemap geopandas -c conda-forge`

2. Segunda opção

   `conda create -n gee python=3.10`

   `conda activate gee`

   `conda install -n base mamba -c conda-forge`

   `mamba install geemap -c conda-forge`

   `mamba install geopandas localtileserver -c conda-forge`

## Abrindo Jupyter notebook

Os códigos acima criam a ambiente de trabalho denominado 
*gee*, com as bibliotecas necessárias instaladas.
Uma vez instalado o ambiente, para abrir o **Jupyter-lab**, vá
no  *Anaconda Prompt (miniconda3)*  e escreve:

`jupyter-lab`

Caso tenha fechado o *Anaconda Prompt (miniconda3)*. Abra-o
novamente e escreva no seu Prompt:

`conda activate gee`

`jupyter-lab`





