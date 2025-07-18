<h1 align="center">Modelagem Preditiva da Resposta Dielétrica de Perovskitas </h1>
<h2 align="center">Redes Neurais e Algoritmos Genéticos</h2> 

<p align="center">
   Perovskita 
  &nbsp;&bull;&nbsp; Redes Neurais
  &nbsp;&bull;&nbsp; Dielétrica
  &nbsp;&bull;&nbsp; Python
</p>

Autores: Ana Luz Pereira Mendes, Caio Matheus Leão Dantas e Rafael Anis Shaikhzadeh Santos

Orientação: Prof. Dr. Daniel R. Cassar

-----------

<p align="center">
<img loading="lazy" src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/>
</p>

# ❓O que é perovskita?
Perovskita é uma classe de materiais que apresentam propriedades de bastante destaque, como supercondutividade, ferroeletricidade, magnetorresistência e, mais recentemente, alto desempenho em células solares. A estrutura desses compostos é caracterizada por uma fórmula geral do tipo ABX3, em que "A" e "B" são cátions de diferentes tamanhos, enquanto "X" é um âncio  (geralmente oxigênio ou halogênio). 

<p align="center">
  <img src="perovskitagif.gif" alt="Descrição da imagem" width="1000"/>
   
<p align="center">
   Figura 1: Gif da estrutura tridimensional de uma perovskita de fórmula BaTi.
</p>

# 🔬Por que prever a constante dielétrica?
A constante dielétrica (ε) é uma propriedade do material que mede sua capacidade de polarização quando exposto a um campo elétrico. Em outras palavras, trata-se da capacidade de um material formar dipolos elétricos internos em resposta ao campo externo.

Essa propriedade fundamental é muito importante na escolha de materiais para a fabricação de dispositivos eletrônicos. Em capacitores, uma constante dielétrica elevada significa maior capacidade de armazenamento de energia. Já em sensores, maior ε indica maior sensibilidade às variações de campo elétrico.

As perovskitas possuem constantes dielétricas elevadas, o que as torna materiais promissores para a composição desses dispositivos, especialmente em aplicações onde a precisão é crucial, como na bioeletrônica. Além disso, mesmo com pequenos estímulos, as perovskitas promovem grandes respostas estruturais e eletrônicas, aumentando ainda mais sua sensibilidade.

# ✅ Requisitos

<code>Requisitos</code> : [requirements.txt](https://github.com/LuzMendes/Tarrasque/blob/main/requirements.txt)

# 📚 Arquivos e Notebooks

<code>Notebook</code> : [Tarrasque.ipynb](https://github.com/LuzMendes/Tarrasque-Modelagem-Preditiva-da-Resposta-Dieletrica-de-Perovskitas./blob/main/Tarrasque.ipynb)

<code>Fontes de dados</code> : https://datadryad.org/dataset/doi:10.5061/dryad.gq3rg

# 😄 Conclusões

Neste trabalho, foi  realizada a predição da constante dielétrica com base em diversos atributos relacionados à estrutura de perovskitas. Para analisar qual seria a melhor arquitetura a ser utilizada, foi implementado uma otimização que testou diversas combinações de funções de ativação, números de neurônios por camada e taxa de aprendizado. Para diminuir o custo do modelo foi aplicado também uma parada antecipada, acompanhe o gráfico abaixo:

<div align="center">
  <img src="Gráfico_perda_por_arquitetura.jpg" alt="Descrição da imagem" width="1000"/>
</div>

<p align="center">
  Figura 2: Gráfico relacionando a perda do modelo por arquitetura testada para os dados de treino.
</p>


----------
# 👥Colaboradores
| [<img loading="lazy" src="https://avatars.githubusercontent.com/u/172425049?v=4" width=115><br><sub>Ana Luz Pereira Mendes</sub>](https://github.com/LuzMendes)<br>[<sub>Ilum - CNPEM</sub>](https://ilum.cnpem.br/)<br> [<sub>Currículo Lattes</sub>](https://lattes.cnpq.br/4596466138573531) [<sub>Linkedin</sub>](https://www.linkedin.com/in/ana-luz-pereira-mendes/)|[<img loading="lazy" src="https://avatars.githubusercontent.com/u/172424922?v=4" width=115><br><sub>Caio Matheus Leão Dantas</sub>](https://github.com/Caiomld)<br>[<sub>Ilum - CNPEM</sub>](https://ilum.cnpem.br/)<br> [<sub>Currículo Lattes</sub>](http://lattes.cnpq.br/8693036735970868) [<sub>Linkedin</sub>](https://www.linkedin.com/in/caio-matheus-le%C3%A3o-dantas/) | [<img loading="lazy" src="https://avatars.githubusercontent.com/u/172424916?v=4" width=115><br><sub>Rafael Anis Shaikhzadeh Santos </sub>](https://github.com/drcassar)<br> [<sub>Ilum - CNPEM</sub>](https://ilum.cnpem.br/)<br> [<sub>Currículo Lattes</sub>](http://lattes.cnpq.br/1717397276752482) [<sub>Linkedin</sub>](https://www.linkedin.com/in/rafaelanis)| 
| :---: | :---: | :---: | 
