---
layout: archive
title: "Resources"
permalink: /resources/
author_profile: true
---

<style>
  /* ---------- Typography ---------- */
  .page__content p,
  .page__content li {
    text-align: justify;
    hyphens: auto;
  }

  .last-updated {
    text-align: right;
  }

  /* ---------- Details / summary ---------- */
  summary {
    display: block;
    cursor: pointer;
  }

  summary::before {
    margin-left: 1ch;
    display: inline-block;
    content: '+';
    transition: transform 0.2s ease;
  }

  details[open] > summary::before {
    transform: rotate(45deg);
  }

  /* ---------- Separators ---------- */
  hr {
    border: none;
    height: 2px;
    background-color: #b9babd;
  }

  /* ---------- Outlook list ---------- */
  #outlook-section ul {
    list-style: none;
    padding-left: 0;
  }
</style>

<p class="last-updated">
  <small><em>Last updated: Jan 08, 2026</em></small>
</p>

<p>
  Here you can find a series of tools, materials, and creative works I have been
  developing throughout my research and outreach activities.
  Feel free to get in touch for anything you'd like to discuss!
</p>

<div id="outlook-section">
  <h2 id="outlook">Outlook</h2>
  <ul>
    <li>🖥️ <a href="#github-bioinformatics"><b>Introduction to bioinformatics</b></a></li>
    <li>🌳 <a href="#physco"><b>phySCO: phylogenomics from Single-Copy Orthologs</b></a></li>
    <li>🧪 <a href="#wetlab-protocols"><b>Wet-lab protocols</b></a></li>
    <li>🎨 <a href="#illustrations"><b>Illustration portfolio</b></a></li>
    <li>🖼️ <a href="#posters"><b>Poster collection</b></a></li>
    <li>💰 <a href="#grants"><b>Grant and funding applications</b></a></li>
  </ul>
</div>

<!-------------------------------------------------------------------------------------->

<h2 id="github-bioinformatics">Introduction to bioinformatics</h2>
<hr>

<p>
  In my GitHub personal page you can find a
  <b><a href="https://github.com/filonico/UNIX_and_bash_basics" target="_blank">
  brief introduction to bioinformatics</a></b>.
  There, I explain the <b>most common bash commands</b> that bioinformaticians
  usually deal with.
</p>

<p>
  Take it as a friendly resource for accessing commonly used commands in early
  bioinformatics.
</p>

[![bash github tutorial](https://filonico-readme-stats.vercel.app/api/pin/?username=filonico&repo=UNIX_and_bash_basics&show_icons=true&theme=transparent)](https://github.com/filonico/UNIX_and_bash_basics)

<p><a href="#outlook">↑ Go up ↑</a></p>

<!-------------------------------------------------------------------------------------->

<h2 id="physco">phySCO: phylogenomics from Single-Copy Orthologs</h2>
<hr>

<p>
  Tired of tedious phylogenetic pipelines to generate species trees after a
  successful BUSCO analysis? Fed up with wasting time copying and pasting
  commands to align, trim sequences, and infer trees?
</p>

<p>
  Here's the solution! <b>Let phySCO transform your workflow today!</b>
</p>

<p>
  phySCO is an all-in-one python tool that (i) takes the output of a series of
  BUSCO analyses, (ii) retrieves ubiquitous single-copy BUSCO orthologs,
  (iii) aligns and trims them, and (iv) infers the corresponding ML
  phylogenetic tree using a partitioned analysis.
</p>

[![phySCO](https://filonico-readme-stats.vercel.app/api/pin/?username=filonico&repo=phySCO&show_icons=true&theme=transparent)](https://github.com/filonico/phySCO)

<p><a href="#outlook">↑ Go up ↑</a></p>

<!-------------------------------------------------------------------------------------->

<h2 id="wetlab-protocols">Wet-lab protocols</h2>
<hr>

<p>
  Researchers always complain—rightly—that bioinformatic code is not always
  shared and that analyses are rarely fully reproducible.
</p>

<p>
  But have you ever thought about wet-lab protocols? How many times have you
  tried to run an experiment for the first time, only to find yourself
  piecing together details from five different papers just to create a
  first draft?
</p>

<p>
  Just like bioinformatic pipelines,
  <b>wet-lab protocols should be openly shared and easy to access</b>.
  That's why I decided to start documenting my protocols on GitHub, where
  anyone can use them and browse previous versions.
</p>

[![Wet-lab protocols](https://filonico-readme-stats.vercel.app/api/pin/?username=filonico&repo=wetlab_protocols&show_icons=true&theme=transparent)](https://github.com/filonico/wetlab_protocols)

<p><a href="#outlook">↑ Go up ↑</a></p>

<!-------------------------------------------------------------------------------------->

<h2 id="illustrations">Illustration portfolio</h2>
<hr>

<p>
  In my free time I like drawing, and sometimes I try to merge this hobby
  with my research work to create illustrations for papers and other
  publications.
</p>

<p>
  Feel free to get in touch if you may need something of this kind.
</p>

<ul>
  <li>
    <b>Animal icons</b>. Used to decorate phylogenetic trees, plots, and
    other figures—mostly focused on branchiopods and bivalves.
  </li>
</ul>

![animal silhouettes](/images/silhouettes_animals.png)

<ul>
  <li>
    <b>Sex determination</b>. Illustrations for presentations about the
    confusing sex determination of bivalves.
  </li>
</ul>

![sex determination](/images/sexDet_coverImage.png)

<ul>
  <li>
    <b>Insect developmental biology</b>. Illustrations used in the chapter
    “Hexapods: reproductive biology and life cycles” in
    <i>Systematics and evolution of hexapods</i>, Liguori Editori (2023).
    All rights reserved.
  </li>
</ul>

![insect development](/images/insect_development.png)

<p><a href="#outlook">↑ Go up ↑</a></p>

<!-------------------------------------------------------------------------------------->

<h2 id="posters">Poster collection</h2>
<hr>

<p>
  Here you can find PDFs of posters I was involved in. Posters that I
  personally presented are indicated by a DNA symbol.
</p>

<details>
  <summary><i><small>More</small></i></summary>
  <ul>
    <li>🧬 <b>Visions from the past: elucidating opsin evolution in a non-bilaterian Metazoa lineage</b>. Roscoff, 2025.</li>
    <li>🧬 <b>How to detect sex-determining genes through molecular evolution</b>. Naples, 2024.</li>
  </ul>
</details>

<p><a href="#outlook">↑ Go up ↑</a></p>

<!-------------------------------------------------------------------------------------->

<h2 id="grants">Grant and funding applications</h2>
<hr>

<p>
  Survivorship bias is the tendency to draw conclusions only from those who
  succeeded, while overlooking those who did not.
</p>

<p>
  Academic careers are no exception. Behind every successful researcher,
  there are grant applications and experiments that failed.
</p>

<p>
  Inspired by this idea, I started gathering all my applications below,
  regardless of their outcome. I hope this may be helpful to others.
</p>

<details>
  <summary><i><small>More</small></i></summary>
  <ul>
    <li><b>Rosemary Grant Advanced Award</b> (SSE, 2023) — Unsuccessful 🔴</li>
    <li><b>Marco Polo Mobility Programme</b> (University of Bologna, 2023) — Successful 🟢</li>
    <li><b>R. C. Lewontin Early Award</b> (SSE, 2023) — Unsuccessful 🔴</li>
  </ul>
</details>

<p><a href="#outlook">↑ Go up ↑</a></p>