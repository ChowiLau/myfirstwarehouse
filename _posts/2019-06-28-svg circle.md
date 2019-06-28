---
layout: page
title: 圈圈圆圆圈圈
excerpt_separator: "<!--more-->"
categories:
     - svg制作
---

<!--more-->
<style>
body { margin: 0 }
svg { vertical-align: middle; background-color: #eee }
</style>

<svg viewBox="0 0 4 4">
    <circle cx="3" cy="3" r="1">
        <animate
            attributeName="cx"
            attributeType="XML"
            dur="4s"
            values="3;1;3"
            keyTimes="0;.5;1"
            repeatCount="indefinite"
        />
        <animate
            attributeName="cy"
            attributeType="XML"
            dur="4s"
            values="3;1;3"
            keyTimes="0;.5;1"
            repeatCount="indefinite"
        />
    </circle>
</svg>