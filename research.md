---
layout: default
title: Research
permalink: /research/
---

# Research

<p class="intro-text">
  My research interests sit broadly at the intersection of astrophysics, data science, and scientific software.
  A lot of what draws me toward astronomy is the idea that large-scale structure and long timescales can still leave detectable traces in data — if you know where and how to look.
</p>

<p class="intro-text">
  Modern astrophysics increasingly involves working with enormous observational datasets,
  where extracting meaningful physical insight depends on statistics, careful modelling,
  and scalable computational methods.
</p>

<section class="research-section">

  <h2>Galactic Archaeology</h2>
  <p>
    One area I find especially fascinating is Galactic Archaeology - the attempt to reconstruct the formation history
    of the Milky Way using the chemical and dynamical properties of stars.
  </p>

  <p>
    A central idea within the field is chemical tagging: the possibility that stars born together may retain similar
    abundance signatures long after they have dispersed throughout the Galaxy. In principle, this opens the door
    to identifying disrupted stellar populations and perhaps even recovering stars that once formed alongside the Sun itself.
  </p>

  <p>
    Much of my interest here lies in combining astrophysical intuition with machine learning and clustering methods
    applied to large spectroscopic surveys such as Gaia, APOGEE, GALAH, and LAMOST.
    These surveys naturally form high-dimensional feature spaces built from chemical abundances,
    stellar kinematics, and phase-space information.
  </p>

  <p>
    What makes the field especially exciting is that astronomy increasingly feels like a meeting point between physics,
    statistics, and computation. Much of the challenge is no longer obtaining data,
    but learning how to navigate it meaningfully.
  </p>

  <div class="subsection-block">

    <h3>Search for Solar Siblings</h3>

    <img src="{{ '/assets/images/solar_siblings.png' | relative_url }}"
         alt="Solar sibling candidate orbital integration"
         class="subsection-image">

    <p class="image-caption">
      Backwards orbital integration of a solar sibling candidate within a Milky Way potential including spiral arm perturbations.
    </p>

    <p>
      One project explored the search for possible solar sibling candidates.
      An established variability metric derived from open cluster studies was used to isolate chemically similar stars
      within abundance space, before further filtering candidates through similarity in orbital actions
      (<em>Jr</em>, <em>Jφ</em>, and <em>Jz</em>). The remaining candidates were integrated backwards through time within a realistic Galactic potential, including perturbations from spiral arm structure, to search for possible close encounters with the Sun
      within roughly 100 parsecs.
    </p>

    <p>
      One particularly interesting result was how strongly the inclusion of spiral arms altered orbital evolution
      and encounter probabilities. Some initially promising results - including the example shown above -
      were proven spurious once Monte Carlo simulations were used to properly account for estimated measurement uncertainties.
    </p>

    <p>
      Although slightly disappointing at the time, this ended up being one of the most useful lessons from the project:
      convincing-looking data can disappear surprisingly quickly once uncertainties are treated properly.
    </p>

  </div>

  <div class="subsection-block">

    <h3>Searches for Cluster Debris Fields</h3>

    <img src="{{ '/assets/images/debris_field.png' | relative_url }}"
         alt="Search for stellar debris fields"
         class="subsection-image">

    <p class="image-caption">
      Exploring possible tidal debris structures associated with disrupted stellar clusters.
    </p>

    <p>
      Another area I've spent time exploring involves searches for tidal debris fields associated with stellar clusters.
      Over long timescales, clusters gradually lose stars through tidal interactions with the Galactic environment,
      leaving behind faint streams and diffuse debris structures spread across large regions of phase space.
      This work has mostly been exploratory and remains unpublished,
      but it has been an extremely interesting way to think about how dynamical evolution slowly reshapes
      stellar populations over billions of years.
    </p>

    <p>
      Identifying these structures is difficult because the signal is often weak compared to the surrounding Galactic background.
      Much of the work involved experimenting with clustering approaches in combined chemical and dynamical feature spaces,
      searching for subtle overdensities that might correspond to disrupted cluster members.
    </p>

    <p>
      What I enjoyed most about these projects was the balance between statistical reasoning,
      orbital dynamics, and physical interpretation.
      Even ambiguous or negative results usually taught something useful about the limitations of the data
      or the assumptions built into the methods being used.
    </p>

  </div>

</section>

<section class="research-section">

  <h2>Other Areas of Interest</h2>
  <div class="subsection-block">

    <h3>Stellar Magnetic Activity</h3>

    <p>
      This is a relatively new interest for me, and one I'm very excited about.
    </p>

    <p>
      Large scale photometric surveys such as Kepler and TESS have produced extensive time-domain datasets, over long observational baselines. While these surveys were optimised for exoplanet detection and have been highly successful in characterising short-term variability, their Full-Frame Image (FFI) data products remain comparatively underexploited. These FFI outputs, along with results from other surveys (Gaia, GALAH, Rubin) presents an opportunity to fill a gap in the literature for studies of magnetic activity and other long term photometric variability in the era of large surveys.
    </p>

    <p>
      The prospects for discovery in these datasets are promising, and I am excited to see what we can find in current and upcoming surveys.
    </p>

  </div>

  <div class="subsection-block">

    <h3>Approximating Actions</h3>

    <p>
      Another area I’ve started exploring is the numerical estimation of orbital actions.
      This began through reading the literature and working on implementing an existing approximation method in code. 
    </p>

    <p>
      What makes this especially interesting to me is the balance between physical accuracy
      and computational efficiency. Modern Galactic surveys increasingly require methods that scale well,
      and I’m curious whether alternative approximations or data-driven approaches could estimate these quantities
      efficiently while remaining physically meaningful.
    </p>

  </div>

  <div class="subsection-block">

    <h3>Open Source in Astrophysics</h3>

    <p>
      I also care quite a lot about open scientific software.
      A huge amount of modern astronomy depends on community-built tooling,
      and long term I’d like open source development to become part of my contribution to the field.
    </p>

    <p>
      Good scientific infrastructure quietly enables an enormous amount of research,
      and I think there’s real value in building tools that are accessible, reproducible,
      and genuinely useful to other people.
    </p>

  </div>

</section>

<section class="research-section">

  <h2>Citizen Science</h2>

  <img src="{{ '/assets/images/whistle.png' | relative_url }}"
       alt="Citizen science and collaborative research"
       class="section-image">

  <p class="image-caption">
    A whistle glitch example taken from the Gravity Spy project, on Zooniverse.
  </p>

  <p>
    I’ve always liked the idea that meaningful scientific contribution doesn’t have to be restricted
    to formal academic environments. Citizen science projects are one of the clearest examples of this.
  </p>

  <p>
    I’ve spent time contributing to projects on Zooniverse, particularly stellar stream identification work
    and Gravity Spy, which combines human pattern recognition with machine learning
    for gravitational wave detector analysis.
  </p>

  <p>
    Outside astronomy, I’m also very interested in ecological citizen science projects in Scotland.
    One project I hope to contribute to over time is the Mountain Birch Project,
    especially while already spending time hiking throughout the Highlands.
  </p>

  <p>
    The project asks hillwalkers around Scotland to document surviving high-altitude birch populations
    so that seeds can be collected and propagated in nurseries.
    These trees possess unique genetics adapted to harsh upland environments,
    and may play an important role in restoring more natural high-altitude woodland ecosystems.
  </p>

  <p>
    I think there’s something genuinely valuable about people developing a closer observational relationship
    with the environments — natural or cosmic — that surround them.
  </p>

</section>

<p class="closing-note">
  This page will gradually expand with notes, reading summaries, software projects,
  and longer-form research writing.
</p>

<style>

.hero-section {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin: 2rem 0 4rem;
}

.hero-image {
  width: 100%;
  max-width: 1000px;
  height: 560px;
  object-fit: cover;
  object-position: center;
  border-radius: 16px;
}

.intro-text {
  line-height: 1.9;
  margin-bottom: 1.5rem;
}

.research-section {
  margin-top: 5rem;
}

.research-section h2 {
  margin-bottom: 2rem;
}

.section-image {
  width: 100%;
  max-width: 850px;
  display: block;
  margin: 0 auto;
  border-radius: 16px;
  object-fit: cover;
}

.subsection-image {
  width: 100%;
  max-width: 700px;
  display: block;
  margin: 2rem auto 0;
  border-radius: 14px;
  object-fit: cover;
}

.subsection-block {
  margin-top: 4rem;
}

.subsection-block h3 {
  margin-bottom: 1.5rem;
}

p {
  line-height: 1.9;
  margin-bottom: 1.4rem;
}

.image-caption {
  margin-top: 0.9rem;
  margin-bottom: 2rem;
  font-size: 0.92rem;
  opacity: 0.75;
  line-height: 1.5;
  font-style: italic;
  text-align: center;
}

.closing-note {
  margin-top: 5rem;
  opacity: 0.8;
}

@media (max-width: 800px) {

  .hero-image {
    height: 320px;
  }

  .section-image,
  .subsection-image {
    max-width: 100%;
  }

}

</style>