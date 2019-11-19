# WinningEleven-2002-Database-Update-From-FIFA2020
WE2002 Database Update From FIFA2020.

Este pequeño tutorial de ejemplo para leer la base de datos de **Winning Eleven 2002** convertida desde **FIFA2020** en formato del archivo <strong><em> Excel.</em></strong>.

**Nota:** El archivo es creado por **PoliPoli** de la comunidad de ZonaWe

## Ejemplo con Python Pandas read_excel to Import Excel File

```
import pandas as pd
datos=pd.read_excel('we2020.xlsx' ,header=0)
print(datos['Name'])
print(datos['Club'])

```

Resultado de la lectura
![Winning Eleven Database update 2002](https://i.ibb.co/dmykZ8N/winningeleven2002.png)

## Ejemplo con Python Conectar con las formulas de mcr db to mcr de PoliPoli

```
import pandas as pd
datos=pd.read_excel('mcr-db-to-mcr.xls' ,sheet_name=6 )
print(datos)

```

Resultado de la lectura
![Winning Eleven Database update 2002](https://i.ibb.co/rG1cBcJ/winningeleven.png)


## Otro ejemplo Python Conectar con las formulas de mcr db to mcr de PoliPoli


```
import pandas as pd
datos=pd.read_excel('mcr-db-to-mcr.xls')
df1 = pd.read_excel(datos, sheet_name='Editar')
df2 = pd.read_excel(datos, sheet_name='Formulas')
df3 = pd.read_excel(datos, sheet_name='Jugadores')

```
