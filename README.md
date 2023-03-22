# ML
import pandas as pd
df= pd.read_csv('https://raw.githubusercontent.com/dataprofessor/data/master/delaney_solubility_with_descriptors.csv')
df

y=df['logS']
print(y)
