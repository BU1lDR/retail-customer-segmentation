<!-- Rendered into the profile README at github.com/BU1lDR by
     BU1lDR/BU1lDR/tools/build_readme.py, on the hour and on dispatch.
     Format: "# <display name> — <heading tail>", a one-line meta row, then at most
     two short paragraphs. Placeholders filled from the GitHub API: {license}
     {version} {live} {description}. Every figure below is a copy of a key in
     outputs/facts.json, and tools/check_docs_drift.py holds this file to it in CI
     the same way it holds the notebook's prose. -->

# Retail customer segmentation — 1,067,371 transaction lines

{license} · Jupyter · pandas · scikit-learn · UCI Online Retail II (CC BY 4.0) · IBM SkillsBuild × BharatCares capstone

Nine logged cleaning steps, RFM segmentation cross-checked against K-Means, CLV estimation and cohort retention on a UK online retailer's two years of orders. Names the 683 high-value accounts worth £1,689,620 that have stopped ordering; the top 20% of identified customers hold 77.2% of identified revenue. States what the data cannot support, including its own 12-month CLV projection that runs 2.91× high.

Every figure is a named key in a committed `outputs/facts.json`, and CI holds the README, the notebook's prose and committed outputs, the generated report and this paragraph to it, so none of the five can drift from the analysis unnoticed.
