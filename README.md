# Bachelor-Thesis
UvA 2025 Business Analytics Thesis


This repository consists of 2 models of the Thesis: an excel file with a scenario analysis for SAF break-even point and a pyton file with the scenario and sensitivity analysis.

1)In the excel model all the parameters are clearly described and shown in tables as well as the Year-on-Year projection of Emissions' cost given by the delta of emissions times the Social Cost of Carbon. In this file the break-even formula is written in slightly different fashion than the one used in the thesis: the cost of Conventional Jet Fuel is moved to the right-hand side of the equation to make it easier to manipulate data and scenarios ( check equation (2) of Thesis for reference of formula). This allows the user to easily change all variables in use at any time, create dashboards or create new scenarios following the existing framework.

2)The python file is structured in a way that when used in google-colab or anaconda-notebook style one has a clear idea of the sections and what the functions are doing: the first cell contains essential variables and break-even function, then every cells contains a different analysis (i.e., scenario analysis, scc sensitivity, wtp sensitivity and growth-rate sensitivity). Each cell contains the corresponding mathematical function and the plotting function.

