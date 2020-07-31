---
title: Chinese MOOC 
author: |
 | Matt Malishev  
#bibliography:/Users/malishev/Documents/Melbourne Uni/Thesis_2016/library.bib
fontsize: 10
geometry: margin=1in
documentclass: article
linkcolor: blue
urlcolor: blue
citecolor: red
output:
  html_document:
    highlight: tango
    code_folding: hide
    code_download: true
    toc: yes
    toc_depth: 4
    number_sections: no
    toc_float: yes
  pdf_document:
    includes:
      in_header: # add .tex file with header content
    highlight: tango
    template: null
    toc: yes
    toc_depth: 4
    number_sections: false
    fig_width: 4
    fig_height: 5
    fig_caption: true
    df_print: tibble 
    latex_engine: xelatex #pdflatex # lualatex
    keep_tex: false # keep .tex file in dir 
  word_document:
    highlight: tango
    keep_md: yes
    pandoc_args: --smart
    #reference: mystyles.docx
    toc: yes
inludes:
  # before_body: before_body.tex
subtitle: 
tags:
- nothing
- nothingness
params: 
  dir: "/Users/malishev/Documents/chinese/mooc/chinese_mooc"
  date: !r Sys.Date()
  session: !r sessionInfo()  
  version: !r getRversion()
  email: "matthew.malishev@gmail.com"
  doi: https://moocs.unipus.cn/my/course/373  
classoption: portrait
# ^['https://github.com/darwinanddavis/UsefulCode'] # footnote
vignette: >
  %\VignetteIndexEntry{Useful R code}
  %\VignetteEncoding{UTF-8}
  %\VignetteEngine{knitr::rmarkdown}
---

<script type="text/x-mathjax-config">
  MathJax.Hub.Config({ TeX: { equationNumbers: {autoNumber: "all"} } });
</script>





\newpage   

Date: 2020-07-31  
R version: 3.5.0   
*Corresponding author: matthew.malishev@gmail.com  
This document can be found at https://moocs.unipus.cn/my/course/373  

\  

R session info 


```
R version 3.5.0 (2018-04-23)
Platform: x86_64-apple-darwin15.6.0 (64-bit)
Running under: macOS  10.14.6

Matrix products: default
BLAS: /System/Library/Frameworks/Accelerate.framework/Versions/A/Frameworks/vecLib.framework/Versions/A/libBLAS.dylib
LAPACK: /Library/Frameworks/R.framework/Versions/3.5/Resources/lib/libRlapack.dylib

locale:
[1] en_US.UTF-8/en_US.UTF-8/en_US.UTF-8/C/en_US.UTF-8/en_US.UTF-8

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

loaded via a namespace (and not attached):
 [1] crayon_1.3.4         digest_0.6.25        lifecycle_0.2.0      magrittr_1.5        
 [5] evaluate_0.14        pillar_1.4.4         rlang_0.4.6          stringi_1.4.6       
 [9] rstudioapi_0.11      vctrs_0.3.1          ellipsis_0.3.1       rmarkdown_2.2       
[13] tools_3.5.0          stringr_1.4.0        tinytex_0.23         xfun_0.14           
[17] yaml_2.2.1           rsconnect_0.8.16     compiler_3.5.0       pkgconfig_2.0.3     
[21] base64enc_0.1-3      htmltools_0.4.0.9003 knitr_1.28           tibble_3.0.1        
```

\newpage  

# Lesson 1  

## Auxiliary verbs 能，会，可以  
- modify verbs and actions    
- negate with 不  

### 能  
- expresses ability  
- expresses possibility due to circumstance   

他不能走路  
He can't walk  
他能走路  
He can walk  

### 会    
- expresses grasp of skil from learning    
- expresses possibility    

今天不会下雨  
Today it won't rain  

### 可以   
- expresses permission  

我可以用一下你的自行车吗？   
Can i use your bike?  

Pose a question with auxiliary verbs by
- using the positive and negative form  
- using 吗


我可以不可以进去 / 我可以进去吗？  









