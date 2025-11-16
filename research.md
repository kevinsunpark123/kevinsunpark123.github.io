---
layout: page
title: "Research"
permalink: /Research/
---

<style>
  /* Make this section full-width, breaking out of the centered container */
  .full-width-breakout {
    width: 100vw;
    margin-left: calc(50% - 50vw);
  }

  .research-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 2rem;
    padding: 1.5rem 4vw;
    box-sizing: border-box;
  }

  .research-card {
    flex: 1 1 50%;
    max-width: 50%;
    background: #ffffff;
    border-radius: 12px;
    padding: 1.5rem;
    box-sizing: border-box;
    box-shadow: 0 4px 12px rgba(0,0,0,0.06);
  }

  .research-card h2 {
    margin-top: 0;
    margin-bottom: 0.75rem;
  }

  .research-card img {
    width: 100%;
    height: auto;
    border-radius: 10px;
    margin: 0 0 0.75rem 0;
  }

  @media (max-width: 900px) {
    .research-card {
      flex: 1 1 100%;
      max-width: 100%;
    }
  }
</style>

<div class="full-width-breakout">
  <div class="research-grid">

    <section class="research-card">
      <h2>Detection Methods of Self-Lensing Flares in Supermassive Black Hole Binaries</h2>
      <img src="/assets/images/step3_best_fits.png"
           alt="Matched-filter best fits for self-lensing flares">
      <p>
        We generated mock supermassive black hole binary light curves at realistic observation times
        involving periodic accretion variability, relativistic Doppler boost, self-lensing flares,
        and quasar noise. We develop a three-step matched filter procedure to recover the periodicity
        of the self-lensing flares and injected binary parameters from noise and sparse sampling.
        We also show that standard Lomb-Scargle periodograms are ineffective in recovering injected
        periodicity due to the non-sinusoidal nature of the flares.
      </p>
    </section>

    <section class="research-card">
      <h2>Detection Rates of Black Hole Shadows and Self-Lensing Flares in Supermassive Black Hole Binaries in LSST</h2>
      <img src="/assets/images/N_dips.png"
           alt="Number of detectable dips in LSST">
      <p>
        Following up on a series of three papers which simulate self-lensing flares and dips
        (caused by the black hole shadow) in supermassive black hole binaries with general
        relativistic ray-tracing methods, I calculated the detection rates of flares and dips in LSST.
        The paper was published in
        <a href="https://journals.aps.org/prd/abstract/10.1103/PhysRevD.111.063011">Physical Review D</a>
        and can also be found on
        <a href="https://ui.adsabs.harvard.edu/abs/2025PhRvD.111f3011P/abstract">NASA ADS</a>.
      </p>
    </section>

  </div>
</div>
