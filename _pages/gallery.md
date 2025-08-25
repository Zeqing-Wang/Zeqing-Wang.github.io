---
layout: archive
title: "Gallery"
permalink: /gallery/
author_profile: true
---


<style>
/* --- Timeline Container --- */
.timeline {
    position: relative;
    max-width: 900px;
    margin: 0 auto;
    padding: 20px 0;
}

/* --- The Central Line --- */
.timeline::after {
    content: '';
    position: absolute;
    width: 3px;
    background-color: #e0e0e0;
    top: 0;
    bottom: 0;
    left: 50%;
    margin-left: -1.5px;
}

/* --- Timeline Item Container --- */
.timeline-item {
    padding: 10px 40px;
    position: relative;
    background-color: inherit;
    width: 50%;
    box-sizing: border-box;
}

/* --- The Circle on the Timeline --- */
.timeline-item::after {
    content: '';
    position: absolute;
    width: 20px;
    height: 20px;
    right: -11.5px;
    background-color: white;
    border: 4px solid #4CAF50; /* 您可以更改为您喜欢的主题色 */
    top: 25px;
    border-radius: 50%;
    z-index: 1;
}

/* --- Position items on the left/right --- */
.left {
    left: 0;
}

.right {
    left: 50%;
}

/* --- Add arrows to the left item (points right) --- */
.left::before {
    content: " ";
    height: 0;
    position: absolute;
    top: 28px;
    width: 0;
    z-index: 1;
    right: 30px;
    border: medium solid white;
    border-width: 10px 0 10px 10px;
    border-color: transparent transparent transparent white;
}

/* --- Add arrows to the right item (points left) --- */
.right::before {
    content: " ";
    height: 0;
    position: absolute;
    top: 28px;
    width: 0;
    z-index: 1;
    left: 30px;
    border: medium solid white;
    border-width: 10px 10px 10px 0;
    border-color: transparent white transparent transparent;
}

/* --- Fix the circle for right-sided items --- */
.right::after {
    left: -11.5px;
}

/* --- The content box for each item --- */
.content {
    padding: 20px;
    background-color: white;
    position: relative;
    border-radius: 8px;
    box-shadow: 0 4px 8px 0 rgba(0,0,0,0.1);
    text-align: center; /* 文本居中 */
}

.content img {
    max-width: 100%;
    height: auto;
    border-radius: 15px; /* 图片圆角 */
}

.content p {
    font-size: 0.9em;
    margin-top: 10px;
    color: #555;
}

/* --- Year Marker --- */
.timeline-year {
    text-align: center;
    font-size: 1.8em;
    font-weight: bold;
    color: #333;
    padding: 10px 0;
    position: relative;
    z-index: 2;
    background-color: #f8f9fa; /* 与页面背景色融合 */
}

/* --- Responsive design for mobile screens --- */
@media screen and (max-width: 768px) {
    /* Move the line to the left */
    .timeline::after {
        left: 25px;
    }

    /* Full-width items */
    .timeline-item {
        width: 100%;
        padding-left: 60px;
        padding-right: 15px;
    }

    /* All items on the right side of the line */
    .left, .right {
        left: 0%;
    }

    /* Position the circle correctly */
    .left::after, .right::after {
        left: 14px;
    }
    
    /* Position the arrows correctly */
    .left::before, .right::before {
        left: 50px;
        border-color: transparent white transparent transparent;
        border-width: 10px 10px 10px 0;
    }
}
</style>


<div class="timeline">

  <div class="timeline-year">2025</div>
  <div class="timeline-item right">
    <div class="content">
      <a href="/images/gallery/kitty_claw_cloud.png"><img src="/images/gallery/kitty_claw_cloud.png"></a>
      <p>Kitty Claw. <br>@Shenzhen, China.</p>
    </div>
  </div>

  <div class="timeline-item left">
    <div class="content">
      <a href="/images/gallery/ny_manhattan.jpg"><img src="/images/gallery/ny_manhattan.jpg"></a>
      <p>A bit reward for reinforcement learning. <br>@Manhattan NYC, U.S.</p>
    </div>
  </div>

  <div class="timeline-item right">
    <div class="content">
      <a href="/images/gallery/tokyo_tower_org.png"><img src="/images/gallery/tokyo_tower_org.png"></a>
      <p>"mirrors.tokyo_tower.jp" <br>@Tokyo, Japan</p>
    </div>
  </div>

  <div class="timeline-year">2024</div>

  <div class="timeline-item left">
    <div class="content">
      <a href="/images/gallery/past_and_future.jpg"><img src="/images/gallery/past_and_future.jpg"></a>
      <p>What's past is prologue. <br>@Zhengzhou, China</p>
    </div>
  </div>

  <div class="timeline-year">2023</div>

  <div class="timeline-item right">
    <div class="content">
      <a href="/images/gallery/escape.jpg"><img src="/images/gallery/escape.jpg"></a>
      <p>Escape from reality. <br>@Changchun, China</p>
    </div>
  </div>
  
  <div class="timeline-item left">
    <div class="content">
      <a href="/images/gallery/Sunrise_in_Changchun.jpg"><img src="/images/gallery/Sunrise_in_Changchun.jpg"></a>
      <p>Sunrise in Changchun. <br>@Changchun, China</p>
    </div>
  </div>

  <div class="timeline-item right">
    <div class="content">
      <a href="/images/gallery/Night_view_of_Pearl_River.jpg"><img src="/images/gallery/Night_view_of_Pearl_River.jpg"></a>
      <p>Night View Of Pearl River. <br>@Guangzhou, China</p>
    </div>
  </div>
  
  <div class="timeline-year">2022</div>
  
  <div class="timeline-item left">
    <div class="content">
      <a href="/images/gallery/YangtzeRiver.jpg"><img src="/images/gallery/YangtzeRiver.jpg"></a>
      <p>Yangtze River. <br>@Wuhan, China</p>
    </div>
  </div>
  
  <div class="timeline-year">2020</div>
  
  <div class="timeline-item right">
    <div class="content">
      <a href="/images/gallery/lijiang.jpg"><img src="/images/gallery/lijiang.jpg"></a>
      <p>Hopes. <br>@Lijiang, China</p>
    </div>
  </div>
  
  <div class="timeline-year">2019</div>
  
  <div class="timeline-item left">
    <div class="content">
      <a href="/images/gallery/snowinoct.jpg"><img src="/images/gallery/snowinoct.jpg"></a>
      <p>Snow in october. <br>@Changchun, China</p>
    </div>
  </div>

  <div class="timeline-item right">
    <div class="content">
      <a href="/images/gallery/zz7z.png"><img src="/images/gallery/zz7z.png"></a>
      <p>Windowpane in Zhengzhou No.7 <br>@Zhengzhou, China</p>
    </div>
  </div>

</div>
