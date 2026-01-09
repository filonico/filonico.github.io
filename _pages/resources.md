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
    <li>
    <b><a href="https://drive.google.com/file/d/1Mw-GgFLSQiBVmWdDHEwQmPVRErn66U0x/view?usp=sharing" target="_blank">Il primo anno di Wood Wide Ants: approcci, risultati e prospettive</a> [The first year of Wood Wide Ants: approaches, results and perspectives]</b>.<br /> <i>Associazione Italiana per lo Studio degli Artropodi Sociali e Presociali [Meeting of the Italian Association for the Study of Social and Presocial Insects] (AISASP)</i>.<br /> Bologna, Italy. Sep 3–5, 2025.
    </li>
    <li>
    🧬 <b><a href="https://drive.google.com/file/d/1SJy0M-vR0e_ay5Wl3rROcIdhrwZkd1L7/view?usp=sharing" target="_blank">Visions from the past: elucidating opsin evolution in a non-bilaterian Metazoa lineage</a></b>.<br /> <i>Jacques Monod Conferences: Origin of metazoans</i>.<br /> Roscoff, France. Jun 16–20, 2025.
    </li>
    <li>
    🧬 <b><a href="https://drive.google.com/file/d/1OROehtrFHCn_U1BPoMQwzHR0HPu9IKj8/view?usp=sharing" target="_blank">How to detect sex-determining genes through molecular evolution: bivalves as a case study</a></b>.<br /> <i>Evoluzione 2024</i>.<br /> Naples, Italy. Sep 9–11, 2024.
    </li>
    <li>
    <b><a href="https://drive.google.com/file/d/1c9WUQQ4pnNtkSr_IR38pH4XSy8kYsY6_/view?usp=sharing" target="_blank">The rise of Branchiopoda genomics: the state of the art and future challenges</a></b>.<br /> <i>SMBE 2023</i>.<br /> Ferrara, Italy. Jul 23–27, 2023.
    </li>
    <li>
    <b><a href="https://drive.google.com/file/d/1tCP67JMO3-8ugBSj8CBTUzEkZK4ZIfEy/view?usp=sharing" target="_blank">Comparing different dating methods on branchiopod phylogeny: MCMCtree and lsd2</a></b>.<br /> <i>SMBE 2023</i>.<br /> Ferrara, Italy. Jul 23–27, 2023.
    </li>
    <li>
    🧬 <b><a href="https://drive.google.com/file/d/1uGF5tZpb5LHcLDHQv1TIR8vcJY4BOiPu/view?usp=sharing" target="_blank">Clues of accelerated molecular evolution in gene families associated wit sex determination in bivalves</a></b>.<br /> <i>Evoluzione 2022</i>.<br /> Ancona, Italy. Sep 4–7, 2022.
    </li>
    <li>
    🧬 <b><a href="https://drive.google.com/file/d/1UvQCD4jXHFAPZVsZ_RtY8YaqNMiMe4OT/view?usp=sharing" target="_blank">First insights and comparative genomics of <i>Hox</i> and <i>ParaHox</i> genes in tadpole shrimps</a></b>.<br /> <i>EuroEvoDevo 2022</i>.<br /> Naples, Italy. May 31–Jun 3, 2022.
    </li>
  </ul>
</details>

<p><a href="#outlook">↑ Go up ↑</a></p>

<!-------------------------------------------------------------------------------------->

<h2 id="grants">Grant and funding applications</h2>
<hr>

<p>
The <b>survivorship bias</b> is the tendency to draw conclusions only on the basis of <em>those who survived</em>, while overlooking <em>those who didn't</em>. As one great professor once taught me, this bias is particularly strong in evolutionary biology, and we should always be aware of its existance.
</p>

<p>
But the survivorship bias is more widespread than we think, and <b>academic careers are no exception</b>. Behind successfull researchers and research lines, there are always (always) grant applications and experiments that didn't succeed.
</p>

<p>
Therefore, also inspired by some collegues, I started gathering below all the grant, award, scholarship, and whatever applications I made—no matter their outcome. Maybe this can be helpful and encouraging to others.
</p>

<details>
  <summary><i><small>More</small></i></summary>
  <ul>
    <li>
    <a href="http://evolutionsociety.org/content/society-awards-and-prizes/graduate-research-excellence-grants/rosemary-grant-advanced-award.html" target="_blank"><b>Rosemary Grant Advanced Award</b></a>.<br /> <i>Society for the Study of Evolution (SSE)</i>. 2023.<br /> Outcome: <b>Unsuccessful</b> 🔴<br /> <a href="https://drive.google.com/file/d/1c_Ki1l_-e2ClXehcMfs9LYaoLKQOUn27/view?usp=sharing" target="_blank">Link to the application</a>.
    </li>
    <li>
    <b>Marco Polo Mobility Programme</b>.<br /> <i>University of Bologna</i>. 2023.<br /> Outcome: <b>Successful</b> 🟢<br /> <a href="https://drive.google.com/file/d/1aqfvqcr78Rt0WJ7odpXxBKf0-K3YsCLI/view?usp=sharing" target="_blank">Link to the application</a>.
    </li>
    <li>
    <a href="https://www.evolutionsociety.org/content/society-awards-and-prizes/graduate-research-excellence-grants/rc-lewontin-early-award.html" target="_blank"><b>R. C. Lewontin Early Award</b></a>.<br /> <i>Society for the Study of Evolution (SSE)</i>. 2023.<br /> Outcome: <b>Unsuccessful</b> 🔴<br /> <a href="https://drive.google.com/file/d/11_a8cWpNMmwWIX1MBjNn5MgGkHE3O6N_/view?usp=sharing" target="_blank">Link to the application</a>.
    </li>
    <li>
    <a href="https://systass.org/linnesys" target="_blank"><b>LinneSys: Systematics Research Fund</b></a>.<br /> <i>The Systematics Association</i>. 2023.<br /> Outcome: <b>Unsuccessful</b> 🔴<br /> <a href="https://drive.google.com/file/d/1TxDKSesx8Im7cUFvJKcWqN_wf0qudwPN/view?usp=sharing" target="_blank">Link to the application</a>.
    </li>
    <li>
    <a href="https://editing.press/bassi" target="_blank"><b>Laura Bassi scolarship for Editorial Assistance</b></a>.<br /> <i>Editing Press</i>. Spring 2023 edition.<br /> Outcome: <b>Successful</b> 🟢<br /> <a href="https://drive.google.com/file/d/19OpZZFrqBNzgeYqR9qROQzv8BbkByMsb/view?usp=sharing" target="_blank">Link to the application</a>.
    </li>
  </ul>
</details>

<p><a href="#outlook">↑ Go up ↑</a></p>