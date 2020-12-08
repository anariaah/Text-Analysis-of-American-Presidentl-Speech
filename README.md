# HW09: Text analysis

## Pacakges

```{r}
library(tidyverse)
library(tidytext)
library(here)
library(topicmodels)
library(sotu)
library(tm)
library(wordcloud)
library(reshape2)
library(ggraph)
library(igraph)

```
You might need to install some packages if they are not in your library. 

For instance, 
```{r}
install.packages("sotu")
install.packages("ggraph")

```

## SOTU

The Statement of the Union documents the speech and oral presentation for each president in the U.S. The dataset contains two datasets, the meta and the text. The text dataset only contains the document. You might want to incorporate two datasets first. 

This analysis uses the sotu package in r directly. The package does not include the presidency of Trump. If you want to use the updated version, please consult [The American Presidency Project](https://www.presidency.ucsb.edu/documents/presidential-documents-archive-guidebook/annual-messages-congress-the-state-the-union)

The analysis utilizes exploratory analysis, word counts, sentiment analysis, and topic modeling. 
If you want to learn more about text mining: [Text Mining Resource](https://www.tidytextmining.com) 

## Docuemnts

+ [Markdown File](https://github.com/anariaah/hw09/blob/master/text.md)
+ [RMarkdown File](https://github.com/anariaah/hw09/blob/master/text.Rmd)