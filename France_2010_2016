import csv
import numpy as np
import pandas as pd
import unidecode
import seaborn as sns
import matplotlib.pyplot as plt
#df=pd.concat(map(pd.read_csv,["data/d1.csv","data/d2.csv","data/d".csv"]))
#from os import listdir
#filepaths=[f for f in listdir("./data") if f.endswith('.csv')]
#df=pd.concat(map(pd.read_csv, filepaths))
with open("Mortalite_2010.csv", encoding='utf8', errors='ignore') as fh:
    lines=fh.readlines()
    list_lines=[]
    for line in lines:
        line=line.rstrip("\n")
        line=line.split(";")
        print(line)
        list_lines.append(line)
print(list_lines)
print(list_lines[3])
annee=list_lines[3]
a=str(annee)[7:-2]
a=int(a)
b=int(list_lines[7][12])+int(list_lines[7][13])+int(list_lines[7][14])+int(list_lines[7][15])
b=int(b)
c=int(list_lines[8][12])+int(list_lines[8][13])+int(list_lines[8][14])+int(list_lines[8][15])
c=int(c)
d=int(list_lines[9][12])+int(list_lines[9][13])+int(list_lines[9][14])+int(list_lines[9][15])
d=int(d)
s1=pd.Series([a,b,c,d], index=["année","Homme>65","Femme>65","Total>65"], name='décès asthme')
s1
print(s1)
