---
title: "Análisis habitacional"
header-includes:
   - \usepackage{pdfpages}
   - \usepackage[default]{open sans}
   - \usepackage[T1]{fontenc}
   - \usepackage{graphicx}
   - \usepackage{fancyhdr}
   - \usepackage{hyperref}
   - \usepackage{xcolor}
   - \usepackage{sidecap}
   - \usepackage[spanish]{babel}
   - \pagestyle{fancy}
   - \renewcommand{\headrulewidth}{0pt}
   - \fancyhead{}
   - \setlength{\headheight}{23pt}
   - \lhead{\includegraphics[width=7cm,height=140cm]{"./logos/logo_oecc.pdf"}}
   - \fancyfoot{}
   - \lfoot{\includegraphics[width=5.0cm,height=140cm]{"./logos/muni.jpg"}}
   - \rfoot{\thepage}
   - \definecolor{graycustom}{HTML}{7b7b7e}
   - \usepackage{floatrow}
   - \floatsetup[figure]{capposition=top}
   - \renewcommand{\arraystretch}{1.5}
   - \usepackage{svg}
   - \usepackage{amsmath}

mainfont: Open Sans
output: 
  pdf_document: default
  keep_tex: true
includes:
fig_caption: yes

html_document:
    df_print: paged
---













# Régimen de tenencia habitacional de los hogares
Para el análisis del régimen de tenencia habitacional de los hogares en la Ciudad de Corrientes se utilizara como unidad de análisis al jefe de hogar.
La elección de esta unidad de análisis se realiza para disminuir las distorsiones que puede generar la correlación entre niveles de hacinamiento y el régimen de tenencia de las personas. 

\begin{table}[!h]

\caption{\label{tab:unnamed-chunk-7}Porcentaje de hogares en la Ciudad de Corrientes S/ régimen de tenencia habitacional}
\centering
\begin{tabular}[t]{lr}
\toprule
Régimen de tenencia & Porcentaje\\
\midrule
\cellcolor{gray!6}{Inquilino} & \cellcolor{gray!6}{21.18\%}\\
Irregular & 10.96\%\\
\cellcolor{gray!6}{Propietario} & \cellcolor{gray!6}{67.86\%}\\
\bottomrule
\end{tabular}
\end{table}

Como se puede ver en la tabla 1, el 67.86% de los hogares en la Ciudad de Corrientes son propietarios de sus viviendas, mientras que el 32.14% se encuentran en situaciones de inquilinato u ocupación irregular.

## Régimen de tenencia habitacional según el género del jefe/a de hogar

La jefatura de hogar de cada nucleo familiar puede estar a cargo de hombres o mujeres. A continuación se realiza el análisis del régimen de tenencia según el género del jefe/a del hogar.

![](habitacional_files/figure-latex/unnamed-chunk-8-1.pdf)<!-- --> 
Cómo se puede ver en el gráfico x, las familias que tienen como jefa de hogar a una mujer son mas propensas a no ser propietarias de su vivienda y a encontrarse en condiciones de inquilinato que aquellas en las que el jefe de hogar es un hombre. 

## Régimen de tenencia habitacional según la edad del jefe de hogar

La edad del jefe de hogar puede condicionar el acceso a una vivienda propia, siendo que la posibilidad de acumulación de ahorros es una función del ingreso percibido a lo largo de la vida laboral.

A continuación se presenta el acceso a la vivienda para los distintos rangos etarios.

![](habitacional_files/figure-latex/unnamed-chunk-9-1.pdf)<!-- --> 
En el gráfico se puede ver como la tenencia de una vivienda propia va disminuyendo conforme es menor la edad de la persona que es jefe/a de hogar. Para las familias compuestas por jefes/as de hogar jóvenes en la Ciudad de Corrientes es mucho mas probable que se encuentren habitando una vivienda que es alquilada o esta siendo ocupada de manera irregular.

## Régimen de tenencia habitacional según la incidencia en la pobreza del jefe de hogar

La pobreza, especificamente la capturada a través del método de la linea de la pobreza, intenta captar la incapacidad coyuntural de satisfacción de las necesidades básicas de las familias. Estar por debajo de la linea de la pobreza indica una situación de vulnerabilidad económica que puede ser medida en un momento determinado, sin embargo, la pobreza estructural es considerablemente más nociva a nivel de marginación social que la pobreza coyuntural. La falta de seguridad habitacional no solamente se limita a la incapacidad temporal de satisfacer necesidades básicas, sino que presenta un problema estructural de incapacidad en la satisfacción de  los derechos básicos de las personas. 

Para analizar la seguridad habitacional de las personas pobres y no pobres, medidas según el método de la linea de la pobreza, se presenta a continuación el régimen de tenencia de las viviendas según la incidencia en la pobreza del jefe/a de hogar.

![](habitacional_files/figure-latex/unnamed-chunk-10-1.pdf)<!-- --> 

En el gráfico x se puede ver una particularidad, la proporción de propietarios de la vivienda en los casos que el jefe de hogar es pobre es mayor que en el caso de los no pobres.
Por otro lado, los pobres tienen una mayor proporción de ocupación irregular que los no pobres, en donde se incluyen casos como ocupación de viviendas, de terreno, etc.



