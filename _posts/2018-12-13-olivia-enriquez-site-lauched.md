---
layout: post
title: "Flag Project in Progress 
date: 2018-12-13
---






\\\
include image
size= 300
width= size * 3
hight= size * 2
diamitoer= size / 1/2

RR= rectangle( 900, 600, "solid", "red")
RC= circle( 150,"solid","pink")
WM= circle( 50,"solid","black")
WWC= circle( 175,"solid","white")

RRRC= underlay-xy(RR, 225, 150,WWC)
RCWWC= underlay-xy(WWC, 50, 75,RC)

Combined= underlay-xy(RRRC, 225, 150,RCWWC)

RL= rectangle( width, hight, "solid", "crimson")
w= size * 3
H= size * 2 
Rc= size * 1/2

R= rectangle(w, H, "solid", "crimson")
C= circle( Rc,"solid","white")
WC= circle( Rc / 1.5,"solid","crimson")

Base= underlay-xy(R, 275,150 ,C)
Base2= underlay-xy(Base, 345,170 ,WC)
\\\


!{ Flag Image](/image/Tuna.png)



When coding this I encountered many challenges and it was very intresting going into these challenges and trying to fix them. I was having an issue with writing the begining code. I looked at creating that shapes. The first shape I needed to use was a rectangle. The questions I had for that were
<ul>
  <li> What properties were needed to complete this </li>
  <li> What am I asked to know for this shape? </li>
  <li> What numbers and colors do I use for this shape</li>
  
