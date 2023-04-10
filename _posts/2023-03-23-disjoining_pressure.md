---
layout: distill
title: Disjoining pressure
description: Derivation of disjoining pressure on a flat surface
giscus_comments: false
date: 2023-03-23

authors:
  - name: Shivam Parashar
    #affiliations:
    #  name: Rutgers University

bibliography: 2018-12-22-distill.bib

# Optionally, you can add a table of contents to your post.
# NOTES:
#   - make sure that TOC names match the actual section names
#     for hyperlinks within the post to work correctly.
#   - we may want to automate TOC generation in the future using
#     jekyll-toc plugin (https://github.com/toshimaru/jekyll-toc).
toc:
  - name: Equations
    # if a section has subsections, you can add them as follows:
    # subsections:
    #   - name: Example Child Subsection 1
    #   - name: Example Child Subsection 2
  - name: Citations
  - name: Footnotes
  - name: Code Blocks
  - name: Interactive Plots
  - name: Layouts
  - name: Other Typography?

# Below is an example of injecting additional post-specific styles.
# If you use this post as a template, delete this _styles block.
_styles: >
  .fake-img {
    background: #bbb;
    border: 1px solid rgba(0, 0, 0, 0.1);
    box-shadow: 0 0px 4px rgba(0, 0, 0, 0.1);
    margin-bottom: 12px;
  }
  .fake-img p {
    font-family: monospace;
    color: white;
    text-align: left;
    margin: 12px 0;
    text-align: center;
    font-size: 16px;
  }

---

## Equations
 
Consider a box where vapor and liquid equilibrium exists. 
The liquid is on the top of the solid surface. The system is at constant (T, P).

The chemical potential of vapor phase and liquid phases are $\mu_v$ and $\mu_l$.
$dN$ molecules from the vapor phase transfers to liquid phase and increase the thickness by
$\dt$. The gibbs free energy change for this process is

\begin{equation}
dG = -SdT + VdP + \mu_v dN_v + \mu_l dN_l + \gamma dA
\end{equation}