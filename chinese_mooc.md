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

Date: 2020-06-08  
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

other attached packages:
[1] dplyr_0.8.5     prettydoc_0.3.1 pacman_0.5.1   

loaded via a namespace (and not attached):
 [1] Rcpp_1.0.4           pillar_1.4.3         compiler_3.5.0       base64enc_0.1-3     
 [5] remotes_2.1.1        prettyunits_1.0.2    tools_3.5.0          testthat_2.3.2      
 [9] digest_0.6.25        pkgbuild_1.0.7       pkgload_1.0.2        evaluate_0.14       
[13] memoise_1.1.0        tibble_2.1.3         pkgconfig_2.0.3      rlang_0.4.5         
[17] cli_2.0.2            rstudioapi_0.11      yaml_2.2.0           xfun_0.11           
[21] stringr_1.4.0        withr_2.1.2          knitr_1.26           fs_1.3.2            
[25] desc_1.2.0           devtools_2.3.0       rprojroot_1.3-2      tidyselect_0.2.5    
[29] glue_1.3.1           R6_2.4.1             processx_3.4.1       fansi_0.4.0         
[33] rmarkdown_2.1        sessioninfo_1.1.1    purrr_0.3.3          callr_3.4.3         
[37] magrittr_1.5         usethis_1.6.0        backports_1.1.5      ps_1.3.0            
[41] htmltools_0.4.0.9003 ellipsis_0.3.0       rsconnect_0.8.16     assertthat_0.2.1    
[45] tinytex_0.19         stringi_1.4.3        crayon_1.3.4        
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








