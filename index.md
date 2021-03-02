Archery Data
========================================================
author: Mauricio Marcos Fajgenbaun
date: 
autosize: true
transition: rotate
font-import: https://fonts.googleapis.com/css2?family=Ballet&display=swap
font-family: "Ballet"
css: custom.css


Details
========================================================
type: exclaim

In 2002, Heather Tollerud, a Saint Olaf College student, undertook a study of the archery scores of
students at the college who were enrolled in an archery course. Students taking the course record a
score for each day they attend class from the first until the last day. Hopefully the instruction they
receive helps them to improve their game.

Data Source
========================================================
type: exclaim

Student project


Variable Description
========================================================
type: exclaim

This dataset contains 7 variables, 5 of them being continuous, and two other categorical.

<li class= "fragment fade-in"> Attendance: Number of days in class </li>
<li class= "fragment fade-in"> Average score over all days </li>
<li class= "fragment fade-in"> Sex: Coded as f or m </li>
<li class= "fragment fade-in"> Day1: Archery score on first day </li>
<li class= "fragment fade-in"> LastDay: Archery score on last day </li>
<li class= "fragment fade-in"> Improvement: Last day - first day score </li>
<li class= "fragment fade-in"> Improve: 1=improved or 0=did not improve </li>
  
  
Summary Descriptors
========================================================
type: exclaim
  
Let´s study some key elements from the data:
  



```r
summary(ArcheryData)
```

```
   Attendance       Average       Sex         Day1          LastDay     
 Min.   :16.00   Min.   : 66.82   f: 8   Min.   : 16.0   Min.   : 49.0  
 1st Qu.:20.00   1st Qu.: 97.72   m:10   1st Qu.: 57.5   1st Qu.:133.8  
 Median :21.00   Median :141.22          Median :121.0   Median :177.5  
 Mean   :20.72   Mean   :141.83          Mean   :112.9   Mean   :169.7  
 3rd Qu.:22.00   3rd Qu.:183.66          3rd Qu.:160.8   3rd Qu.:217.2  
 Max.   :22.00   Max.   :229.62          Max.   :201.0   Max.   :255.0  
  Improvement        Improve      
 Min.   :-10.00   Min.   :0.0000  
 1st Qu.: 25.00   1st Qu.:1.0000  
 Median : 48.50   Median :1.0000  
 Mean   : 56.83   Mean   :0.8333  
 3rd Qu.: 90.00   3rd Qu.:1.0000  
 Max.   :142.00   Max.   :1.0000  
```


Scatterplot of Attendance vs Average
========================================================
type: exclaim


 
<style>
  .p_iframe iframe {
    width:90%;
    height:576px;
}
</style>

<div class="p_iframe">
<iframe frameborder="0" seamless='seamless' scrolling=no src="plotly.html"></iframe>
</div>

