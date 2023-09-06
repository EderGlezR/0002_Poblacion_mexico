# dist_pob_mx
#Distribución de la población por municipio en México

#Librerias

import geopandas as gpd

import matplotlib.pyplot as plt

import libpysal as ps

import shapefile

from shapely.geometry import shape

import osr

import pandas as pd

import numpy as np

from mpl_toolkits.axes_grid1 import make_axes_locatable

#Archivos
shp_path="C:/Users/g_onz/Box/07 Proyectos de Data/001 shape/Municipios/"  #Ruta hacia el Shape de los archivos

graph_path="C:/Users/g_onz/Box/07 Proyectos de Data/001 shape/Municipios/" #Ruta para guardar mapas

file="Municipios"  #Archivo de Shape
