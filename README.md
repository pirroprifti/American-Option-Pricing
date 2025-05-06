<h1>American Options: Least Squares Monte Carlo</h1>

<h2>Description</h2>
This project implements the Least Squares Monte Carlo (LSMC) method introduced by Longstaff and Schwartz (2001) to price American-style options, which require solving an optimal stopping problem. The project compares the LSMC approach against both the Black-Scholes closed-form solution and Monte Carlo simulation for European options. Additionally, the algorithm's estimates are evaluated for accuracy and convergence. This work was developed for a graduate-level statistics course in Monte Carlo methods, but is intended to serve as a foundational piece for further exploration in quantitative finance, including derivative pricing, simulation methods, and computational statistics. The repository includes a R Quarto file with the code and write up which is what is used to render the PDF file that contains a comprehensive analysis, commentary, and development of theory.
<br />

<h2>Languages Used</h2>

- <b>R</b>

<h2>Program walk-through:</h2>

<p align="left">
1.) Make sure the .RData file is in your working directory<br/>

<br />
2.) Run the file and test out the functionalities and valuation methods. Click render to compile to pdf (included in repository). Some example cases are provided in the .qmd file. <br/>

<br />
Note: If chosing to not use the saved simulation in the .RData file, comment out the line of code that loads in the .RData file and run as normal. Be warned, this evaluation simulation takes around 15 minutes to run. That is why the .RData was created.

</p>
