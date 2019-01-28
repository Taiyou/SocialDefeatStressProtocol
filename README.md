# SocialDefeatStressProtocol
This repository describes social defeat stress protocol and the social interaction test at OIST, specially A366 in Lab 1 level A.

I summarized the protocol in benchling.
[Repeated social defeat stress protocol](https://benchling.com/s/prt-1sqpXXYvAsB73vCYdM2W)

## MATLAB codes:
```
makeList.m
getCoordinates.m
SI_Hgraph.m
```

`SI_Hgraph` generates heatmaps of object and social interaction.


## Example1
```MATLAB
>> datapath = '/your_directory/SampleData/control';
>> SI_Hgraph(datapath);
```
A heatmap of object interaction
![Imgur](https://i.imgur.com/flfOaKM.png)

A heatmap of social interaction
![Imgur](https://imgur.com/XHzewyP.png)

## Example2
```MATLAB
>> TestSDandCont
```
A boxplot contrasting social interaction score in the repeatedly socially defeated model and control groups.
![Imgur](https://imgur.com/a/PAjdpG1.png)

Furthermore, please check codes by yourself.
