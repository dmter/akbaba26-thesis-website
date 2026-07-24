# Geovisual Storytelling of Climate-Induced Migration Patterns in Urban Environments

Diploma (master's) thesis website by **Demet Akbaba**, Department of Geoinformatics.

This is a static website presenting the cartographic outputs of a diploma thesis that uses
geovisual storytelling to communicate how climate stressors (droughts, floods) relate to
human migration in urban environments. It compares two contrasting cases: **slow-onset**
drought-driven migration across urban regions of Europe (2015–2024), and **rapid-onset**
displacement in Southern Malawi following Tropical Cyclone Freddy (2023).

## What is on the site

- **18 static thematic maps** produced in ArcGIS Pro, organised into the two case studies.
  Each map opens in a full-screen overlay with a 2–3 sentence explanation (method + main
  finding), a click-to-zoom view for inspecting fine detail, and prev/next arrows to move
  between maps without closing the overlay.
- A methodology flowchart of the full workflow, from data acquisition through ground-truthing
  to publication and user testing.
- Objectives, Methods and Workflow, Map Outputs, Results, Contribution, Downloads, and Contact
  sections summarising the thesis, plus a footer strip with the partner institutions' logos
  (Paris-Lodron University Salzburg, Palacký University Olomouc, Erasmus+).

## Case studies

**Europe — slow-onset (16 maps):** Human Canvas (Wurman dots), two Climate Stress Grid maps,
Economic Magnet, ten annual Demographic Heartbeat maps (2015–2024), and two Typology of
European Countries maps (2018, 2022).

**Malawi — rapid-onset (2 maps):** Displacement Flow (IOM DTM origin–destination) and
Bivariate Susceptibility (population change × landslide exposure).

## How it is built

- Plain **HTML5 + CSS3**. No JavaScript, no frameworks, no external requests — everything
  (styles, icons, images) is self-contained in this folder.
- All interactive behaviour described above (lightbox, zoom, navigation) is implemented
  purely in CSS, using the `:target` pseudo-class and a hidden-checkbox toggle pattern.

## Running locally

Open `index.html` in any modern web browser. No build step or server is required.

## Data sources

Copernicus Climate Data Store & Land Monitoring Service (ERA5-Land, NDVI) · Eurostat & ARDECO ·
IOM Displacement Tracking Matrix · OCHA / Humanitarian Data Exchange · Sentinel-2 & Planet imagery.

## Author and institutions

**Demet Akbaba** — Erasmus Mundus Joint Master's Degree, Copernicus Master in Digital Earth.
Paris-Lodron University Salzburg & Palacký University Olomouc, Department of Geoinformatics.

- PLUS Supervisor: Prof. Dr. Stefan Lang
- UPOL Supervisor: Mgr. Radek Barvíř, Ph.D.
- Contact: demet.akbaba@stud.plus.ac.at

## Note

This GitHub repository is a public source-code copy and backup. The official thesis website
is hosted on the Department of Geoinformatics (KGI) server as part of the formal submission.
