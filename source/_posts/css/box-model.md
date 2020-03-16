---
title: 标准盒子模型
date: 2016-10-28 13:47:45
tags: CSS基础
categories: CSS
---
>标准盒子模型定义

<!--more-->
# 标准盒子模型的构成
      content   +   padding  +   border   +     margin
     内容区大小  +    内边距   +   边框大小 +      外边距
     
# 标准盒子模型的w3c图示
      =================================================================
      =                       TM Margin(Transparent)                  =  
      =     —————————————————————————————————————————————————————     =  
      =     |                     TB Border                     |     =  
      =     |    !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!     |     =  
      =     |    !                TP Padding              !     |     =  
      =     |    !    ++++++++++++++++++++++++++++++++    !     |     =  
      =     |    !    +                              +    !     |     =  
      =     |    !    +                              +    !     |     =  
      =     |    !    +                              +    !     |     =  
      =  LM | LB ! LP +            Content           + RP ! RB  | RM  =  
      =     |    !    +                              +    !     |     =  
      =     |    !    +                              +    !     |     =  
      =     |    !    +                              +    !     |     =  
      =     |    !    +                              +    !     |     =  
      =     |    !    ++++++++++++++++++++++++++++++++    !     |     =       
      =     |    !                    BP                  !     |     =  
      =     |    !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!     |     =  
      =     |                         BB                        |     =  
      =     —————————————————————————————————————————————————————     =  
      =                               BM                              =  
      =================================================================
      
                ====  Margin edge
                ————  Border edge
                !!!!  Padding edge
                ++++  Content edge                   
# 其他盒子模型
    注:其他盒子模型只是存在对各个方向上的计算参照不一致