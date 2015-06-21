---
title       : Neural Network Function Approximation 
subtitle    : Coursera Developing Data Products
author      : Jorge Palma
job         : Data science enthusiast
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Neural Network Function Approximation

<div class=WordSection1>

<p class=MsoNormal><o:p>&nbsp;</o:p></p>

<p class=MsoNormal>&quot;Function approximation, which finds the underlying
relationship from a given finite input-output data, is the fundamental problem
in a vast majority of real world applications, such as prediction, pattern
recognition, data mining and classification. Various methods have been
developed to address this problem, where one of them is by using artificial
neural networks&quot;<o:p></o:p></p>

<p class=MsoNormal><o:p>&nbsp;</o:p></p>
<p class=MsoNormal><o:p>&nbsp;</o:p></p>
<p class=MsoNormal><o:p>&nbsp;</o:p></p>
<p class=MsoNormal><o:p>&nbsp;</o:p></p>

<p class=MsoNormal><span style='font-size:8.0pt;mso-bidi-font-size:11.0pt;
line-height:115%'>Source: Improving neural networks by preventing co-adaptation
of feature detectors, G. E. Hinton, N. Srivastava, A. <span class=SpellE>Krizhevsky<span style='mso-special-character:footnote-separator'><![if !supportFootnotes]>

<hr align=left size=1 width="33%">


</div>


--- 

## Neural Network Function Approximation

<p class=MsoNormal><o:p>&nbsp;</o:p></p>

<p>The shiny application executes the function approximation using a neural network with a number of observations.  The application is executed by clicking on the Model tab and click on the Run Model button. This action will take the values for the number of neurons in the hidden layer and the fraction of the data that correspond with the training set.</p>

<p>The number of neurons in the hidden layer will determine the number of weights for the free parameters. In the Model tab you will see a greater number of weights, this number include the weight between the hidden layer and the output layer.</p>

<p>The training set should be sufficiently large and diverse so that it could represent the problem well. For good generalization, the size of the training set should be several times larger that the network capacity.</p>


--- 

## Neural Network Function Approximation

<p class=MsoNormal><o:p>&nbsp;</o:p></p>

<p>The output of this application is a root mean square error of the test set. The lower the value of the RMSE the better it is. The user can modify the number of neurons and the size of the training to find the optimal value for these two parameters using the RMSE as guide.</p>


<p>The next slide has the output for the following parameters:</P>

<P>- 70% of the data is used for the training set</p>

<P>- 3 hidden neurons in the hidden layer</p>

<P>The RMSE is shown at the bottom of the slide</p>


--- 

## Neural Network Function Approximation


```
## # weights:  13
## initial  value 1.907332 
## iter  10 value 0.128250
## iter  20 value 0.092395
## iter  30 value 0.089138
## iter  40 value 0.086103
## iter  50 value 0.085164
## iter  60 value 0.084803
## iter  70 value 0.084606
## iter  80 value 0.084463
## iter  90 value 0.084441
## iter 100 value 0.084431
## final  value 0.084428 
## converged
```

```
## [1] 84.66899
```
---
