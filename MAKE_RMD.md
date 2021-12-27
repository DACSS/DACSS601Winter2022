# Make an RMarkdown

- Open RStudio  

- Make a new R Markdown file from   

![Make a new RMD file](https://i.imgur.com/aIe3vtN.png)  

- Select Empty Document
![Create Empty Document](https://i.imgur.com/IJFf22j.png)  

- This is the file you shoulld get when you make a new RMD file.
![New File](https://i.imgur.com/czUf3oP.png)  

- Setup the file by adding this to your empty file:  
````
---
title: "THE TITLE"
description: "SOME DESCRIPTION"
author: "YOUR NAME"
date: "`r Sys.Date()`"
output: distill::distill_article
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = FALSE)
```
````
![Setup the file](https://i.imgur.com/Kmab4Iy.png)  

- You are all set now! Feel free to add your code now.
