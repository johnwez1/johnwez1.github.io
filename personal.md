---
layout: default
title: Personal
permalink: /personal/
---

<div class="hero-section">
  <img src="{{ '/assets/images/hike.jpeg' | relative_url }}" alt="Mountain landscape" class="hero-image">
  <p class="image-caption">Looking over Loch Treig in the Scottish Highlands</p>
</div>

# Personal

Most of my time away from a screen ends up somewhere outside - usually in the hills, on the coast,
or heading toward weather that probably looked questionable in the forecast.

This page is a slower collection of things connected to that side of life:
trips, photos, notes from the hills, and whatever else gradually accumulates over time.

<div class="feature-block">
  <div class="feature-image">
    <img src="{{ '/assets/images/munros.png' | relative_url }}" alt="Scottish Munros">
    <p class="image-caption">Munros summited across the Scottish Highlands, credit munromap.co.uk.</p>
  </div>

  <div class="feature-content">
    <h2>Hiking</h2>
    <p>
    Hiking has probably become the main way I reset properly. A few days walking through glens,
    ridgelines, and remote parts of Scotland does more for attention span and perspective than
    almost anything else. Over the years I've gradually worked through the Scottish Munros and have completed over 50 so far. Hopefully one day I'll finish them all. 
    </p>
    <p>
    Unfortunately, my fair weather days are mostly reserved for Paragliding, and this leaves some of the most terrible weather for hiking. Still, I’ll admit there’s something deeply satisfying about coming home after a miserable day in the hills. Soaked through, exhausted, and slightly questioning your decisions - only to end up beside a fire with a warm meal afterwards.
    </p>
  </div>
</div>

<div class="feature-block reverse">
  <div class="feature-image">
    <img src="{{ '/assets/images/paragliding.jpeg' | relative_url }}" alt="Paragliding">
    <p class="image-caption">Taking off at Ölüdeniz.</p>
  </div>

  <div class="feature-content">
    <h2>Paragliding</h2>
    <p>
    Paragliding completely changed how I look at landscapes and weather. Once you've spent time
    flying, you start noticing wind direction, thermals, cloud movement, and terrain in a very different way.
    </p>
    <p>
    One of the things I love most about paragliding is how completely it humbles everyone who enters the sport. Whatever you were outside of flying tends to get left behind pretty quickly. On launch, everyone becomes a student again, and you can fully expect to receive an unexpectedly advanced lesson in physics and meteorology from Bob on the hill. It’s a real privilege to spend time around people with decades of experience in the air. 
    </p>
    <p>
    I'm very much an amateur at the moment, but have been fortunate enough to fly in some incredible places already. Hopefully I can build this part time hobby to the point that overnight flying/camping trips are possible (Vol Biv). Watch this space!
    </p>
  </div>
</div>

<div class="feature-block">
  <div class="feature-image">
    <img src="{{ '/assets/images/beaver.jpeg' | relative_url }}" alt="Rewilding and ecological restoration">
    <p class="image-caption">Beaver spotted on the River Tay - Aberfeldy, Scotland.</p>
  </div>

  <div class="feature-content">
    <h2>Rewilding</h2>
    <p>
    More recently I've become very interested in rewilding and ecological restoration, an interest that has grown out of time spent hiking and flying throughout Scotland.
    </p>
    <p>
    One of my lifelong dreams would be to eventually restore a piece of land in Scotland. I'd love to see the biodiversity restored, starting from the trees and river banks, to building up the insects, birds and fish. If the initiatives to return apex predators like the Lynx are ever succesful, we might be lucky enough to witness a truly natural environment.
    </p>
  </div>
</div>

<p class="closing-note">
  Photos, essays, maps, and field notes will appear here over time.
</p>

<style>
.hero-section {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin: 2rem 0 3rem;
}

.hero-image {
  width: 100%;
  max-width: 1000px;
  height: 700px;
  object-fit: cover;
  object-position: center;
  border-radius: 16px;
}

.feature-block {
  display: flex;
  align-items: center;
  gap: 2rem;
  margin: 4rem 0;
}

.feature-block.reverse {
  flex-direction: row-reverse;
}

.feature-image {
  flex: 1;
}

.feature-image img {
  width: 100%;
  max-width: 420px;
  aspect-ratio: 1 / 1;
  border-radius: 14px;
  object-fit: cover;
  display: block;
}

.feature-content {
  flex: 1.3;
}

.feature-content h2 {
  margin-top: 0;
}

.closing-note {
  margin-top: 3rem;
  opacity: 0.8;
}

@media (max-width: 800px) {
  .feature-block,
  .feature-block.reverse {
    flex-direction: column;
  }

  .hero-image {
    height: 260px;
  }

  .feature-image img {
    max-width: 100%;
  }
}
</style>