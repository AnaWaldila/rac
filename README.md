# RAC Version 1.0

## Introduction

RAC, "Reservatório de Águas de Chuva" (name in Portuguese, Rainwater Water Tank) is a desktop software thats calculates the water tank's volume based on each Rio de Janeiro's neighborhood and user's water consume in their home. The software can calculate all non potable water, investment cost for the project and the time history to return the investment. 
The software was developed with Visual Basic computational language and was used the Visual Studio 2015 platform.

## Software

The software starts with a principal menu and the user can choose between 6 buttons: "Dimensionamento de Reservatório" (water tank design), "Sobre o Rio de Janeiro" (about Rio de Janeiro's City), "Custo de Implantação" (cost), "Sistema de Coleta de Águas Pluviais" (Collecting rainwater system), "Utilizando o Programa" (using the software) and "Sobre o Programa" (about the software), like Figure 1 shows:

<div>
<img src="Figures/RAC - 01.png" width="40%">
</div>
<p>
 <b>Figure 1:</b> RAC - Principal Window
</p>

First button "Dimensionamento de Rservatório" opens a new window with some informations to introduce:

* "Bairros do Distrito do Rio de Janeiro", Neighborhoods of Rio de Janeiro's City - The user choose only one
* "Área do telhado", Roof's area (m²)
* "Área do jardim", Gardens's area (m²)
* "Número de dias que lava o jardim por mês", Number of times the user clean the garden per month
* "Número de carros", Number of cars
* "Número de lavagens (lavagens/mês)", Number of times the user clean the car per month
* "Área de limpeza", cleaning area (m²)
* "Numero de limpezas (limpezas/mes)", Number of times the user clean the house with water (for instance, bathroom, kitchen)
* "Número de pessoas na edificação", Number of persons in house.
* "Tipo de Válvula", toilet valve: The user choose between "Valvula Hidra",hydra valve, or "Caixa Acoplada", toilet-coupled box.
* "Inflação anual", annual inflation. The default is 6.9% per year (Brazil, 2016). If the user can put another one, only select the option "Desejo usar outro valor", i.e, I want to user another value.

All informations above can see in Figure 2.

<div>
<img src="Figures/RAC - 02.png" width="100%">
</div>
<p>
 <b>Figure 2:</b> RAC - Design water tank Window
</p>

Finaly, with all informations entered in textboxes, some results are presented to user. Next, translate to English:

"<b>Water Tank</b>

Your consumption of non-potable water (in liters) per month is: <b>[here the user's consume value]</b>.

Based on our calculus method, water tank's volume is (in liters) is: <b>[here the water tank's average  volume]</b>.

We suggest the water tank (in liters): <b>[here a suggestion about water tank]</b> .

First Flush's volume is: <b>[here the first flush's volume]</b>.

<b>Cost</b>

For a flume's avarage length, <b>[here the flume's value]</b> meters, the cost is <b>[here the cost of the flume, based on cost in Brazil, 2016]</b>.  

For a vertical conductor's length, <b>[here the vertical conductor's value]</b>, the cost is <b>[here the cost of the vertical conductor, based on cost in Brazil, 2016]</b>.

For a horizontal conductor's length, <b>[here the horizontal conductor's value]</b>, the cost is <b>[here the cost of the horizontal conductor, based on cost in Brazil, 2016]</b>.

The cost of water tank is <b>[here the value of the water tank]</b>.

All cost is <b>[here the value of the design and implementation]</b>.

<b>Payback Time</b>

For the neighborhood and a consume of <b>[here the consume of non-potable water]</b>, CEDAE's tariff is <b>[here the CEDAE's tariff based on Rio de Janeiro 2016]</b>.

The annual inflation considered is (%): <b>[here the inflation considered by the user]</b>

The payback time is (years): <b>[here the time in years]</b>"

Figure 3 show all this results

<div>
<img src="Figures/RAC - 03.png" width="100%">
</div>
<p>
 
 
 <b>Figure 3:</b> RAC - Result Window
</p>
