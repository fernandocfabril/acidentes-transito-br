# Avalização Final da Disciplina de Mineração de Dados - Hub de Inteligência Artificial - Turma 8 - Sescoop

## Criar um ambiente virtual
Criar um ambiente virtual para instalar as bibliotecas e executar o projeto.  
Nesse projeto utilizei o pacote **Anaconda**.  
Para criar o ambiente virtual deve utilizar o comando ```conda```
```python
conda create -n <nome_ambiente> python=3.13
```
Para criar o ambiente virtual com o python utilize o comando abaixo:
```python
python -m venv venv
```

## Ativar o ambiente virtual
Utilizando o pacote **Anaconda**
```python
conda activate <nome_ambiente>
```

## Instalar as bibliotecas

O arquivo *requirements.txt* contém todas as bibliotecas necessárias para utilizar no projeto.  
Para instalar execute o comando abaixo.
```python
pip install -r requirements.txt
```

## Abrir o notebook com o Jupyter
```python
jupyter notebook
```

## Insights  
* Em um mesmo acidentes tiveram 95 pessoas envolvidas:  
Pesquisando pela internet sobre o assunto, achei uma reportagem sobre esse acidente: [Veículos engavetam em grave acidente na BR-277, em Balsa Nova; PRF diz que pelo menos cinco pessoas morreram](https://g1.globo.com/pr/parana/noticia/2023/09/02/grave-acidente-br-277.ghtml)  
Inclusive na reportagem fala em 7 mortes, mas depois a PRF corrigiu para 5.  
Na reportagem fala em 50 veículos envolvidos no acidente e nesse dataset consta 131 veículos.  

* Correlação entre as variáveis númericas
  - Correlação Forte:  
    Feridos com Feridos Leves.  
    Ilesos com Pessoas.  
    Veiculos com Ignorados.  

  - Correlação Moderada:  
    Feridos Leves com Pessoas e Feridos Graves.  
    Feridos com Pessoas.  
    Veiculos com Pessoas.  
* A causa de acidente com mais acidente é **"Reação tardia ou ineficiente do condutor"**

* Acidentes na cidade de Maringá/PR
  *  Nos dias de Semana acontece mais acidentes do que no final de semana.  
  * No Sábado e Sexta-Feira são os 2 dias com mais acidentes, em números e percentualmente.
  * Os números de acidentes são maiores em PLENO DIA e PLENA NOITE, respectivamente.  



