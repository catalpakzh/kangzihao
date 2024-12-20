---
title: Some Questions When Built Website
author: Kang Zihao
date: "2024-10-12"
slug: questions-when-built-website
---

> When I built my website, I countered some questions. Therefore, I plan to write down it as a summary.

## Start is simple

I followed the book called [Blogdown](https://bookdown.org/yihui/blogdown/) and built my website quickly. I deploy my website on the [Netlify](https://www.netlify.com/). 

## Adjustment according to preference 

All things have been set by the template initially. By adjusting the `CSS` file, I changed some appearance, such as font style and size, hover style, note style and some other small changes. In addition, adding `js` link in custom html can implement extra functions. The  <u>.yaml</u> file under initial folder controls the basic structure and personal information.

## Some questions I had met

How to add a catalog for each article? I spent some time looking for the answer. Finally, I found that there was a html document under layout folder caller `single.html`.

How to use mathematical expressions in `.md` files? Maybe you use R markdown to write an article, you will not counter this question. But markdown can't use mathematical expressions. By adding `javascript` into `head_custom` to slove this question. About mathematical expressions, you can read [The Best Way to Support LaTeX Math in Markdown with MathJax](https://yihui.org/en/2018/07/latex-math-markdown/) as a reference.

How to include a picture on the website? Notice the `static` folder which is used to store the pdf, images and so on. Creating a folder like `img` to store photos .

How to adjust the size of figures? Using the html script, for example:
```
<img src="/img/sea.jpg" style="max-width:15%;min-width:40px;float:right;" alt="Kang Zihao" />
```
It seems that markdown can't change the size. But R Markdown can adjust the size of pictures directly. If creating a `.rmd` file in the content folder, I recommend creating a separate folder to store the file.


Actually, I don't have any knowledge of HTML and CSS before. Therefore, I am still exploring the function of the website.The [Poe AI](https://poe.com/) really help me a lot to establish my website. Reading other's websites and github is also a good method to improve my website.

