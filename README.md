
<img loading="lazy" src="https://github.com/Glaubernaoli/PCD---GenomeIdentifier/assets/172425065/bcfc56a4-b124-4988-88b4-e860cb438f27" width=800>

</div>

<h1 align="center"> Predição da eficiência de energia renovável usando Redes Neurais </h1>

### Tarrasque, Turma 2024
###  Enzo Januzzi, Glauber Nascimento de Oliveira e Raquel de Godoy Vianna
###  Redes Neurais e Algoritmos Genéticos -  Prof. Dr. Daniel Cassar

 <h4 align="center"> 
     Educational Purpouse
</h4>

<p align="center">
<img loading="lazy" src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/>
</p>

<h2 align="left"> 💡 Descrição </h2>

<div align="justify">
 
 A busca pela sustentabilidade vem crescendo cada vez mais no contexto atual de mudanças climáticas, com o uso de materiais poluentes e não degradáveis por grandes indústrias, o que afeta o ecossistema global. Nesse sentido, estudar sistemas renováveis, como as energias solares, hidroelétricas, entre outros, é de suma importância, visando compreender seus componentes e potencial para aplicação em larga escala, substituindo gradativamente as fontes não renováveis. [1,2]
 
 
  Nesse sentido, combinar técnicas de ML com o Aprendizado Profundo (Deep Learning, ou DL) é uma estratégia interessante para estudar os sistemas de energia, sendo possível fazer previsões para os parâmetros desses sistemas e otimizá-los. Um exemplo de DL são as redes neurais, como a Multi Layer Perceptron (MLP), cuja arquitetura varia para cada parâmetro considerado. [3] Logo, o objetivo deste projeto é identificar e otimizar os hiperparâmetros de uma rede neural do tipo MLP para resolver um problema de regressão de interesse científico.
</div>

<h2 align="left"> 🏹 Target </h2>

<div align="justify">

Buscamos prever dois targets, `Storage_Efficiency_Percentage` e `GHC_Emission_Reduction_tCO2e`, sendo o primeiro a eficiência de armazenamento de energia em porcentagem e o segundo a redução das emissões de gases do efeito estufa (em tCO2e).

</div>


<h2 align="left"> 📔 Notebooks e arquivos do projeto </h2>

<div align="justify">

`energy_dataset_.csv`: Dataset usado no trabalho.
 
`Introdução.ipynb`: Neste notebook, estão todos os códigos necessários para rodar o modelo, seu treinamento e o cálculo das métricas.

`Otimização_hiperparâmetros_RN.ipynb`: Neste notebook, estão todos os códigos necessários para a otimização dos hiperparâmetros pelo Optuna e o teste do melhor modelo retornado.

`hiperparâmetros_RN.db`: Dados da ominização do Optuna 

</div>

<h2 align="left"> 🤖 Modelo Usado </h2>

<div align="justify">

 `Rede Neural Perceptron Multicamadas`: É uma rede neural com uma ou mais camadas ocultas com números indeterminados de neurônios em cada camada oculta.

 `Optuna`: É um otimizador automático de hiperparâmetros.

<!--
<div>

<h2 align="left"> 🧰 Métricas Usadas </h2>

<div align="justify">

`RMSE`: ...

`popopoo`: métrica...

`pupupu`: métrica...

`blibliblub`: métrica...

</div>

</div>
-->


<h2 align="left"> 📁 Acesso ao projeto </h2>

<div align="justify">

Você pode acessar o código pelo github ou, preferencialmente, baixá-lo.

</div>

<h2 align="left"> 🛠️ Abrir e rodar o projeto </h2>

<div align="justify">

Depois de baixar o projeto você deve abrí-lo no Jupyter Notebook/VS code

</div>

<h2 align="left"> 📓 Linguagens e programas usados </h2>

<div align="justify">

`Python`, `Jupyter Notebook`, `VS Code`, `Math`, `Scikit Learn`, `Numpy`, `Pandas` , `Torch`, `Optuna`

</div>

<h2 align="left"> 📖 Referências </h2>

<div align="justify">


1. [Programa das Nações Unidas para o Desenvolvimento. (2024, 25 de abril). What is the sustainable energy transition and why is it key to tackling climate change? Climate Promise.](https://climatepromise.undp.org/news-and-stories/what-sustainable-energy-transition-and-why-it-key-tackling-climate-change)
2. [Organização das Nações Unidas. (s.d.). Renewable energy – Powering a safer future.](https://www.un.org/en/climatechange/raising-ambition/renewable-energy)
3. [Alharbi, A. H., Khafaga, D. S., Zaki, A. M., M., S., Ibrahim, A., Abdelhamid, A. A., Eid, M. M., Khodadadi, N., Abualigah, L., & Saeed, M. A. (2024). Forecasting of energy efficiency in buildings using multilayer perceptron regressor with waterwheel plant algorithm hyperparameter. Frontiers in Energy Research, 12, 1393794.](https://doi.org/10.3389/fenrg.2024.1393794)

</div>


<h2 align="center"> :octocat:  Autores </h2>

<div align="center">

|  [<img loading="lazy" src="https://github.com/user-attachments/assets/0c4d1ac3-f05b-499f-8618-bfaf749b3504" width=115><br><sub>Glauber Nascimento</sub>](https://github.com/Glaubernaoli)<br> [<sub>Currículo Lattes</sub>](http://lattes.cnpq.br/0913262665776521)<br> [<sub>Linkedin</sub>](https://www.linkedin.com/in/glauber-naoli/) |  [<img loading="lazy" src="https://github.com/Glaubernaoli/PCD---GenomeIdentifier/assets/172424999/b5e432b6-bf0c-42a1-88c3-68df3c7d7545" width=115><br><sub>Enzo Januzzi</sub>](https://github.com/EnzoJanuzzi)<br> [<sub>Currículo Lattes</sub>](http://lattes.cnpq.br/1031555112242239)<br> [<sub>Linkedin</sub>](https://www.linkedin.com/in/enzo-januzzi-xavier-9063842b0/?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) | [<img loading="lazy" src="https://github.com/user-attachments/assets/abf88829-f67d-4d53-8a36-0bf7d70d21e4" width=115><br><sub>Raquel de Godoy Vianna</sub>](https://github.com/RaquelGVianna)<br> [<sub>Currículo Lattes</sub>](https://lattes.cnpq.br/7590950936353244)<br> [<sub>Linkedin</sub>](https://www.linkedin.com/in/raquel-de-godoy-vianna-58b5b92a7?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) | 
| :---: | :---: | :---: |

 <h2 align="center"> :octocat:  Orientador </h2>

<div align="center">

| [<img loading="lazy" src="https://github.com/user-attachments/assets/463d4753-7fa4-4a42-aa54-409e4150bb51" width=115><br> <sub> Prof. Dr. Daniel R. Cassar </sub>](https://github.com/drcassar)<br> [<sub>Ilum - CNPEM</sub>](https://ilum.cnpem.br/)<br> [<sub>Currículo Lattes</sub>](http://lattes.cnpq.br/1717397276752482) |
| :---: |

<div align="center">


![ILUM, CNPEM, MINISTÉRIO DA EDUCAÇÃO](https://github.com/Glaubernaoli/PCD---GenomeIdentifier/assets/172425065/6c9216ea-0cdb-4dac-aac5-445d505b2804)
