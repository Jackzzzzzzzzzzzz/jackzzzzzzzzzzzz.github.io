<style>
/* Neutralize the older Minimal-theme rules before applying the approved design. */
div.wrapper { width: auto; margin: 0 auto; }
header, section, footer {
  float: none; width: auto; position: static;
  margin: 0; padding: 0; border: 0; bottom: auto;
  -webkit-font-smoothing: inherit;
}
section { color: inherit; }
body { overflow-wrap: normal; }
strong { color: inherit; }
a:hover, a:focus { color: var(--accent); font-weight: inherit; }
header h1 a:hover, header h1 a:focus { color: var(--ink); }




/* Custom typography and layout for the existing Minimal theme. */
:root { color-scheme: light; --ink: #202c3b; --muted: #596575; --accent: #185a73; --rule: #dfe5e9; }
* { box-sizing: border-box; }
html { scroll-padding-top: 28px; }
body { margin: 0; padding: 56px 36px 32px; background: #fff; color: var(--ink); font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif; font-size: 16px; line-height: 1.7; -webkit-font-smoothing: antialiased; }
.wrapper { max-width: 1008px; margin: 0 auto; display: grid; grid-template-columns: 280px minmax(0, 1fr); gap: 24px 64px; align-items: start; }
header { position: sticky; top: 40px; min-width: 0; }
header h1 { margin: 0 0 24px; font-size: 32px; font-weight: 650; line-height: 1.18; letter-spacing: -1.15px; }
header h1 a { color: var(--ink); text-decoration: none; }
header img { display: block; width: 100%; height: auto; border-radius: 8px; }
header > p { margin: 18px 0 0; color: var(--muted); font-size: 14px; line-height: 1.75; }
header .view, header .downloads { display: none; }
section { min-width: 0; font-size: 16.5px; line-height: 1.75; }
p { margin: 0 0 18px; }
h1, h2, h3, h4 { color: var(--ink); }
section h2 { margin: 42px 0 19px; padding-bottom: 10px; border-bottom: 1px solid var(--rule); font-size: 23px; line-height: 1.3; font-weight: 650; letter-spacing: -.35px; }
section h3 { margin: 23px 0 10px; font-size: 18px; line-height: 1.45; font-weight: 650; letter-spacing: -.15px; }
a { color: var(--accent); text-decoration: none; text-underline-offset: 3px; }
a:hover { text-decoration: underline; }
a:focus-visible, summary:focus-visible { outline: 2px solid var(--accent); outline-offset: 4px; border-radius: 2px; }
strong { font-weight: 650; }
img { max-width: 100%; height: auto; }
.position { margin: 0 0 5px; font-size: 18px; line-height: 1.45; font-weight: 600; }
.affiliation { margin: 0; color: var(--muted); font-size: 15px; line-height: 1.6; }
.contact-links { display: flex; flex-wrap: wrap; gap: 8px 22px; margin: 19px 0 0; font-size: 14.5px; line-height: 1.6; font-weight: 550; }
.contact-links a { padding: 3px 0; }
.contact-links .cv-link { font-weight: 650; }
.project-status { margin: -2px 0 13px; font-size: 13px; color: var(--muted); }
.research-figure { margin: 22px 0 0; padding: 16px; border: 1px solid var(--rule); border-radius: 8px; }
.research-figure a { display: block; }
.research-figure img { display: block; width: 100%; }
.research-figure figcaption { margin-top: 14px; color: var(--muted); font-size: 13.5px; line-height: 1.65; }
.expertise-group { margin: 0; padding: 18px 0; border-bottom: 1px solid #edf0f2; }
.expertise-group:first-of-type { padding-top: 0; }
.expertise-group.expertise-last { border-bottom: 0; padding-bottom: 0; }
.expertise-group h3 { margin: 0 0 7px; font-size: 17px; }
.expertise-group p { margin: 0; font-size: 15.5px; line-height: 1.75; }
.publication { padding: 0 0 24px; margin: 0 0 24px; border-bottom: 1px solid #edf0f2; }
.publication:last-child { border-bottom: 0; padding-bottom: 0; margin-bottom: 0; }
.publication h3 { margin: 0 0 10px; font-size: 17px; line-height: 1.5; letter-spacing: 0; font-weight: 600; }
.publication .authors { margin: 0 0 8px; font-size: 14px; line-height: 1.7; color: var(--muted); }
.publication .authors strong { color: var(--ink); }
.publication .venue { margin: 0; font-size: 14px; line-height: 1.65; color: var(--ink); }
.publication .contribution { display: inline-block; color: var(--accent); font-weight: 650; }
footer { grid-column: 2; padding-top: 16px; border-top: 1px solid var(--rule); color: var(--muted); font-size: 12px; line-height: 1.6; }
footer p { margin: 0; }
footer small { font-size: inherit; }
ul, ol { padding-left: 24px; }
blockquote { margin: 18px 0; padding-left: 18px; border-left: 2px solid var(--rule); color: var(--muted); }
code { font-size: .9em; }
pre { padding: 16px; background: #f5f7f8; overflow: auto; border-radius: 6px; }
table { border-collapse: collapse; width: 100%; }
th, td { padding: 8px; text-align: left; border-bottom: 1px solid var(--rule); }
@media (max-width: 900px) {
  body { padding: 34px 30px 26px; }
  .wrapper { max-width: 680px; grid-template-columns: minmax(0, 1fr); gap: 28px; }
  header { position: static; display: grid; grid-template-columns: 144px minmax(0, 1fr); gap: 8px 25px; padding-bottom: 26px; border-bottom: 1px solid var(--rule); }
  header img { grid-column: 1; grid-row: 1 / 3; margin: 0; }
  header h1 { grid-column: 2; grid-row: 1; margin: 0; align-self: end; font-size: 30px; }
  header > p { grid-column: 2; grid-row: 2; margin: 0; font-size: 13.5px; line-height: 1.65; }
  footer { grid-column: 1; }
}
@media (max-width: 480px) {
  body { padding: 28px 22px 24px; }
  header { grid-template-columns: 96px minmax(0, 1fr); gap: 8px 18px; }
  header h1 { font-size: 26px; letter-spacing: -.7px; }
  header > p { font-size: 12px; line-height: 1.65; }
  section { font-size: 16px; line-height: 1.75; }
  section h2 { font-size: 22px; margin-top: 34px; }
  .position { font-size: 17px; }
  .affiliation { font-size: 14px; }
  .contact-links { gap: 8px 21px; }
  .research-figure { padding: 10px; }
  .research-figure figcaption { font-size: 13px; }
  .publication h3 { font-size: 16px; }
}
@media print {
  body { padding: 0; font-size: 11pt; }
  .wrapper { display: block; max-width: none; }
  header { position: static; margin-bottom: 24px; }
  header img { width: 110px; }
  header .view { display: none; }
  section { font-size: 11pt; }
  section h2 { break-after: avoid; }
  .publication, .expertise-group, .research-figure { break-inside: avoid; }
  footer { margin-top: 24px; }
}


</style>

<p class="position">PhD student in Nutritional Sciences</p>
<p class="affiliation">University of Illinois Urbana-Champaign</p>

<p class="contact-links">
  <a href="mailto:ruijiez4@illinois.edu">Email</a>
  <a href="https://www.linkedin.com/in/ruijie-jack-zhang/">LinkedIn</a>
  <a href="https://github.com/Jackzzzzzzzzzzzz">GitHub</a>
  <a class="cv-link" href="Jack_Zhang_CV.pdf">CV (PDF)</a>
</p>

## About

I study how intestinal epithelial cells maintain tissue function and regulate mucosal immunity. My work combines molecular and cellular biology, bioinformatics, and machine learning to connect gene regulation with cell states and tissue organization. My broader interests include integrating multi-omics data to understand the molecular mechanisms underlying cancer and chronic inflammatory disease.

## Current Research

My doctoral research investigates how the RNA-binding protein hnRNP I (PTBP1) supports intestinal epithelial function and how its loss alters antimicrobial defense and inflammation in the colon. I integrate single-cell and spatial transcriptomics with molecular assays and quantitative tissue imaging to examine epithelial specialization and mucosal organization.

## Selected Project

### Spatial mapping of intestinal epithelial organization

<p class="project-status">Ongoing research</p>

How does epithelial hnRNP I loss reshape the organization of the colon? I combine tissue annotation, computational unrolling, and single-cell reference mapping to compare epithelial domains and cell-state patterns along anatomical axes. This analysis reveals altered regional epithelial organization and distributions of progenitor-associated signals in knockout tissue.

<figure class="research-figure">
  <a href="assets/images/spatial-unrolling.png">
    <img src="assets/images/spatial-unrolling.png" alt="Annotated colon section, epithelial mask, and computationally unrolled tissue map along proximal–distal and serosa–luminal axes." width="1446" height="726" loading="lazy">
  </a>
  <figcaption><strong>Computational unrolling of colon tissue.</strong> Paired crypt-base and crypt-top annotations define anatomical coordinates for comparing epithelial organization. Select the image to enlarge.</figcaption>
</figure>

## Methods & Expertise

<div class="expertise-group">
  <h3>Computational biology</h3>
  <p>Single-cell and spatial transcriptomics; cell-state classification, tissue deconvolution, differential expression, gene regulatory networks, and splice-junction analysis. Statistical modeling and machine learning in R and Python.</p>
</div>

<div class="expertise-group">
  <h3>Molecular &amp; cellular biology</h3>
  <p>qPCR, Western blotting, chromatin immunoprecipitation (ChIP), and cell and organoid culture to investigate gene regulation and epithelial function.</p>
</div>

<div class="expertise-group expertise-last">
  <h3>Quantitative tissue imaging</h3>
  <p>Multiplex immunofluorescence, confocal and epifluorescence microscopy, and quantitative image analysis using Fiji/ImageJ, QuPath, and Python.</p>
</div>

## Selected Publications

<div class="publication">
  <h3><a href="https://doi.org/10.26599/FSHW.2023.9250038">The impact of short-term changes in sleeping and eating patterns on glucometabolic health and gut microbiota in healthy young adults: a proof-of-concept controlled feeding study</a></h3>
  <p class="authors">Jiehua Chen, <strong>Ruijie Zhang</strong>, Chao Zhou, Louise Weiwei Lu, Dana Feng, Haiqiao Zou, Ran Gao, Xinying Zhang, Peiyi Chen, Jiayue Zhu, Haoxie Xu, Nina Zeng, Cijuan Zhang, Bin Liu, Mingfu Wang, Qian Ge, Caiqun Ouyang, Feng Chen.</p>
  <p class="venue"><em>Food Science and Human Wellness</em>, 2024. <span class="contribution">Co-first author.</span></p>
</div>

<div class="publication">
  <h3><a href="https://doi.org/10.3390/nu15173747">Consumption of Different Egg-Based Diets Alters Clinical Metabolic and Hematological Parameters in Young, Healthy Men and Women</a></h3>
  <p class="authors">Catherine J. Andersen, Lindsey Huang, Fangyi Zhai, Christa Palancia Esposito, Julia M. Greco, <strong>Ruijie Zhang</strong>, Rachael Woodruff, Allison Sloan, Aaron R. Van Dyke.</p>
  <p class="venue"><em>Nutrients</em>, 2023.</p>
</div>

<div class="publication">
  <h3><a href="https://doi.org/10.1080/10408398.2021.1974335">Missing puzzle pieces of time-restricted-eating (TRE) as a long-term weight-loss strategy in overweight and obese people? A systematic review and meta-analysis of randomized controlled trials</a></h3>
  <p class="authors">Jie-Hua Chen, Louise Weiwei Lu, Qian Ge, Dana Feng, Jianfeng Yu, Bin Liu, <strong>Ruijie Zhang</strong>, Xinying Zhang, Caiqun Ouyang, Feng Chen.</p>
  <p class="venue"><em>Critical Reviews in Food Science and Nutrition</em>, 2023.</p>
</div>


