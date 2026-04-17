---
layout: archive
title: "Gallery"
permalink: /gallery/
author_profile: true
---


<style>
:root {
    --gallery-ink: #22302d;
    --gallery-muted: #65716d;
    --gallery-paper: #ffffff;
    --gallery-soft: #f4f8f6;
    --gallery-line: #bfd7cf;
    --gallery-accent: #2f8f74;
    --gallery-warm: #d35b4a;
    --gallery-shadow: 0 18px 42px rgba(31, 52, 47, 0.14);
}

.gallery-intro {
    max-width: 760px;
    margin: 0 auto 1.8rem;
    padding: 1.25rem 0.25rem 0.4rem;
    color: var(--gallery-muted);
    font-size: 1.02em;
    line-height: 1.75;
}

.gallery-intro p {
    margin: 0;
}

.timeline {
    position: relative;
    max-width: 980px;
    margin: 0 auto;
    padding: 1rem 0 2.5rem;
}

.timeline::after {
    content: '';
    position: absolute;
    width: 2px;
    background: linear-gradient(180deg, transparent, var(--gallery-line) 4%, var(--gallery-line) 96%, transparent);
    top: 0;
    bottom: 0;
    left: 50%;
    transform: translateX(-50%);
}

.timeline-item {
    position: relative;
    width: 50%;
    box-sizing: border-box;
    margin: 0.4rem 0 1.4rem;
    padding: 0 44px;
}

.timeline-item::after {
    content: '';
    position: absolute;
    width: 15px;
    height: 15px;
    top: 30px;
    right: -7.5px;
    z-index: 1;
    border: 3px solid var(--gallery-paper);
    border-radius: 50%;
    background: var(--gallery-accent);
    box-shadow: 0 0 0 4px rgba(47, 143, 116, 0.18);
}

.timeline-item.left {
    left: 0;
}

.timeline-item.right {
    left: 50%;
}

.timeline-item.right::after {
    left: -7.5px;
}

.timeline-item::before {
    content: '';
    position: absolute;
    top: 35px;
    width: 32px;
    height: 2px;
    background: var(--gallery-line);
}

.timeline-item.left::before {
    right: 10px;
}

.timeline-item.right::before {
    left: 10px;
}

.timeline .content {
    position: relative;
    overflow: hidden;
    background: var(--gallery-paper);
    border: 1px solid rgba(47, 143, 116, 0.16);
    border-radius: 8px;
    box-shadow: 0 10px 28px rgba(31, 52, 47, 0.10);
    transition: transform 180ms ease, box-shadow 180ms ease, border-color 180ms ease;
}

.timeline .content:hover {
    transform: translateY(-4px);
    border-color: rgba(47, 143, 116, 0.34);
    box-shadow: var(--gallery-shadow);
}

.timeline .content a {
    display: block;
    background: var(--gallery-soft);
}

.timeline .content img {
    display: block;
    width: 100%;
    aspect-ratio: 4 / 3;
    object-fit: cover;
    transition: transform 300ms ease, filter 300ms ease;
}

.timeline .content:hover img {
    transform: scale(1.035);
    filter: saturate(1.06) contrast(1.02);
}

.timeline .content p {
    margin: 0;
    padding: 0.9rem 1rem 1rem;
    color: var(--gallery-muted);
    font-size: 0.9em;
    line-height: 1.55;
    text-align: left;
}

.timeline .content p::first-line {
    color: var(--gallery-ink);
    font-weight: 700;
}

.timeline-year {
    position: relative;
    z-index: 2;
    width: fit-content;
    margin: 0.2rem auto 1.1rem;
    padding: 0.35rem 0.9rem;
    color: var(--gallery-ink);
    font-size: 1.15em;
    font-weight: 800;
    letter-spacing: 0;
    line-height: 1;
    background: var(--gallery-paper);
    border: 1px solid rgba(47, 143, 116, 0.20);
    border-radius: 999px;
    box-shadow: 0 8px 20px rgba(31, 52, 47, 0.08);
}

.timeline-year::before {
    content: '';
    display: inline-block;
    width: 0.55rem;
    height: 0.55rem;
    margin-right: 0.45rem;
    border-radius: 50%;
    background: var(--gallery-warm);
    vertical-align: 0.08rem;
}

@media screen and (max-width: 768px) {
    .gallery-intro {
        margin-bottom: 1rem;
        padding-top: 0.8rem;
        font-size: 0.96em;
    }

    .timeline {
        padding-bottom: 1.5rem;
    }

    .timeline::after {
        left: 18px;
        transform: none;
    }

    .timeline-item {
        width: 100%;
        margin-bottom: 1.2rem;
        padding-left: 48px;
        padding-right: 0;
    }

    .timeline-item.left,
    .timeline-item.right {
        left: 0;
    }

    .timeline-item.left::after,
    .timeline-item.right::after {
        left: 10.5px;
        right: auto;
    }

    .timeline-item.left::before,
    .timeline-item.right::before {
        left: 18px;
        width: 22px;
    }

    .timeline-year {
        margin-left: 0;
        margin-right: auto;
        transform: translateX(0);
    }

    .timeline .content p {
        padding: 0.8rem 0.9rem 0.9rem;
    }
}

@media (prefers-reduced-motion: reduce) {
    .timeline .content,
    .timeline .content img {
        transition: none;
    }

    .timeline .content:hover {
        transform: none;
    }

    .timeline .content:hover img {
        transform: none;
    }
}
</style>


<div class="gallery-intro">
  <p>Little windows from places I loved, years I don't want to lose.</p>
</div>

<div class="timeline">
  <div class="timeline-year">2026</div>
  <div class="timeline-item left">
    <div class="content">
      <a href="/images/gallery/snow_mountian.png"><img src="/images/gallery/snow_mountian.png" alt="Snow mountain in Jiuzhaigou" loading="lazy"></a>
      <p>“太美丽了家人们”. <br>@Jiuzhaigou, China.</p>
    </div>
  </div>

  <div class="timeline-year">2025</div>
  <div class="timeline-item right">
    <div class="content">
      <a href="/images/gallery/somewhere.png"><img src="/images/gallery/somewhere.png" alt="Somewhere on Earth" loading="lazy"></a>
      <p>Happy April Fools' Day <br>@Somewhere, Earth.</p>
    </div>
  </div>
  <div class="timeline-item left">
    <div class="content">
      <a href="/images/gallery/dive.png"><img src="/images/gallery/dive.png" alt="Dive in Okinawa" loading="lazy"></a>
      <p>Dive. <br>@Okinawa, Japan.</p>
    </div>
  </div>
  <div class="timeline-item right">
    <div class="content">
      <a href="/images/gallery/kitty_claw_cloud.png"><img src="/images/gallery/kitty_claw_cloud.png" alt="Kitty claw cloud in Shenzhen" loading="lazy"></a>
      <p>Kitty Claw. <br>@Shenzhen, China.</p>
    </div>
  </div>

  <div class="timeline-item left">
    <div class="content">
      <a href="/images/gallery/ny_manhattan.jpg"><img src="/images/gallery/ny_manhattan.jpg" alt="Manhattan city view" loading="lazy"></a>
      <p>A bit reward for reinforcement learning. <br>@Manhattan NYC, U.S.</p>
    </div>
  </div>

  <div class="timeline-item right">
    <div class="content">
      <a href="/images/gallery/tokyo_tower_org.png"><img src="/images/gallery/tokyo_tower_org.png" alt="Tokyo Tower" loading="lazy"></a>
      <p>"mirrors.tokyo_tower.jp" <br>@Tokyo, Japan</p>
    </div>
  </div>

  <div class="timeline-year">2024</div>

  <div class="timeline-item left">
    <div class="content">
      <a href="/images/gallery/past_and_future.jpg"><img src="/images/gallery/past_and_future.jpg" alt="Past and future in Zhengzhou" loading="lazy"></a>
      <p>What's past is prologue. <br>@Zhengzhou, China</p>
    </div>
  </div>

  <div class="timeline-year">2023</div>

  <div class="timeline-item right">
    <div class="content">
      <a href="/images/gallery/escape.jpg"><img src="/images/gallery/escape.jpg" alt="Escape from reality in Changchun" loading="lazy"></a>
      <p>Escape from reality. <br>@Changchun, China</p>
    </div>
  </div>
  
  <div class="timeline-item left">
    <div class="content">
      <a href="/images/gallery/Sunrise_in_Changchun.jpg"><img src="/images/gallery/Sunrise_in_Changchun.jpg" alt="Sunrise in Changchun" loading="lazy"></a>
      <p>Sunrise in Changchun. <br>@Changchun, China</p>
    </div>
  </div>

  <div class="timeline-item right">
    <div class="content">
      <a href="/images/gallery/Night_view_of_Pearl_River.jpg"><img src="/images/gallery/Night_view_of_Pearl_River.jpg" alt="Night view of Pearl River" loading="lazy"></a>
      <p>Night View Of Pearl River. <br>@Guangzhou, China</p>
    </div>
  </div>
  
  <div class="timeline-year">2022</div>
  
  <div class="timeline-item left">
    <div class="content">
      <a href="/images/gallery/YangtzeRiver.jpg"><img src="/images/gallery/YangtzeRiver.jpg" alt="Yangtze River in Wuhan" loading="lazy"></a>
      <p>Yangtze River. <br>@Wuhan, China</p>
    </div>
  </div>
  
  <div class="timeline-year">2020</div>
  
  <div class="timeline-item right">
    <div class="content">
      <a href="/images/gallery/lijiang.jpg"><img src="/images/gallery/lijiang.jpg" alt="Lijiang scenery" loading="lazy"></a>
      <p>Hopes. <br>@Lijiang, China</p>
    </div>
  </div>
  
  <div class="timeline-year">2019</div>
  
  <div class="timeline-item left">
    <div class="content">
      <a href="/images/gallery/snowinoct.jpg"><img src="/images/gallery/snowinoct.jpg" alt="Snow in October in Changchun" loading="lazy"></a>
      <p>Snow in october. <br>@Changchun, China</p>
    </div>
  </div>

  <div class="timeline-item right">
    <div class="content">
      <a href="/images/gallery/zz7z.png"><img src="/images/gallery/zz7z.png" alt="Windowpane in Zhengzhou No.7" loading="lazy"></a>
      <p>Windowpane in Zhengzhou No.7 <br>@Zhengzhou, China</p>
    </div>
  </div>

</div>
