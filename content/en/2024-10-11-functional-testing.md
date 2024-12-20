---
title: Functional Testing
date: '2024-10-06'
slug: functional-testing
categories:
  - Test
tags:
  - Test
---


> This section is for testing some functions in my website. These features utilize JavaScript in HTML and modify CSS files to achieve.


 
## Test for Demo tabs {.tabset}

Below is an example tabset.

### First tab

Hello world! Ciao!

### Second tab {.active}

Here is a table.

|x  |y  |z  |
|---|---|---|
|1  |2  |3  |


#### A level-4 heading

### Third tab

#### Nested tabs! {.tabset #nested-tabs}

##### Tab 1

Isn't it cool? Keep going!

##### Tab 2

Where am I now?


## Test for mathematical expression  

`$z = x + y$`.

$$a^2 + b^2 = c^2$$

`$$\begin{vmatrix}a & b\\
c & d
\end{vmatrix}=ad-bc$$`



## Make the footnote appear on the right

This function let the footnote show on the right side of the text. You can find some useful information in blog of yihui[^1] and guozheng[^2] 

[^1]: This is yihui's github [question section](https://github.com/yihui/yihui.org/discussions/1561).

[^2]: This is guozheng's [github](https://github.com/residualsun1/Residualsun)


Insert the code below into any `html` file.

```{html}
<script src="https://cdn.jsdelivr.net/npm/@xiee/utils/js/sidenotes.min.js" defer></script>
```

## Insert Video

Use the `<iframe>` tag to embed a video.By adding `&autoplay=0` at the end of the video's URL to prevent it from playing automatically.

```
<iframe src="//player.bilibili.com/player.html?isOutside=true&aid=336580443&bvid=BV1CR4y1E7fm&cid=437226045&p=35&autoplay=0"
```

<iframe src="//player.bilibili.com/player.html?isOutside=true&aid=336580443&bvid=BV1CR4y1E7fm&cid=437226045&p=35&autoplay=0"
allowfullscreen="allowfullscreen" 
width="100%" 
height="500"
scrolling="no" 
frameborder="0" 
sandbox="allow-top-navigation allow-same-origin allow-forms allow-scripts"></iframe>
