---
title: Economics
layout: page
---
<!--
MVP prediction 

HUD merge

Maintaining econ website

Add names for origami pieces
-->
## Academic Interest
My passion in economics lies in leveraging data and theory to fundamentally understand structures and dynamics. I'm interested in various areas in economics, especially in IO and financial economics.

Relevant courses:
- Industrial Organization
- Econometrics
- Economics of Risk, Uncertainty & Information
- Mathematics of Derivative Securities
- Data Cleaning with Python

<b>Working Major Thesis</b>: Measuring firm-specific demand shock generated spillover in a platform market

<br>

## Past Experiences

<style>
.proj-card {
  border: 1px solid #e2e2e2;
  border-radius: 8px;
  padding: 20px 24px;
  margin: 24px 0;
}
.proj-card h3 {
  margin: 0 0 4px 0;
}
.proj-tagline {
  color: #555;
  font-style: italic;
  margin-bottom: 12px;
}
.proj-meta {
  font-size: 0.85rem;
  color: #888;
  margin-bottom: 12px;
}
.proj-meta span {
  display: inline-block;
  background: #f1f1f1;
  border-radius: 4px;
  padding: 2px 8px;
  margin: 2px 4px 2px 0;
}
.proj-card ul {
  margin: 8px 0;
}
.proj-links a {
  margin-right: 16px;
  font-weight: bold;
}
.proj-figure {
  margin-top: 16px;
  text-align: center;
}
.proj-figure img {
  max-width: 100%;
  border: 1px solid #eee;
}
.proj-figure .caption {
  font-size: 0.75rem;
  color: #888;
  margin-top: 4px;
}
</style>

<div class="proj-card">
  <h3>Census–HUD Data Merge</h3>
  <div class="proj-tagline">Linking HUD median family income records to Census tract demographics on a county level</div>
  <div class="proj-meta">
    <span>Stata</span>
    <span>Census data</span>
    <span>HUD data</span>
    <span>Professional work</span>
  </div>
  <p><b>Context: </b> Stata Merge conducted at Kenyon Consulting for damage analysis</p>
  <p><b>Approach:</b></p>
  <ul>
    <li>Data sources & granularity - HUD Section 8 administrative records indexing on FIPS code, years, merging with appropriate Census years
    </li>
    <li>Issues encountered - New England counting on town, deduping, missing entries"</li>
    <li>Validations - Manual search on county movements, sample listing, filtering </li>
  </ul>
  <p><b>Result:</b> Produced an analysis-ready panel of 150k records, 99% matched</p>
  <div class="proj-links">
    <!-- <a href="#">Writeup</a> <a href="#">Data source</a> -->
  </div>
  <!--
  <div class="proj-figure">
    <img src="assets/Econ/census-hud-merge.png" alt="Merge result">
    <div class="caption">[Figure caption]</div>
  </div>
  -->
</div>

<div class="proj-card">
  <h3>NBA MVP Predictor</h3>
  <div class="proj-tagline">Predicting the season MVP from player & team performance stats</div>
  <div class="proj-meta">
    <span>Stata</span>
    <span>NBA stats</span>
    <span>Prediction / modeling</span>
  </div>
  <p><b>Context:</b> Was invested in the Shai MVP debate. Wanted to see what the stats say.</p>
  <p><b>Approach:</b></p>
  <ul>
    <li>Data - Player statistics from past 30 years scraped from Basketball Reference with Python Request, along with season MVP</li>
    <li>Addressed issues such as non-standard characters, mid-season trades, etc</li>
    <li>Tackled multicollinearity by iteratively testing models with Variance Inflation Factors</li>
  </ul>
  <p><b>Result:</b>Probability ranking of MVP candidates for 2026. Top 3 (It's currently the mid-season): Nikola Jokić, Shai Gilgeous-Alexander, Giannis Antetokounmpo </p>
  <div class="proj-links">
    <!-- <a href="#">Writeup</a> -->
  </div>
  <!--
  <div class="proj-figure">
    <img src="assets/Econ/mvp-predictor.png" alt="MVP prediction results">
    <div class="caption">[Figure caption]</div>
  </div>
  -->
</div>

<div class="proj-card">
  <h3>GitHub Data Analysis Repo</h3>
  <div class="proj-tagline">Various data exploration and prediction tools for the Olympics</div>
  <div class="proj-meta">
    <span>Python</span>
  </div>
  <p><b>Context:</b> Data exploration tool, team project for STAT 3250</p>
  <p><b>Approach:</b></p>
  <ul>
    <li>[Data source]</li>
    <li>[Methods]</li>
    <li>[Reproducibility]</li>
  </ul>
  <p><b>Result:</b> [Key finding]</p>
  <div class="proj-links">
    <a href="https://github.com/[user]/[repo]">View on GitHub →</a>
  </div>
</div>