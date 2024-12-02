# Tratamento de Dados de Tomografia por Técnicas de Álgebra Linear Computacional

Equipe de estudantes: *Emanuel Piveta Pozzobon, Henrique Valente Nogueira, Pedro Coelho Gimenes de Freitas e Rafael Dalacorte Erdmann*

*Ilum - Escola de Ciência, 2024*

*Prof. Dr. Vinicius Francisco Wasques*

Este repositório compila o trabalho final da disciplina de Álgebra Linear Computacional, onde o grupo explorou as questões matemáticas da Tomografia Computadorizada. Aqui encontra-se: um relatório escrito em formato pdf, diagramado em LaTeX conforme modelo disponibilizado pelo professor, e dois cadernos Python, onde analisa-se a reconstrução de imagens tomográficas e a comparação de métodos iterativos. 

O caderno principal cumpre duas funções: explica como utilizar a biblioteca ```Tomopy``` para reconstruir imagens tomográficas a partir de dados reais, extraídos do repositório ```TomoBank``` e explica nossa implementação do algoritmo de Técnicas de Reconstrução Algébrica (TRA, também conhecido como método de Kaczmarz) conforme descrito por Anton & Rorrers (2012). Os resultados obtidos não obtiveram a exatidão esperada, resultando em imagens distorcidas.

## Base de dados
[Lorentz](https://tomobank.readthedocs.io/en/latest/source/data/docs.data.lorentz.html) e [Nano CT Ângulos Esparsos](https://tomobank.readthedocs.io/en/latest/source/data/docs.data.nano.html). Ambas estão disponíveis no repositório [```TomoBank```](https://tomobank.readthedocs.io/en/latest/index.html).

## Bibliotecas utilizadas
- ```Tomopy```
- ```DXchange```
- ```NumPy```
- ```SciPy```
- ```MatPlotLib```

## IA Generativa
Neste trabalho, houve utilização de Chat GPT 4.0 (licença gratuita de uso diário limitado) para auxílio nos códigos.
