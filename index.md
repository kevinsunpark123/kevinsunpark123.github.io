---
layout: page
title: "Kevin Park"
permalink: /
---
<style>
h1, h2, h3, h4, h5, h6 {
  color: white !important;
}
</style>

<style>
.page-subtitle,
.page__subtitle,
.subtitle,
p.subtitle,
p.page-subtitle,
p.page__subtitle {
  color: white !important;
}
</style>

<style>
  /* Fullscreen background video */
  .bg-video {
    position: fixed;
    top: 0;
    left: 0;
    min-width: 100%;
    min-height: 100%;
    width: auto;
    height: auto;
    z-index: -1;          /* behind everything else */
    object-fit: cover;    /* crop nicely to fill the viewport */
  }

  /* Content overlay on top of the video */
  .content-overlay {
    position: relative;
    z-index: 1;
    padding: 2rem 1.5rem 3rem;
    background: rgba(0, 0, 0, 0.45);  /* semi-transparent so video shows through */
    color: #ffffff;                   /* readable on dark background */
  }

  .content-overlay img {
    border-radius: 10px;
  }
</style>

<!-- Background video -->
<video class="bg-video" autoplay muted loop playsinline>
  <source src="/assets/images/inc87.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

<!-- Your normal content, rendered as Markdown -->
<div class="content-overlay" markdown="1">

# About me

<img src="/assets/images/kevin_pic.jpeg"
     alt="Kevin picture"
     style="float:right; width:200px; margin:0 0 0.75rem 1rem; border-radius:10px;">

In May 2025, I graduated Columbia University with a B.A. in Physics and a B.A. in Mathematics. I am currently working with Prof. [Zoltan Haiman](http://user.astro.columbia.edu/~zoltan/) on electromagnetic (EM) signatures of supermassive black hole binaries. 

So far, I have been focusing on one EM signature called **gravitational self-lensing**, which are periodic microlensing flares expected to occur for edge-on black hole binaries. Anticipating that the Vera Rubin Observatory's Legacy Survey of Space and Time (LSST) will have enough quasars discover these rare signatures, I have estimated **how many such edge-on binaries we expect in the LSST catalog**, and **how to efficiently detect these signals in noisy data**. I am also an associate member of the [LSST Active Galactic Nuclei Science Collaboration](https://agn.science.lsst.org/) and a member of the Binary Follow-up Task Force Subgroup, which aims to .

# Research Interests

I am interested in using **time-domain and multi-wavelength observations** to identify sub-parsec supermassive black hole binaries through their transient EM signatures, including:

- Self-lensing flares (see background video, credit: Jordy Davelaar)
- Relativistic Doppler boosting
- (Hydrodynamical) Accretion variability
- Merger-driven Signatures
- Spectral signatures (e.g. shifting broad lines)
- Blazar/Jet-related variability.

Long term, I hope to connect time-domain EM observations with signals from **Pulsar Timing Arrays (PTAs)** or the **Laser Interferometer Space Antenna (LISA)** to better understand supermassive black hole binaries from a multi-messenger perspective.

I am also interested in **Tidal Disruption Events**, the recently discovered **Quasi-Periodic Eruptions**, and also other high-energy transients.

## Contact Me at:
- [ksp2136@columbia.edu](mailto:ksp2136@columbia.edu)


</div>
