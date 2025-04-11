<h1 align='center'>
Online Site  <a href="https://mincetur-romellfudi.glitch.me"><img src="https://cdn.glitch.com/2bdfb3f8-05ef-4035-a06e-2043962a3a13%2Fview-source%402x.png" alt="view source" height="30"></a>
</h1>

# Peru Ministerio de Comercio y Turismo

[![](snapshot/intro.jpg#splash)](https://www.mincetur.gob.pe/)

## Data Science for Peruvian Government study

### By Romell Domínguez
[![](https://raw.githubusercontent.com/romellfudi/assets/master/favicon.ico)](https://www.romellfudi.com/)

### You can also view online via:

#### ARRIBO-> [![NBViwer](https://img.shields.io/badge/display-nbviwer-blue.svg)](http://nbviewer.jupyter.org/github/romellfudi/MinCeTur/blob/master/arribo/arribo.ipynb) [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/romellfudi/MinCeTur/master?filepath=arribo/arribo.ipynb) [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/romellfudi/MinCeTur/blob/master/arribo/arribo.ipynb)

#### FLUJO TURISTA-> [![NBViwer](https://img.shields.io/badge/display-nbviwer-blue.svg)](http://nbviewer.jupyter.org/github/romellfudi/MinCeTur/blob/master/flujo_turista/flujo_turista.ipynb) [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/romellfudi/MinCeTur/master?filepath=flujo_turista/flujo_turista.ipynb) [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/romellfudi/MinCeTur/blob/master/flujo_turista/flujo_turista.ipynb)

#### MOVIMIENTO GENERAL-> [![NBViwer](https://img.shields.io/badge/display-nbviwer-blue.svg)](http://nbviewer.jupyter.org/github/romellfudi/MinCeTur/blob/master/movimiento_general/movimiento_general.ipynb) [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/romellfudi/MinCeTur/master?filepath=movimiento_general/movimiento_general.ipynb) [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/romellfudi/MinCeTur/blob/master/movimiento_general/movimiento_general.ipynb)

#### OFERTA HOTELERA-> [![NBViwer](https://img.shields.io/badge/display-nbviwer-blue.svg)](http://nbviewer.jupyter.org/github/romellfudi/MinCeTur/blob/master/oferta_hotelera/oferta_hotelera.ipynb) [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/romellfudi/MinCeTur/master?filepath=oferta_hotelera/oferta_hotelera.ipynb) [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/romellfudi/MinCeTur/blob/master/oferta_hotelera/oferta_hotelera.ipynb)

#### PERNOCTACIONES-> [![NBViwer](https://img.shields.io/badge/display-nbviwer-blue.svg)](http://nbviewer.jupyter.org/github/romellfudi/MinCeTur/blob/master/pernoctaciones/pernoctaciones.ipynb) [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/romellfudi/MinCeTur/master?filepath=pernoctaciones/pernoctaciones.ipynb) [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/romellfudi/MinCeTur/blob/master/pernoctaciones/pernoctaciones.ipynb)

#### VISITANTES A SITIOS TURÍSTICOS-> [![NBViwer](https://img.shields.io/badge/display-nbviwer-blue.svg)](http://nbviewer.jupyter.org/github/romellfudi/MinCeTur/blob/master/visitantes_a_sitios_turisticos/visitantes_a_sitios_turisticos.ipynb) [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/romellfudi/MinCeTur/master?filepath=visitantes_a_sitios_turisticos/visitantes_a_sitios_turisticos.ipynb) [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/romellfudi/MinCeTur/blob/master/visitantes_a_sitios_turisticos/visitantes_a_sitios_turisticos.ipynb)

## Requirements

* [Python 3.6](https://www.python.org/downloads/release/python-360/)
* [Jupyter Notebook](http://jupyter.org/)

## Folder Structure

The project is organized as follows:

```
_config.yml          # Configuration file for the Jekyll theme, used for customizing the website layout and settings
LICENSE              # License information for the project
README.md            # Project documentation, including an overview and instructions
requirements.txt     # Python dependencies required to run the notebooks and scripts

_layouts/            # HTML layout templates for the website
  default.html       # Default layout template used across the site

arribo/              # Analysis of tourist arrivals to lodging establishments in Peru
  arribo.ipynb       # Analysis of monthly/yearly trends, domestic vs. international visitor patterns, seasonal visitation patterns, and predictive models
  arribo.png         # Snapshot image for visualization
  rptaniomes_a.xls   # Data file for monthly arrivals
  rptaniomes_b.xls   # Data file for monthly arrivals by national visitors
  rptaniomes_c.xls   # Data file for monthly arrivals by international visitors
  rptaniomest_a.xls  # Data file for regional arrivals
  rptaniomest_b.xls  # Data file for regional arrivals by national visitors
  rptaniomest_c.xls  # Data file for regional arrivals by international visitors

assets/              # Static assets for the project
  css/               # Stylesheets for the website
    style.scss       # Main stylesheet for customizing the website's appearance

flujo_turista/       # Analysis of international tourist flows and economic impact
  flujo_turista.ipynb # Analysis of foreign exchange earnings, tourist arrivals through entry points, migration patterns by country, and future forecasts
  flujo_turista.png  # Snapshot image for visualization

movimiento_general/  # Analysis of passenger movement at Peruvian airports
  movimiento_general.ipynb # Comparison of passenger traffic across key airports, domestic vs. international patterns, and seasonal trends in air traffic
  movimiento_general.png  # Snapshot image for visualization

oferta_hotelera/     # Analysis of lodging infrastructure across Peru
  oferta_hotelera.ipynb # Analysis of lodging establishments by region, room and bed-place capacity, and future infrastructure growth forecasts

pernoctaciones/      # Analysis of overnight stays in Peruvian lodging
  pernoctaciones.ipynb # Analysis of overnight stays by domestic and international tourists, regional distributions, and seasonal occupancy patterns
  pernoctaciones.png # Snapshot image for visualization

snapshot/            # Snapshot images used in the project
  intro.jpg          # Introductory image for the project
  promperu.png       # PromPeru logo used in the documentation

visitantes_a_sitios_turisticos/ # Analysis of visitor trends to specific tourist sites in Peru
  visitantes_a_sitios_turisticos.ipynb # Analysis of visitor numbers to key cultural attractions, seasonal patterns, and long-term trends in site popularity
  visitantes_a_sitios_turisticos.png  # Snapshot image for visualization
```

Each notebook not only analyzes historical tourism data but also implements time series forecasting models to predict future trends, providing valuable insights for tourism planning and development in Peru.

## Resources

[![](snapshot/promperu.png#favico) ](https://www.promperu.gob.pe/TurismoIN/estadisticasEnLinea/)

## License

MIT. See the LICENSE file for the copyright notice.

**2018, October**


<style>
img[src*='#splash'] { 
    width:700px;
    display: block;
    margin: auto;
}
</style>
