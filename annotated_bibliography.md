---
title: Annotated Bibliography
author: Nate Lant
bibliography: bibliography.bib
output: pdf_document
---

```r
biblio <- bibtex::read.bib("bibliography.bib")
```

So far this is just notes on what I've read until I can format this correctly and get the ```.bib``` file working.

## Berlin Taxis
Bischoff J, Maciejewski M (2016). "Autonomous Taxicabs in Berlin, â€“ A Spatiotemporal Analysis of Service Performance.", _Transportation Research Procedia_, *19*, 176-186. ISSN 23521465,, doi: 10.1016/j.trpro.2016.12.078 (URL:, https://doi.org/10.1016/j.trpro.2016.12.078), <URL:, www.sciencedirect.com, https://linkinghub.elsevier.com/retrieve/pii/S235214651630864X>.

### Notes

They tested the effect on traffic from empty cars and demand shift as people switch from public transit.

They show how they scale from the 100% base scenario to the 10% without describing how they scaled down trip rates and network capacity (maybe described in previous paper).

Helpful graphics include the passenger waiting times during time of day, the productivity of the vehicles during time of day, and spatial distribution of waiting times and empty rides.

They found 10% of transit riders switched to autonomous taxis (only measured on the city center model, no outskirts). No explanation was given.

### Abstract


## Simulation of city-wide replacement of private cars with autonomous taxis in Berlin (Joschka Bischoff, Michal Maciejewski, 2016)
Bischoff J, Maciejewski M (2016). "ScienceDirect Simulation of, city-wide replacement of private cars with autonomous taxis in, Berlin." _Procedia Computer Science_, *83*, 237-244. doi:, 10.1016/j.procs.2016.04.121 (URL:, https://doi.org/10.1016/j.procs.2016.04.121), <URL:, www.sciencedirect.com>.

### Notes
Goal is to find optimum number of autonomous taxis (ATs) to service the city of Berlin, by replacing the private cars. They came up with 100,000 (not sure how exactly)

Details include the dispatching strategy using the demand-supply balancing strategy, _undersupply_ and _oversupply_.

I think the dispatch algorithm should include a buffer distance around the request. The model should be seen from the customer's perspective.

Data not supported...
- The split of car and public transit.
- Section 3.2, certain adaptations pertaining to shortest path search...
- What are taxi ranks (section 4)
- 4.2, the graphs all look the same, and they don't talk about why 100,000 vehicles were chosen. "It was a good compromise..."
- 4.3 the Replacement ratio... is it 1:10 or 1:12?
- 4.3.2 where did they get the 40 min utilization of CDVs?
- Conclusion, total drive time? what is it?

### Abstract

## Help
I need to figure out the ```.bib``` file.

I also need to actually write an abstract.

# References
