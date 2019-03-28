# Overwatch-League

This project is to display the data of the Professional Overwatch League teams and how they perform when they are either on the Home team or the Away team. From the data we will be able to see exactly how well each team is performing compared to the others and be able to see that difference shown in two different percentage pie charts and in a side-by-side bar chart.

import sqlite3 
import csv
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

The abbreviations of the Professional Overwatch teams are:
ATL Atlanta Reign,	
BOS Boston Uprising,	
FLA Florida Mayhem,
HOU Houston Outlaws,	
LDN London Spitfire,	
NYE New York Excelsior,	
PAR Paris Eternal,	
PHI Philadelphia Fusion,	
TOR Toronto Defiant,
WAS Washington Justice,	
CDH Chengdu Hunters,
DAL Dallas Fuel,
GZC Guangzhou Charge,
HZS Hangzhou Spark,
GLA Los Angeles Gladiators,
VAL Los Angeles Valiant,
SFS San Francisco Shock,
SEO Seoul Dynasty,
SHD Shanghai Dragons,
VAN Vancouver Titans,
