# tikv_metric  
Group Member：   
xiejiandong, hunterlxt, tier-cap  

Background:  
Sometimes, we want to optimise delay of tikv; but we don't know the detail delays in the Tikv flow steps;  
As the same purpose, we want to optimise memory use of tikv, we want to know volumn of memory used in the Tikv models;  
  
Project Goal:  
We will add delay and memory metric to tikv,  
it will provide the better way to analyse the bottleneck of tikv;  

Project Design:  
1、Analyse Tikv codes;  
2、Add statistic codes to fetch the metric data;  
3、Metric datas will be pushed to promisuse as usual. we can see them on the grafana board;  

Progress:  
1、We begin to analyse the codes of tikv; 30%  
