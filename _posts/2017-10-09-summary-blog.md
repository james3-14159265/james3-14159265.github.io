---
title: summary blog
layout: post
author: james.spicer
permalink: /summary-blog/
source-id: 1rUIoH3-tkTW3YXomOCfKmnojIWE3xytHrD0U__zR2yE
published: true
---
 In the past four weeks we have been doing work on excel, creating a code and a system that codes it and decodes it. =VLOOKUP(D1,$A1:$B27,2) is the formulae for the computer so it could understand what was going on and code the message.For example i entered the word hello world and it came out as yvbbeq-rcvi. And to decode it we had to concatenate it. ![image alt text]({{ site.url }}/public/ZFf8gUzM45q4Eqgw7dH8Q_img_0.png)

 So, this is a screenshot of the work that i did over the four weeks. The top five lines show where i encrypted it and decrypted it. Where it says na, it means that there is no letters above it to code so it just says nothing. Then the decoding bit at the bottom shows how we decode it. It is not quite finished yet but, the bit i have done works. Where it says left, it basically means move onto the next letter from the coded message. The code is =LEFT($E$8,1*E12) which means display the next letter from the letters in the box on the left. The factor line is basically just numbers that show how many letters are in the message. On the switch line, it says a 1 or 0. The 1 means that there is a change there between it and the box before and the 0 means that there is no change to the code. Then it would split it in the split line below, so the letters would show individually then i would just use the vlookup i used at the start to decode the message and it would show up in the decoded line.

