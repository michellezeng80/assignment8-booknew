# Assignment 8 Jupyter Book
This book contains a data analysis of the {ref}`disney` Dataset, which was my final project done in the Programming in Python for Data Science course. I investigated several questions associated with the Disney datasets. I wanted to know the relationship between {ref}`box-office-gross` and {ref}`film-genre`.

## Dataset Descritption
For this final project, we were provided with 5 datasets regarding Disney's revenue, actors, directors, box office success etc. The data were obtain from data.world {cite:p}`data` which follows a Creative Common Attribution 4.0 International License {cite:p}`cc`.

The tables are disney-characters.csv, disney-director.csv, disney-voice-actors.csv, disney_revenue_1991-2016.csv, disney_movies_total_gross.csv. Each table is stored in a .csv file. I used the disney-director and disney_movies_total_gross tables described below:

* **disney-director.csv**
This file contains information on the title of 56 Disney movies and the name of the movies' first directors scraped from {cite:p}`list`.

* **disney_movies_total_gross.csv**
This file includes information on Disney movie box office gross and inflation adjustments of 579 films. Each film was given a movie title, a release date, a genre, a {ref}`mpaa-rating`, a total gross and an inflation adjusted gross.

## Glossary

(disney)=
### Disney
The Walt Disney Company, commonly known as Disney is an American multinational mass media and entertainment conglomerate headquartered at the Walt Disney Studios complex in Burbank, California {cite:p}`Disney`.

{numref}`Disney-logo` is the Disney Logo.

```{figure} https://upload.wikimedia.org/wikipedia/commons/a/a4/Disney_wordmark.svg
---
height: 300px
name: Disney-logo
---
The Disney Logo
```

(box-office-gross)=
###  Box Office Gross
Definition. Revenue generated from ticket sales (receipts) including any taxes and other levies {cite:p}`UNESCO`. 

(film-genre)=
### Film Genre
The ways in which the film industry, critics, academics, and audiences classify film, forming structures that shape the production and marketing of particular films and manage the expectations of both critics and audiences towards them. The classic film genres are westerns, comedies, musicals, and war films, with thrillers, crime or detective films, film noir, horror, and science fiction also prominent. The major film genres have distinctive textual features including subject matter and themes, setting, narrative form, characterization, iconography, and filmic techniques. Some tend to be defined primarily by their subject matter (e.g. detective films), some by their setting (e.g. the western), and others by their narrative form (e.g. the musical). In addition to textual features, different genres also involve different functions, pleasures, audiences, modes of involvement, styles of interpretation, and text-reader relationships. Many are hybrid genres: for example, romantic comedy or action adventure, problematizing the notion that genres can have clear and distinct borders {cite:p}`genre`.

(mpaa-rating)=
### MPAA-Rating
The Motion Picture Association film rating system is used in the United States and its territories to rate a motion picture's suitability for certain audiences based on its content. 

```{tip}
It was changed from MPAA to MPA!
```
The system and the ratings applied to individual motion pictures are the responsibility of the Motion Picture Association (MPA), previously known as the Motion Picture Association of America (MPAA) from 1945 to 2019 {cite:p}`MPAA`. 


{numref}`MPA-logo` is the MPA Logo.

```{figure} https://upload.wikimedia.org/wikipedia/commons/a/af/Motion_Picture_Association_logo_2019.svg
---
height: 300px
name: MPA-logo
---

MPA logo in use since 2019
```


```{margin} Did you know?
What math equations are in use in the analysis?
```

```{note}
Here they are!
```


```{math}
:label: sum_label3
x_{1} + x_{2} + x_{3} +\dots + x_{n}=\sum_{n=1}^{10}n
```

Equation {eq}`sum_label3` is to calculate the sum of all values.


```{math}
:label: subtract_label4
a-b = c
```
Equation {eq}`subtract_label4` is to calculate the difference between two values.


### Import Python Libraries

The required libraries needed for the analysis are below:

```python
import pandas as pd
```

```python
import altair as alt
```




## Bibliography

```{bibliography} references.bib
:all:
```
