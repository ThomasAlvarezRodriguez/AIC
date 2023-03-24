On ne peut pas garder toutes les colonnes, un choix s'opère donc. 
Nous scindons les colonnes restantes dans plusieurs dataframes :
Data, dataframe général, possédant "eventid","iyear","imonth","iday","extended","resolution","country_txt","region_txt","provstate","city","success", "suicide","attacktype1_txt", "targtype1_txt","targsubtype1_txt","natlty1_txt","gname","nperps","claimed","weaptype1_txt","weapsubtype1_txt","nkill","nwound","dbsource"
geo, dataframe ayant pour but la géolocalisation, comprenant "eventid", "latitude", "longitude"
headlines, dataframe comprenant les descriptions. "eventid","summary"
