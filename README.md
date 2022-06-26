# RAC Version 1.0

## Introduction

RAC, "Reservatório de Águas de Chuva" is a desktop software that calculates the volume of the reservoir based on the water consumption of each neighborhood in Rio de Janeiro and the user in their residence. The software calculates all non-potable water and the cost for the project. The software was developed in Visual Basic computational programming and the Visual Studio 2015 platform was used.

## Software

The software starts with a main menu and the user can choose one of 6 buttons: "Dimensionamento de Reservatório" (reservoir design), "Sobre o Rio de Janeiro" (about the city of Rio de Janeiro), "Custo de Implantação" (cost), "Sistema de Coleta de Águas Pluviais"" (Rainwater Collection System), "Utilizando o Programa" (using the software) and "Sobre o Programa" (about the software), as shown in Figure 1:

<div>
<img src="Figures/RAC - 01.png" width="40%">
</div>
<p>
 <b>Figure 1:</b> RAC - Principal Window
</p>

First button "Dimensionamento de Reservatório" opens a new window with some pieces of informations to input:

* "Bairros do Distrito do Rio de Janeiro", Neighborhoods of Rio de Janeiro's City - The user chooses only one;
* "Área do telhado", Rooftop's area (m²);
* "Área do jardim", Gardens's area (m²);
* "Número de dias que lava o jardim por mês", Number of days the user washs the garden per month;
* "Número de carros", Number of cars;
* "Número de lavagens (lavagens/mês)", Number of days the user cleans the car per month;
* "Área de limpeza", cleaning area (m²);
* "Numero de limpezas (limpezas/mes)", Number of times the user cleans the house with water (for instance, bathroom, kitchen etc);
* "Número de pessoas na edificação", Number of people in house.
* "Tipo de Válvula", toilet valve: The user chooses between "Valvula Hidra", hydra valve, or "Caixa Acoplada", toilet-coupled box.
* "Inflação anual", annual inflation. The default is 6.9% per year (Brazil, 2016). If the user puts another one, only selects the option "Desejo usar outro valor", i.e, "I want to user another value".

All pieces of information above is shown in Figure 2.

<div>
<img src="Figures/RAC - 02.png" width="100%">
</div>
<p>
 <b>Figure 2:</b> RAC - Design reservoir Window
</p>

Finaly, with all pieces of information, some results are presented to the user. Next, translated to English:

"<b>Reservoir</b>

Your consumption of non-potable water (in liters) per month is: <b>[here the user's consume value]</b>.

Based on our method, reservoir's volume is (in liters): <b>[here the reservoir's volume]</b>.

We suggest the reservoir (in liters): <b>[here a suggestion about reservoir]</b> .

First Flush's volume is: <b>[here the first flush's volume]</b>.

<b>Cost</b>

For a flume's avarage length, <b>[here the flume's value]</b> meters, the cost is <b>[here the cost of the flume, based on cost in Brazil, 2016]</b>.  

For a vertical conductor's length, <b>[here the vertical conductor's value]</b>, the cost is <b>[here the cost of the vertical conductor, based on cost in Brazil, 2016]</b>.

For a horizontal conductor's length, <b>[here the horizontal conductor's value]</b>, the cost is <b>[here the cost of the horizontal conductor, based on cost in Brazil, 2016]</b>.

The cost of reservoir is <b>[here the value of the reservoir]</b>.

All cost is <b>[here the value of the design and implementation]</b>.

<b>Payback Time</b>

For the neighborhood and a consume of <b>[here the consume of non-potable water]</b>, CEDAE's tariff is <b>[here the CEDAE's tariff based on Rio de Janeiro, 2016]</b>.

The annual inflation considered is (%): <b>[here the inflation considered by the user]</b>

The payback time is (years): <b>[here the time in years]</b>"

Figure 3 shows all this results.

<div>
<img src="Figures/RAC - 03.png" width="100%">
</div>
<p>
 
 <b>Figure 3:</b> RAC - Result Window
</p>

Also that, the user can export all result in a .txt file.

Returns to the main window, all the other buttons present an explanation about the cost, in the city of Rio de Janeiro, water collection system, using the software and about the software (as explained above). All of this has explanations in Portuguese.

Figure 4 shows all horizontal and vertical donor, reservoir, system accessories, and system installation costs. Methods on how to calculate these costs and how to calculate consumption of non-potable water are presented.

<div>
<img src="Figures/RAC - 04.png" width="100%">
</div>
<p>
 
 <b>Figure 4:</b> RAC - System Implementation Cost Window
</p>

"Sobre Rio de Janeiro" explanations are given about ALERTA RIO and how to collect a database to design the reservoir in software. Entire database based on the hydrometeorological conditions of the city of Rio de Janeiro. Then Figure 5 shows this:

<div>
<img src="Figures/RAC - 05.png" width="100%">
</div>
<p>
 
 <b>Figure 5:</b> RAC - Rio de Janeiro's City Window
</p>

The "Sistema de Coleta de Água", or Water Collection System, presents a litter pieces of information about how the user can collect rainwater and its importance. Then Figure 6 shows this:

<div>
<img src="Figures/RAC - 06.png" width="100%">
</div>
<p>
 
 <b>Figure 6:</b> RAC - Water Collect System Window
</p>

"Utilizando o Software", or Using Software, explains how to use RAC software and input data to design a reservoir and its system. Figure 7 shows this:

<div>
<img src="Figures/RAC - 07.png" width="100%">
</div>
<p>
 
 <b>Figure 7:</b> RAC - Using Software Window
</p>

Finally, Figure 8 shows about the software, the University, developer and professor:

<div>
<img src="Figures/RAC - 08.png" width="70%">
</div>
<p>
 
 <b>Figure 8:</b> RAC - About the Software Window
</p>

## References

Jacob, R.V.B, Junior, A.A.O.,Siciliano, W.C., Reis, A.W.Q.R, Oliveira, I.T. Dias consecutivos secos para estivativa de volumes de aproveitamento de águas pluviais em períodos de estiagem na cidade do Rio de Janeiro. 10° Simpósio Brasileiro de Captação e Manejo, Belem-Pa, 2016.

JACOB, RAYSSA VOGELER BERQUÓ ; OHNUMA JR, ALFREDO AKIRA ; SICILIANO, WILLIAN CAMPOS ; REIS, ANA WALDILA DE QUEIROZ RAMIRO ; OLIVEIRA, ISRAEL TIAGO DE . CONSECUTIVE DAYS DRIED TO ESTIMATED OF RESERVOIRS FOR RAINWATER HARVESTING IN DROUGHT PERIODS IN RIO DE JANEIRO CITY. ITEGAM- Journal of Engineering and Technology for Industrial Applications (ITEGAM-JETIA), v. 3, p. 185-189, 2017.

## Information About the Software

Rio de Janeiro State University

Faculty of Engineering

Developer: Ana Waldila de Queiroz Ramiro Reis

Professors: Alfredo Akira Ohnuma Junior

Contact: anawaldila@hotmail.com

Project website: https://projetosapuerj.com/rac/
