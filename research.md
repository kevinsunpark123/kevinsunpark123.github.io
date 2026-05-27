---
layout: page
title: "Research"
permalink: /Research/
---

<style>
  /* Full-width section */
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
    flex: 1 1 calc(50% - 1rem);
    max-width: calc(50% - 1rem);
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
    float: right;
    width: 50%;          /* about half the card width */
    height: auto;        /* keep aspect ratio */
    border-radius: 10px;
    margin: 0 0 0.75rem 1rem; /* space to the left & below */
  }

  @media (max-width: 900px) {
    .research-card {
      flex: 1 1 100%;
      max-width: 100%;
    }
    .research-card img {
      float: none;
      display: block;
      width: 100%;
      margin: 0 0 0.75rem 0;
    }
  }
</style>

<div class="full-width-breakout">
  <div class="research-grid">
    
    <section class="research-card">
      <h2>Discovery of new Little Red Dots in DESI DR1</h2>
      <img src="/assets/images/multipanel_SEDs.png"
           alt="LRD_SEDs">
      <p>
      JWST has unveiled an abundant population of compact broad-line emitters largely at $z\gtrsim4$, the Little Red Dots (LRDs), which might represent a previously unprobed supermassive black hole evolution channel predominant at high redshift. We searched for low-redshift LRDs in the Dark Energy Spectroscopic Instrument (DESI) survey finding eight LRDs at $z=0.2-0.45$, which show spectral features similar to the high-redshift LRDs in the rest-frame optical. The sources are characterized by broad Balmer lines, steep Balmer decrements, compact morphologies, Balmer absorption features. Given the effective volume $4.9 \; {\rm Gpc^3}$ covered by DESI DR1 at $z<0.45$, our sample corresponds to a number density of $1.6\times10^{-9}$Mpc$^{-3}$, indicating a number density $\sim$10,000 times lower than in the first billion years of cosmic time. We find a dearth of luminous and red LRDs at $z<1$ compared to higher-redshift, which could suggest lower gas feeding rates of LRD activity due to higher metallicities at later cosmic epochs.
      </p>
    </section>

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
        The paper can be found at <a href="[https://arxiv.org/abs/2512.08427](https://journals.aps.org/prd/abstract/10.1103/p328-62sl)">Physical Review D</a>.
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

      </p>
    </section>

  </div>
</div>
