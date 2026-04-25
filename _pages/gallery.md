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
    max-width: 1040px;
    margin: 0 auto;
    padding: 0.7rem 0 2.5rem;
}

.timeline::after {
    content: '';
    position: absolute;
    width: 2px;
    background: linear-gradient(180deg, transparent, var(--gallery-line) 4%, var(--gallery-line) 96%, transparent);
    top: 0;
    bottom: 0;
    left: 76px;
}

.timeline-section {
    position: relative;
    display: grid;
    grid-template-columns: 132px minmax(0, 1fr);
    gap: 1.25rem;
    margin-bottom: 1.5rem;
}

.timeline-section::before {
    content: '';
    position: absolute;
    left: 68.5px;
    top: 0.72rem;
    z-index: 1;
    width: 15px;
    height: 15px;
    border: 3px solid var(--gallery-paper);
    border-radius: 50%;
    background: var(--gallery-accent);
    box-shadow: 0 0 0 4px rgba(47, 143, 116, 0.18);
}

.timeline-gallery {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
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

.timeline .content.wide {
    grid-column: span 2;
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

.timeline .content.wide img {
    aspect-ratio: 2.1 / 1;
}

.timeline .content:hover img {
    transform: scale(1.035);
    filter: saturate(1.06) contrast(1.02);
}

.timeline .content p {
    position: absolute;
    right: 0;
    bottom: 0;
    left: 0;
    margin: 0;
    padding: 2.7rem 0.85rem 0.75rem;
    color: rgba(255, 255, 255, 0.84);
    font-size: 0.84em;
    line-height: 1.55;
    text-align: left;
    background: linear-gradient(180deg, transparent, rgba(9, 22, 19, 0.76));
}

.timeline .content p::first-line {
    color: #fff;
    font-weight: 700;
}

.timeline-year {
    position: sticky;
    top: 1rem;
    z-index: 2;
    width: fit-content;
    height: fit-content;
    margin: 0;
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
    }

    .timeline-section {
        grid-template-columns: 48px minmax(0, 1fr);
        gap: 0.85rem;
        margin-bottom: 1.25rem;
    }

    .timeline-section::before {
        left: 10.5px;
        top: 0.67rem;
    }

    .timeline-year {
        position: relative;
        top: auto;
        margin-left: 0;
        margin-right: auto;
        transform: translateX(0);
        padding: 0.35rem 0.55rem;
        font-size: 0.95em;
    }

    .timeline .content p {
        padding: 2.35rem 0.75rem 0.65rem;
        font-size: 0.78em;
    }
}

@media screen and (max-width: 560px) {
    .timeline-gallery {
        grid-template-columns: 1fr;
    }

    .timeline .content.wide {
        grid-column: auto;
    }

    .timeline .content.wide img {
        aspect-ratio: 4 / 3;
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
  <section class="timeline-section">
    <div class="timeline-year">2026</div>
    <div class="timeline-gallery">
      <div class="content wide">
        <a href="/images/gallery/snow_mountian.png"><img src="/images/gallery/snow_mountian.png" alt="Snow mountain in Jiuzhaigou" loading="lazy"></a>
        <p>“太美丽了家人们”. <br>@Jiuzhaigou, China.</p>
      </div>
      <div class="content wide">
        <a href="/images/gallery/DT_in_GZ.jpeg"><img src="/images/gallery/DT_in_GZ.jpeg" alt="Moment in Guangzhou" loading="lazy"></a>
        <p>没有人能代替 <br>@Guangzhou, China.</p>
      </div>
    </div>
  </section>

  <section class="timeline-section">
    <div class="timeline-year">2025</div>
    <div class="timeline-gallery">
      <div class="content">
        <a href="/images/gallery/somewhere.png"><img src="/images/gallery/somewhere.png" alt="Somewhere on Earth" loading="lazy"></a>
        <p>Happy April Fools' Day <br>@Somewhere, Earth.</p>
      </div>
      <div class="content">
        <a href="/images/gallery/dive.png"><img src="/images/gallery/dive.png" alt="Dive in Okinawa" loading="lazy"></a>
        <p>Dive. <br>@Okinawa, Japan.</p>
      </div>
      <div class="content">
        <a href="/images/gallery/kitty_claw_cloud.png"><img src="/images/gallery/kitty_claw_cloud.png" alt="Kitty claw cloud in Shenzhen" loading="lazy"></a>
        <p>Kitty Claw. <br>@Shenzhen, China.</p>
      </div>
      <div class="content">
        <a href="/images/gallery/ny_manhattan.jpg"><img src="/images/gallery/ny_manhattan.jpg" alt="Manhattan city view" loading="lazy"></a>
        <p>A bit reward for reinforcement learning. <br>@Manhattan NYC, U.S.</p>
      </div>
      <div class="content wide">
        <a href="/images/gallery/tokyo_tower_org.png"><img src="/images/gallery/tokyo_tower_org.png" alt="Tokyo Tower" loading="lazy"></a>
        <p>"mirrors.tokyo_tower.jp" <br>@Tokyo, Japan</p>
      </div>
    </div>
  </section>

  <section class="timeline-section">
    <div class="timeline-year">2024</div>
    <div class="timeline-gallery">
      <div class="content wide">
        <a href="/images/gallery/past_and_future.jpg"><img src="/images/gallery/past_and_future.jpg" alt="Past and future in Zhengzhou" loading="lazy"></a>
        <p>What's past is prologue. <br>@Zhengzhou, China</p>
      </div>
    </div>
  </section>

  <section class="timeline-section">
    <div class="timeline-year">2023</div>
    <div class="timeline-gallery">
      <div class="content">
        <a href="/images/gallery/escape.jpg"><img src="/images/gallery/escape.jpg" alt="Escape from reality in Changchun" loading="lazy"></a>
        <p>Escape from reality. <br>@Changchun, China</p>
      </div>
      <div class="content">
        <a href="/images/gallery/Sunrise_in_Changchun.jpg"><img src="/images/gallery/Sunrise_in_Changchun.jpg" alt="Sunrise in Changchun" loading="lazy"></a>
        <p>Sunrise in Changchun. <br>@Changchun, China</p>
      </div>
      <div class="content wide">
        <a href="/images/gallery/Night_view_of_Pearl_River.jpg"><img src="/images/gallery/Night_view_of_Pearl_River.jpg" alt="Night view of Pearl River" loading="lazy"></a>
        <p>Night View Of Pearl River. <br>@Guangzhou, China</p>
      </div>
    </div>
  </section>
  
  <section class="timeline-section">
    <div class="timeline-year">2022</div>
    <div class="timeline-gallery">
      <div class="content wide">
        <a href="/images/gallery/YangtzeRiver.jpg"><img src="/images/gallery/YangtzeRiver.jpg" alt="Yangtze River in Wuhan" loading="lazy"></a>
        <p>Yangtze River. <br>@Wuhan, China</p>
      </div>
    </div>
  </section>
  
  <section class="timeline-section">
    <div class="timeline-year">2020</div>
    <div class="timeline-gallery">
      <div class="content wide">
        <a href="/images/gallery/lijiang.jpg"><img src="/images/gallery/lijiang.jpg" alt="Lijiang scenery" loading="lazy"></a>
        <p>Hopes. <br>@Lijiang, China</p>
      </div>
    </div>
  </section>
  
  <section class="timeline-section">
    <div class="timeline-year">2019</div>
    <div class="timeline-gallery">
      <div class="content">
        <a href="/images/gallery/snowinoct.jpg"><img src="/images/gallery/snowinoct.jpg" alt="Snow in October in Changchun" loading="lazy"></a>
        <p>Snow in october. <br>@Changchun, China</p>
      </div>
      <div class="content">
        <a href="/images/gallery/zz7z.png"><img src="/images/gallery/zz7z.png" alt="Windowpane in Zhengzhou No.7" loading="lazy"></a>
        <p>Windowpane in Zhengzhou No.7 <br>@Zhengzhou, China</p>
      </div>
    </div>
  </section>

</div>
