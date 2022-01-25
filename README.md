# hilalpy
A package to analyse the data of Moon sighting for lunar crescent visibility criterion


#Hilalpy
import hilalpy

#Input File
path = 'C:/Users/USER/OneDrive - Universiti Malaya/PhD/References/Source of Moon Sighting Report/Raw Data/Final Data/Final.csv'
figure = 'C:/Users/USER/OneDrive - Universiti Malaya/PhD/References/Source of Moon Sighting Report/Raw Data/Final Data/figure1.jpg'
errorratetotal = "C:/Users/USER/OneDrive - Universiti Malaya/PhD/References/Source of Moon Sighting Report/Raw Data/Final Data/Errorrate.csv"
x = 'ArcV'
y = 'ArcL'
conditionx = 3
conditiony =6.4
limitx = 20
limity = 20

hilalpy.cond (path,figure,errorratetotal,x,y,conditionx,conditiony,limitx,limity)
