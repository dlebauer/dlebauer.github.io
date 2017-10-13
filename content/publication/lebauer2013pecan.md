+++
abstract = "Ecological models help us understand how ecosystems function, predict responses to global change, and identify future research needs. However, widespread use of models is limited by the technical challenges of model-data synthesis and information management. \n To address these challenges, we present a ecoinformatic workflow, the Predictive Ecosystem Analyzer (PEcAn), that facilitates model analysis. Herein we describe the PEcAn modules that synthesize plant trait data to estimate model parameters, propagate parameter uncertainties through to model output, and evaluate the contribution of each parameter to model uncertainty. We illustrate a comprehensive approach to the estimation of parameter values, starting with a statement of prior knowledge that is refined by species level data using Bayesian meta-analysis; this is the first use of a rigorous meta-analysis to inform the parameters of a mechanistic ecosystem model. \n Parameter uncertainty is propagated using ensemble methods to estimate model uncertainty. Variance decomposition allows us to quantify the contribution of each parameter to model uncertainty; this information can be used to prioritize subsequent data collection. By streamlining the use of models and focusing efforts to identify and constrain the dominant sources of uncertainty in model output, the approach used by PEcAn can speed scientific progress. \n      We demonstrate PEcAn's ability to incorporate data to reduce uncertainty in productivity of a perennial grass monoculture (Panicum virgatum L.) modeled by the Ecosystem Demography model.  Prior estimates were specified for fifteen model parameters, and species-level data were available for seven of these. Meta-analysis of species-level data substantially reduced the contribution of three parameters (specific leaf area [SLA], maximum carboxylation rate, and stomatal slope) to overall model uncertainty. By contrast, root turnover rate, root respiration rate, and leaf width had little effect on model output, therefore trait data had little impact on model uncertainty. \n For fine root allocation the decrease in parameter uncertainty was offset by an increase in model sensitivity. Remaining model uncertainty is driven by growth respiration, fine root allocation, leaf turnover rater, and SLA. By establishing robust channels of feedback between data collection and ecosystem modeling, PEcAn provides a framework for more efficient and integrative science."
abstract_short = "A new approach to the use of crop and ecosystem simulation models as a framework for synthesis of heterogeneous data and mechanistic understanding of how agricultural ecosystem function. Facilitates the prioritization of research directions to optimize data collection and model improvement. "
authors = ["David LeBauer", "Dan Wang", "Katherine Richter", "Carl Davidson", "Michael Dietze"]
date = "2013-05-01"
image_preview = ""
math = true
publication_types = ["2"]
publication = "In *Ecological Monographs*."
publication_short = "In *Ecol. Mon.*"
selected = true
title = "Facilitating feedbacks between field measurements and ecosystem models."
url_code = "https://github.com/dlebauer/pecan-archives"
#url_dataset = "https://betydb.org"
url_pdf = "publication/lebauer2017betydb.pdf"
#url_project = "project/lebauer2017betydb/"
#url_slides = "#"
#url_video = "#"

[[url_custom]]
name = "F1000 Recommendation"
url = "https://f1000.com/prime/718024607"
#name = "Custom Link"
#url = "http://www.example.org"

# Optional featured image (relative to `static/img/` folder).
[header]
image = "lebauer2013pecan.png"
caption = "Figure 7. Sensitivity analysis and variance decomposition to determine what sources of uncertainty are most important, given what we can measure and what we hypothesize about how the system operates in the form of a mechanistic crop simulation model. Panels show for each trait a) uncertainty and variablility in the trait itself, b) sensitivity of yield predictions to variance in the trait and c) amount of uncertainty in yield prediction due to the trait."

+++

