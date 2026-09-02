---
layout: splash
permalink: /
title: ""
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

{% include home-hero.html %}

<section class="home-section home-section--research">

  <div class="home-section__header">
    <span class="home-eyebrow">Research interests</span>

    <h2>
      Understanding economic and financial systems
      through quantitative methods.
    </h2>

    <p>
      My interests lie at the intersection of economics, finance,
      econometrics, statistics, and data science. I am particularly
      interested in combining economic theory with empirical and
      computational methods.
    </p>
  </div>


  <div class="home-grid home-grid--research">

    <article class="home-card">
      <span class="home-card__number">01</span>

      <h3>Monetary Economics</h3>

      <p>
        Monetary policy, transmission mechanisms, and the interaction
        between macroeconomic and financial dynamics.
      </p>

      <div class="home-card__topics">
        <span>Monetary policy</span>
        <span>Macro-finance</span>
        <span>Transmission</span>
      </div>
    </article>


    <article class="home-card">
      <span class="home-card__number">02</span>

      <h3>Financial Econometrics</h3>

      <p>
        Time-series analysis, structural identification, causal inference,
        and statistical modelling of economic and financial data.
      </p>

      <div class="home-card__topics">
        <span>Time series</span>
        <span>SVAR</span>
        <span>Causal inference</span>
      </div>
    </article>


    <article class="home-card">
      <span class="home-card__number">03</span>

      <h3>Machine Learning</h3>

      <p>
        Statistical learning and computational methods for analysing
        economic and financial systems.
      </p>

      <div class="home-card__topics">
        <span>Machine learning</span>
        <span>Deep learning</span>
        <span>Data science</span>
      </div>
    </article>


    <article class="home-card">
      <span class="home-card__number">04</span>

      <h3>Financial Markets</h3>

      <p>
        Financial intermediation, market dynamics, risk modelling,
        and quantitative applications in finance.
      </p>

      <div class="home-card__topics">
        <span>Financial markets</span>
        <span>Risk</span>
        <span>Intermediation</span>
      </div>
    </article>

  </div>

</section>


<section class="home-section home-section--featured">
  <div class="home-section__header">
    <span class="home-eyebrow">Featured research</span>
    <h2>Monetary Policy and the Pandemic</h2>
    <p>
      An empirical study of the effects of monetary policy during the
      COVID-19 period using structural vector autoregressive methods.
    </p>
  </div>

  <div class="home-feature">

    <div class="home-feature__image">
      <img
        src="{{ '/images/TFG-ECOEST_Sastre_2025.png' | relative_url }}"
        alt="Monetary Policy and the Pandemic research project"
      >
    </div>

    <div class="home-feature__content">
      <span class="home-feature__tag">Econometrics · Monetary Policy · SVAR</span>

      <h3>Monetary Policy and the Pandemic</h3>

      <p>
        Undergraduate thesis examining the effects of monetary policy during
        the COVID-19 period through empirical and quantitative methods.
      </p>

      <div class="home-actions">
        <a
          href="{{ '/files/TFG-ECOEST_Sastre_2025.pdf' | relative_url }}"
          class="btn btn--primary"
        >
          Read thesis
        </a>

        <a
          href="{{ '/portfolio/' | relative_url }}"
          class="home-link"
        >
          View projects <span aria-hidden="true">→</span>
        </a>
      </div>
    </div>

  </div>
</section>


<section class="home-section home-section--writing">
  <div class="home-section__header home-section__header--row">
    <div>
      <span class="home-eyebrow">Writing</span>
      <h2>Ideas beyond the research.</h2>
    </div>

    <a
      href="{{ '/year-archive/' | relative_url }}"
      class="home-link"
    >
      View all writing <span aria-hidden="true">→</span>
    </a>
  </div>

  <article class="home-writing-card">
    <div>
      <span class="home-writing-card__meta">Essay · 2026</span>
      <h3>The genius of the Lagrangian</h3>
      <p>
        An accessible exploration of constrained optimisation and why the
        Lagrangian is such a powerful idea in economics and mathematics.
      </p>
    </div>

    <a
      href="{{ '/posts/2026/08/blog-post-1/' | relative_url }}"
      class="home-link"
      aria-label="Read The genius of the Lagrangian"
    >
      Read article <span aria-hidden="true">→</span>
    </a>
  </article>
</section>


<section class="home-section home-section--contact">
  <div class="home-contact">
    <div>
      <span class="home-eyebrow">Get in touch</span>
      <h2>Interested in quantitative economics and finance?</h2>
      <p>
        Explore my projects, research interests, and academic work.
      </p>
    </div>

    <a
      href="mailto:rocsastre.research@gmail.com"
      class="btn btn--primary"
    >
      Contact me
    </a>
  </div>
</section>
