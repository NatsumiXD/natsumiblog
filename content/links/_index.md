---
title: "友链~"
author: ["Natsumi"]
tags: ["links"]
ShowToc: false
---

<style>
    .friendurl {
    text-decoration: none !important;
    color: black;
    box-shadow: none !important;
}

.myfriend {
    width: 56px !important;
    height: 56px !important;
    border-radius: 50%!important;
    padding: 2px;
    margin-top: 20px !important;
    margin-left: 14px !important;
    background-color: #fff;
}

.frienddiv {
    overflow: auto;
    height: 100px;
    width: 49%;
    display: inline-block !important;
    border-radius: 5px;
    background: none;
    
    -webkit-transition: all ease-out 0.3s;
    -moz-transition: all ease-out 0.3s;
    -o-transition: all ease-out 0.3s;
    transition: all ease-out 0.3s;
}

.dark .frienddiv:hover {
    background: var(--code-bg);
}

.frienddiv:hover {
    background: var(--theme);
    transition: transform 1s;
    webkit-transform: scale(1.1);
    -moz-transform: scale(1.2);
    -ms-transform: scale(1.2);
    -o-transform: scale(1.2);
    transform: scale(1.1);
}

.frienddiv:hover .frienddivleft img { 
    transition: 0.9s !important;
    -webkit-transition: 0.9s !important;
    -moz-transition: 0.9s !important;
    -o-transition: 0.9s !important;
    -ms-transition: 0.9s !important;
}

.frienddivleft {
    width: 92px;
    float: left;
    margin-right: -5px;
}

.frienddivright {
    margin-top: 18px;
    margin-right: 18px;
}

.friendname {
    text-overflow: ellipsis;
    font-size: 100%;
    margin-bottom: 5px;
    color: var(--primary);
}

.friendinfo {
    text-overflow: ellipsis;
    font-size: 70%;
    color: var(--primary);
}

@media screen and (max-width: 600px) {
    .friendinfo {
        display: none;
    }
    .frienddivleft {
        width: 84px;
        margin: auto;
    }
    .frienddivright {
        height: 100%;
        margin: auto;
        display: flex;
        align-items: center;
        justify-content: center;
    }
    .friendname {
        font-size: 18px;
    }
}
</style>


<div class="frienddiv" title="当v1.hitokoto.cn无法访问时主页会出现彩蛋！" onclick="window.open('https://github.com/hsn8086', '_blank');">
    <div class="frienddivleft">
        <img class="myfriend" src="https://avatars.githubusercontent.com/u/51445446?v=4" title="hsn" style="">
    </div>
    <div class="frienddivright">
        <div class="friendname">hsn8086</div>
        <div class="friendinfo">简介被我吃掉啦!</div>
    </div>
</div>

<div class="frienddiv" onclick="window.open('https://gmoe.link/', '_blank');">
    <div class="frienddivleft">
        <img class="myfriend" src="https://www.gmoe.cc/img/gu.jpg" title="Googu" style="">
    </div>
    <div class="frienddivright">
        <div class="friendname">咕谷酱</div>
        <div class="friendinfo">世界に忘れられた</div>
    </div>
</div>