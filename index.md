---
layout: none
permalink: /
---

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Kevin Park</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    /* Basic reset */
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      padding: 0;
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
    }

    /* Fullscreen background video */
    .bg-video {
      position: fixed;
      top: 0;
      left: 0;
      min-width: 100%;
      min-height: 100%;
      width: auto;
      height: auto;
      z-index: -1;
      object-fit: cover; /* behave like background-size: cover */
    }

    /* Content overlay on top of the video */
    .content-overlay {
      position: relative;
      z-index: 1;
      max-width: 900px;
      margin: 0 auto;
      padding: 2rem 1.5rem 3rem;
      background: rgba(0, 0, 0, 0.45); /* adjust opacity if you want */
      color: #fff;
      line-height: 1.6;
    }

    .content-overlay img {
      border-radius: 10px;
    }

    a {
      color: #aad4ff;
    }

    @media (max-width: 700px) {
      .content-overlay {
        padding: 1.5rem 1rem 2rem;
      }
    }
  </style>
</head>
<body>

  <!-- Background video -->
  <video class="bg-video" autoplay muted loop playsinline>
    <source src="/assets/images/mytalk.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>

  <!-- Main content; markdown is still processed inside this div -->
  <div class="content-overlay" markdown="1">

# Kevin Park  
### Supermassive Black Hole Binaries, Quasars, LSST, Gravitational Self-Lensing

# About me

<img src="/assets/images/kevin_pic.jpeg"
     alt="Kevin picture"
     style="float:right; width:200px; margin:0 0 0.75rem 1rem; border-radius:10px;">

In May 2025, I graduated Columbia University with a B.A. in Physics and a B.A. in Mathematics. I am currently working with [Zoltan Haiman](http://user.astro.columbia.edu/~zoltan/) on electromagnetic (EM) signatures of supermassive black hole binaries (SMBHBs). 

So far, I have been focusing on one EM signature called **gravitational self-lensing**, which for edge-on black hole binaries aligning with respect to our line of sight. Anticipating that the Vera Rubin Observatory's Legacy Survey of Space and Time (LSST) will have enough quasars discover these rare signatures, I have estimated **how many such edge-on binaries we expect in the LSST catalog**, and **how to efficiently detect these signals in noisy data**. I am also an associate member of the [LSST Active Galactic Nuclei Science Collaboration](https://agn.science.lsst.org/) and a member of the Binary Follow-up Task Force Subgroup.

# Research Interests

I am interested in searching for sub-pc **supermassive black hole binaries** using their **transient EM signatures**, including:

- Self-lensing flares
- Relativistic Doppler boosting
- (Hydrodynamical) Accretion variability
- Merger Signatures
- Spectral signatures (e.g. shifting broad lines)
- Blazar/Jet-related variability and flares.

Eventually, I would like to do multi-messenger astrophysics with **Pulsar Timing Arrays (PTAs)** and **Laser Interferometer Space Antenna (LISA)**.

I am also interested in **Tidal Disruption Events** and the recently discovered **Quasi-Periodic Eruptions**.

## Contact Me at:
- [ksp2136@columbia.edu](mailto:ksp2136@columbia.edu)

  </div>

</body>
</html>
