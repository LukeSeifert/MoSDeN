---
title: 'MoSDeN: A Python package calculating improved delayed neutron group parameters'
tags:
    - Python
    - molten salt reactors
    - delayed neutron precursors
    - nuclear data
authors:
    - name: Luke Seifert
      orcid: 0000-0002-9860-4341
      affiliation: 1 
      corresponding: true
    - name: Kathryn Huff
      orcid: 0000-0002-7075-6802
      affiliation: 2
    - name: Madicken Munk
      orcid: 0000-0003-0117-5366
      affiliation: 3 
affiliations:
    - name: Department of Nuclear, Plasma, and Radiological Engineering, University of Illinois Urbana-Champaign, Urbana, IL
      index: 1
    - name: Nuclear Engineering & Engineering Physics, University of Wisconsin-Madison, Madison, WI
      index: 2
    - name: School of Nuclear Science and Engineering, Oregon State University, Covallis, OR
date: 03 July 2026
bibliography: paper.bib
---

# Summary
DNPs are approximated using few groups.
MSRs use conventional groups.
These groups do not account for MSR effects that alter behavior.
This tool serves provides a method for calculating improved parameters.

# Statement of Need
Discuss how this tool combines existing methodologies and offers a novel approach
Who is this for? What problem does it solve?

# State of the Field
Discuss existing tools (other microscopic approaches, other approaches for MSRs)

# Software Design
Discuss flow from preprocess to concentrations to count rate to group fit to post process
Explain design/architecture you chose and exaplin why you chose it (beyond superficial code structure description)
Talk about different models and their purposes

# Research Impact Statement
Publications, external use, integrations (compelling and specific, not aspirational)
Dissertation
Publication in review with NSE
Novel analyses

# AI Usage Disclosure
Some LLM usage was used for small functions used for a single calculation.
Any function that used an LLM has unit tests hand written to evaluate and confirm its accuracy for applicable use cases (base.get_irrad_index function specifically).

# Acknowledgements

This material is based upon work supported in part by an Integrated University Program Graduate Fellowship. I am grateful for this generous support.
Funding for this work was supported by the Department of Nuclear, Plasma, and Radiological Engineering at the University of Illinois at Urbana-Champaign.
Any opinions, findings, conclusions or recommendations expressed in this publication are those of the author(s) and do not necessarily reflect the views of the Department of Energy Office of Nuclear Energy.

Thanks to Nathan Glaser, Matthew Disimone, Rhys MacMillan, Bryan Park, Owen Strong, Elijah Capps, Liam Pohlmann, Zo\"{e} Richter, and all other members of the Advanced Reactors and Fuel Cycles Group for their help in reviewing the code and the writing in this work.
Thanks to Kathryn Huff and Madicken Munk for their advice and guidance during the development of this work.
Thanks to Tomasz Kozlowski, April Novak, Samuel Walker, and Daniel Katz for their feedback on this work.

# References