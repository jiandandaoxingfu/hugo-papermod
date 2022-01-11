---
title: "first"
date: 2022-01-06 18:13:52.872 +0800
summary: 'How to use hugo with the theme "paperMod"'
weight: 1
tags: ["first", "two"]
categories: ["first"]
author: "JMx"
showToc: true
TocOpen: false
draft: true
hidemeta: false
comments: false
disableHLJS: true 
disableShare: true
hideSummary: false
searchHidden: false
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
cover:
    image: https://d33wubrfki0l68.cloudfront.net/c38c7334cc3f23585738e40334284fddcaf03d5e/2e17c/images/hugo-logo-wide.svg
    alt: "图片"  
    caption: "" 
    relative: false 
    hidden: true 
---

{{< katex >}}

## content

![图片](images/1.png)

这是一个行内公式： $a^2+b^2=1$. 下面的是块级公式
$$ 
x^2+y^2=1 
$$
支持以下数学环境
\begin{pmatrix}
   a & b \\\\
   c & d
\end{pmatrix}

\begin{equation}
\begin{array}{l}
	& x^2 = 1, \\\\
	& y^2 = 2, \\\\
	& z^2 = 3.
\end{array}
\end{equation}

\begin{equation}
	x^2 + y^2 = 1.
\end{equation}

$$
x = \begin{cases}
   a &\text{if } b \\\\
   c &\text{if } d
\end{cases}
$$



{{< embed-pdf url="post/first/files/test.pdf" >}}