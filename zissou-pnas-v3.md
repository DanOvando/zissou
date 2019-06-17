---
title: The Regional Effects of Marine Protected Areas
author:
  - name: Daniel Ovando
    affiliation: a,1
    email: danovan@uw.edu
  - name: Jennifer E. Caselle
    affiliation: b
  - name: Christopher Costello
    affiliation: b   
  - name: Olivier Deschenes
    affiliation: b  
  - name: Steven D. Gaines
    affiliation: b
  - name: Ray Hilborn
    affiliation: a
  - name: Owen Liu
    affiliation: b        
address:
  - code: a
    address: University of Washington, School of Aquatic and Fishery Science
  - code: b
    address: University of California, Santa Barbara
corresponding_author:
  - code: 1
    text: "To whom correspondence should be addressed. E-mail: danovan@uw.edu"
lead_author_surname: Ovando
author_contributions: |
  DO
  
conflict_of_interest: |
  The authors declare no conflict of interest
abstract: |
  Marine Protected Areas (MPAs) with varying levels of protection cover between 3-7% of the worlds oceans, up from less than 1% in the year 2000. The Convention on Biological Diversity's Strategic Plan for Biodiversity  calls for 10% of coastal waters to be protected inside MPAs by 2020, with other bodies calling for at least 30% of the oceans to be placed in MPAs. This expansion is driven by a desire to achieve conservation benefits inside and outside of MPA borders, and in some cases produce economic benefits to fisheries. Despite the expanding role of MPAs in marine resource management, we lack a clear understanding of what the regional effects of these protected areas might be, and how we might detect them. We used a bio-economic simulation model to demonstrate how the regional effects of MPAs are affected by suite of economic and environmental drivers, and show how commonly used methods to measure MPA effectiveness may fail to capture the the true regional impacts. We present am empirical strategy for estimating regional MPA effects on biomass density using 16 years of data from inside and outside of MPAs within the Channel Islands, California, USA. We find no statistically clear effect of MPAs on total biomass densities of targeted finfish throughout the study region. The next generation of MPA science must address the challenge of understanding and estimating the regional effects of MPAs.
  
significance: |
  Marine protected areas are increasingly being used to manage marine resources. The connected nature of ocean ecosystems means that closing areas to fishing in MPAs may provide conservation and fishery benefits beyond the protected borders. This connectivity presents major challenges for . Our study examines what we should expect the regional conservation and fishery effects of MPAs to be under a broad range of circumstances, and then asks how we can detect the conservation effects of MPAs in the real world. We show that commonly used metrics such as the density of fishes inside and outside of MPAs are a very poor estimator of the true conservation effect of MPAs, and present an alternative method in a case study of the Channel Islands National Marine Sanctuary. We find no statistically clear effect of the network of MPAs in the Channel Islands, which out simulation analysis suggests is entirely reasonable. Our results present a comprehensive analysis of the challenges of designing MPAs for regional effects. 
acknowledgements: |
  This study would not be possible without the thousands of hours of work provided by PISCO divers over the years. Funding for this study was provided by XX. 
keywords:
  - Marine Protected Areas
  - Conservation
  - Fisheries
  - Bio-economic modeling
  - Program Evaluation
  - Channel Islands National Marine Sanctuary
## must be one of: pnasresearcharticle (usual two-column layout), pnasmathematics (one column layout), or pnasinvited (invited submissions only)
pnas_type: pnasresearcharticle
bibliography: My Library.bib
csl: pnas.csl
lineno: false
watermark: false
output: 
  rticles::pnas_article: default
  bookdown::word_document2: default
---







\correspondingauthor{\textsuperscript{1}To whom correspondence should be addressed. E-mail: danovan@uw.edu}


No-take Marine Protected Areas (MPAs), spatial regions in the ocean in which fishing is prohibited, have a long history in the management of marine resources. Traditional cultures in Oceania utilized (often temporary) MPAs as a sort of "fish bank" for times of need [@johannes1978]. Modern MPAs were first put in place primarily as conservation areas, as marine analogs to the terrestrial protection of iconic landscapes like Yellowstone or Kruger National Parks [@iucn1976]. However, over time our goals and expectations for MPAs have evolved; MPAs are now frequently designed to both protect the marine ecosystems within their boundaries, and bolster fish populations and fishing opportunities throughout the region in which they are located (what we term "regional-scale effects") [@gaines2010].  


With these goals of both conservation and resource management in mind, the Convention on Biological Diversity’s Strategic Plan for Biodiversity calls for 10% of coastal waters to be protected inside MPAs by 2020. Despite these goals, our understanding of the regional-scale conservation and fishery impacts of current and future MPAs is surprisingly limited. We have evidence that well enforced and appropriately sized MPAs can provide conservation benefits within their borders [@lester2009;@halpern2003; @edgar2014; @gerber2005]. As these conservation benefits accrue inside MPAs, the MPA(s) can affect the waters beyond their borders through the spillover of adult and larval fish from the protected to the fished areas as well as through displacement of fishing effort. Several studies have documented empirical evidence for the existence of adult or larval spillover affecting both abundance and fisheries [e.g. @goni2010; @halpern2009;@kay2012; @stobart2009; @mcclanahan2000; @russ1996; @thompson2017]. The more complex and potentially important question however is not whether spillover occurs (it must to some degree in any realistic scenario), but what the net effects of spillover are and whether these effects are detectable. From a fishery perspective, are spillover benefits sufficient to offset losses in fishing grounds caused by an MPA? From a conservation perspective, does the buildup of adults inside an MPA increase abundance outside through spillover, or does concentration of fishing outside the reserve result in a net loss in regional abundance?

As stakeholders around the world increasingly seek to use MPAs in marine resource management portfolios and the performance of existing MPAs is evaluated, it is critically important that we develop a better understanding of the magnitude and drivers of regional-scale MPA effects. To address this gap, this study examines two critical questions: 1) What do we expect the regional-scale conservation and fishery effects of MPAs to be and 2) When (and how) can we expect to detect these effects? We address these questions using a simulation analysis to frame the theoretical regional conservation and fishery impacts of MPAs, from which we then develop an empirical assessment of the evidence for regional-level conservation effects of MPAs resulting from a network of closures put in place in the Channel Islands, California, USA, in 2003. 

What Are the Regional Effects of MPAs? {.unnumbered}
----------------------

**key thing: a lot more ways for small things to happen than big things **
  
<!-- xx need to add in discussion of other outcomes not covered here, e.g. resiliency, tourism, etc. xx -->

Much of the literature on the effects of Marine Protected Areas focuses on assessing the conservation effects within the borders of protected areas [e.g. @edgar2014]. While these effects are extremely important, they do not paint a complete picture of the effects of MPAs; the organisms within the borders of protected areas are generally part of a broader population, the biological stock, connected through adult movement and larval dispersal. If the goal of conservationists or natural resource managers is to increase the total abundance or productivity of a resource, a broader question we should ask of MPAs is not just are there more fish inside the borders of a reserve, but how do MPAs affect the broader region in which they sit? 

We define the regional conservation effects of MPAs as the change in total biomass of fish (summing inside and outside of MPAs) relative to the total biomass of fish that would have occurred without the MPAs (acknowledging that other outcomes such as increased biodiversity or resiliency are also important to conservation but are beyond the scope of this analysis). We assess the fishery effects of MPAs as the total fishery catches with the MPAs relative to the fishery catches that would have occurred without the MPAs. Note that this definition of regional effects is in line with the recommendations of @ferraro2018, and differs from effects measured by for example differences in outcomes before and after MPAs. 

We used a simulation model to examine the regional conservation effects of MPAs under a wide array of conditions that might reasonably be expected to affect these outcomes. The model explores combinations of MPA design (e.g. sizes, number, and placement of MPAs), life history (e.g. growth and mortality rates, adult movement, larval dispersal, and timing of density dependence), and fishing fleet dynamics (e.g. degree of fishing pressure, size selectivity of the fleet, reaction of fishing pressure to MPA placement) (See Supplementary Table.XX for a complete description of simulation variables). Numerous works have used simulation modeling to explore the effects of MPAs on different outcomes such as fisheries yields and stock abundance [see @fulton2014 and references within],  but these prior studies have either focused on the effect of a select set of drivers (such as dispersal rates) on outcomes, or have been highly localized assessments that incorporate multiple drivers but are tuned to one specific region. Our model captures critical biological features (such as the timing of density dependence), while still being flexible and fast enough to be generalized to a broad array of scenarios. We use this model to explore how different drivers interact to affect the conservation and fishery outcomes of MPAs. 

### Theoretical Conservation Effects {#conservation .unnumbered}

If we imagine a region that has driven its fish populations to near extinction that then places 100% of its waters inside a no-take MPA, we would expect the regional-scale conservation effects to be massive. On the other hand, if we implement an MPA for a lightly fished sedentary species it is possible to create a net conservation loss if the concentration of fishing pressure outside the reserve has a greater effect than the biomass buildup inside the reserve. Within these broad bounds, numerous factors can act to affect the regional effects of MPAs. These include the scale of adult and larval dispersal relative to the size of the MPAs [@gaines2003; @botsford2008; @difranco2018], the strength and timing of density dependence in the population (e.g. pre- or post-settlement), how overfished the population would be without the MPA, and how fishing activity responds to the implementation of the MPAs [@hilborn2004; @hilborn1992; @walters2004; @hastings2003;@gerber2003; @gerber2005; @hilborn2004a; @gaines2010; @botsford2003]. In addition, even for the same total area of MPAs, the location and spacing of the MPAs can have a profound influence on their cumulative impact through habitat and network effects [@gaines2010; @costello2010]. Theory and modeling exercises indicate that the expected regional conservation effects of MPAs can vary widely and are extremely context-dependent [@fulton2015]. 




We tested the effects of different combinations of these theoretical drivers of MPA conservation effects using 20,000 simulated MPA scenarios. Across all simulations the median simulated equilibrium regional conservation effect, expressed as the percentage change in total biomass with the MPAs and without the MPAs, was 15%, with a min of -82% and a max of over 100%. The median time required for the simulated MPAs to cause a 10% increase in biomass was approximately 10 years. 

A striking outcome of this simulation analysis is the wide range of conservation outcomes that can occur depending on the dynamics of the system. When  "small" MPAs (smaller than 25% of the population range of the species) were implemented in relatively unexploited fisheries (fished population above 50% of unfished biomass), the median regional conservation effect was 1%. For moderate without-MPA depletion (50% to 75%), MPA sizes from 1% to 50% of the population range produced median conservation effects of 25%, while for depletion above 75% the median regional conservation effect from was 57% (Fig.\ref{conservation-effects}-A). 

These simple results support the intuitive conclusion that bigger MPAs on overfished populations produce large outcomes, and *vice versa*. However, when combined with other factors such as fleet dynamics and life history, the conservation effects of MPAs can vary widely, a finding corroborated by empirical evidence from @starr2015 and @caselle2015 (Fig.\ref{conservation-effects}-B). Small MPAs can produce small positive effects, large positive effects, or even negative effects. As the area protected inside MPAs increases, positive effects become more likely, but even massive MPAs can produce conservation effects as low as 0% and as high as 200% and above depending on the context in which they are placed. The degree of without-MPA depletion (i.e. fishing pressure) has a clearer signal, with small conservation benefits of MPAs when fishing is light, and larger effects when MPAs are large, but again even for severely overfished populations the conservation effects of MPAs can vary widely. 

While positive conservation outcomes were much more likely to occur across our simulations (95% of the time), the 5% of runs that produced net conservation losses are of particular interest. These runs occurred almost exclusively when the simulate fleet followed a "constant catch" fishing strategy. Under the constant catch fleet model, fishing communities seek to catch the same amount regardless of the presence of an MPA. While a constant catch greater than MSY is not possible over the long-term under the assumptions of this simulation framework, over the short-term a constant-catch scenario is not implausible. Subsistence fisheries may use a constant-catch style policy over the short-term, as they seek to ensure that their food needs are met. More industrial fisheries may have pre-arranged agreements with buyers to deliver set amounts of fish. Constant-catch dynamics might also occur in fisheries with constraining quotas that are not updated after the implementation of MPAs.





\begin{figure*}%[tbhp]
  \centering
  \includegraphics[width=.9\linewidth]{figs/conservation-effect.pdf}
  \caption{Median (A) and range (B) regional MPA conservation effect (expressed as percent of unfished biomass) after 15 years of protection across a range of without-MPA depletion and MPA sizes}
  \label{conservation-effects}
\end{figure*}

### Theoretical Fishery Effects {#fisheries .unnumbered}

Intuition and theory tell us that MPAs can have similarly diverse effects on fisheries outcomes as they did for conservation. If 100% of fishable area is placed inside an MPA then clearly the MPA can have no fishery benefits. The effects of smaller MPAs will depend on whether the spillover from MPAs is sufficient to offset losses in fishing grounds, and on the response of fishing fleets to the MPAs [see @hilborn2004 for general summary of possible fishery effects of MPAs]. 

We used our simulation model to explore the effects of MPAs on fisheries. We express the fishery effects as a percentage of maximum sustainable yield (the maximum average catch that can taken from the fishery, MSY) gained or lost in the scenario with MPAs relative to the world without MPAs. MPAs produced gains in fishery catches in 20% of simulations (meaning MPAs produced reductions in fishery catches in 80% of simulations). The median MPA effect for MPAs covering less than 25% of the target species' range was negligible. MPAs covering 50% or more of the range generally produced reductions of catches of 25% of MSY or greater, though large MPAs were able to provide fishery benefits of 25% or higher when the target fishery was severely depleted in the absence of MPAs (Fig. \ref{catch-msy-effects}A). In fact, under the assumptions of our model MPAs were only able to produce fishery benefits when without-MPA depletion was greater than roughly 60%, though even then while positive outcomes were more frequent negative ones were still possible (Fig. \ref{catch-msy-effects}B). The simulated fishery effects of MPAs, similar to the conservation outcomes, are highly variable and context dependent. 




\begin{figure*}%[tbhp]
  \includegraphics[width=0.9\linewidth]{figs/fishery-effect.pdf}
  \caption{Median (A) and range (B) MPA fishery effects, expressed as the difference in catch with and without MPAs  as a proportion of MSY, after 15 years of protection across a range of without-MPA depletion and MPA sizes}
  \label{catch-msy-effects}
\end{figure*}


## How Can We Detect Regional Effects?

Basic bioeconomic theory tells us then that we should expect the regional conservation and fishery effects of MPAs to be highly context dependent. Given that their effects are not so obvious as to negate the need for program evaluation, how then can we go about measuring what the true effects of MPAs are? In a perfect setting, MPAs would be randomly assigned, and the conservation and fishery outcomes in places with and without treatment would be compared. This is clearly not how MPAs are in fact placed. What is required then is some means of controlling for biases introduced by factors such as the MPA siting process and biological and economic spillover [see @ferraro2018 and @larsen2019 for a thorough discussion of these problems]. 

From the fisheries perspective, catch rates before and after [e.g. @roberts2001a] or near and far from MPAs [e.g. @russ2004a] are often presented as evidence for the fisheries effects of MPAs. However neither of these approaches can be counted on to provide reliable estimate of the net fishery effects of MPAs, due to failures to account for potential broader trends in catch rates independent of MPAs and the potentially confounding effects of effort redistribution. @smiith2006a presents an econometrically robust method for estimating the fishery effects of MPAs, though this approach requires highly fine-resolution data on comparable fishing effort both near and far from MPAs. It is beyond the scope of this paper to dive deeper into detecting the net fishery effects of MPAs, and so we now focus on the question of estimating their regional conservation effects. 

Conservation effects are often estimated by comparing densities inside MPAs to densities in selected control sites outside MPAs, which we will refer to as density ratios. @lester2009 and @halpern2002 present meta-analyses of hundreds of such studies. These results often find massively higher densities inside MPAs than outside [@lester2009], which are often equated to mean that the MPA has had a substantial positive effect on fish populations. How reliable are density ratios as an estimator of regional conservation effects though?

Control sites are often selected with regards to ecological traits such as habitat characteristics [@ferraro2018]. However, selection of control sites is further complicated by the very spillover that MPAs are often intended to create. Export of adult or larvae from the MPA to the "control" site dilutes their status as controls, as does concentration of fishing effort from MPAs to control sites. In theory, control sites far enough away enough to negate both biological and economic spillover could be selected, but finding suitably far sites that are also appropriate proxies for the ecological and economic context of the MPAs is challenging. While these concerns have been stated in various forms in the past [e.g. @halpern2004], the MPA evaluation literature has by and large been unable to address them adequately [@ferraro2018]. 

Failure to account for these spillover effects can result in a biased estimate of the true effect of a policy such as MPA placement [@larsen2019]. A reasonable question then is how biased is the density ratio as an estimator of regional conservation effects? In an ideal world, the control sites used in a density ratio are perfect proxies for what would have occurred without the MPA. We used our simulation model to approximate this scenario, calculating the density ratio as the ratio of densities inside the MPAs relative to the overall density from the paired simulation without MPAs (Fig.\ref{density-ratio}-A). In this idealized case, the density ratio is often a reasonable estimator for the regional conservation effect, especially for more mobile species. However, even under this ideal example the density ratio becomes increasingly positively biased the lower movement rates are, due to the fact that this ratio contains no information on what is happening outside the MPAs in the scenario with MPAs. 

What happens when the "control" sites are in fact affected by the application of the MPA through biological and economic spillover? To evaluate a more realistic density ratio, we calculated the density ratio as the mean density inside MPAs relative to the mean density outside the MPAs (both weighted by distance from MPA borders). We only include simulations in which habitat and larval dispersal rates are identical inside and outside of MPAs, to approximate a scenario in which treatment and control sites have been paired by ecological characteristics. Under these circumstances the density ratio is a somewhat biased and very inaccurate estimator of the true regional effect of MPAs. While on average high density ratios in this scenario correspond with high true regional effects, for any one simulation the relationship is extremely weak. For higher movement rates, density ratios were frequently near 0% (potentially leading stakeholders to conclude that the MPA had been ineffective), when in fact in many cases the true effect of the MPA was highly positive. For highly sedentary species extremely high density ratios could create the appearance of massive conservation gains when in fact the net effect on the regional population has been near zero or even negative (Fig.\ref{density-ratio}-B). 

We note that spatial before-after-control-impact (BACI) studies present a potential improvement over density ratios, but are much rarer due to the need of extensive pre-MPA monitoring. We did however find spatial BACI to have similar flaws to density ratios in the face of biological and economic spillover though, see SM.  

To the extent then that control sites that are both sufficiently similar to the region treated with MPAs and are unaffected by biological or economic spillover can be selected, density ratios may be reliable estimators of regional conservation effects. In reality these conditions are unlikely to hold but for a few select cases. In the case of the Channel Islands for example, control sites are located on average XXkm from MPA borders, making biological and economic connectivity of some degree a certainty. In these circumstances without robust statistical controls density ratios may provide a severely inaccurate estimate of the true regional conservation effect of marine protected areas. 




\begin{figure*}%[tbhp]
  \centering
  \includegraphics[width=.9\linewidth]{figs/density-ratio.pdf}
  \caption{Simulated density ratios (x-axis) plotted against true regional change in biomass caused by MPAs (y-axis). Each point represents a simulation, and color represents the movement rate of fish in the simulation. Black line shoes the one:one line, blue line is a linear fit of the relationship between density ratios and true regional change in biomass}
  \label{density-ratio}
\end{figure*}





What then is a viable alternative? We propose a solution, building off of @caselle2015; a difference-in-difference estimator comparing densities in species targeted by fishing effort (e.g. kelp bass, *Paralabrax clathratus*) from those not targeted (e.g. Garibaldi, *Hypsypops rubicundus*) before and after MPA implementation [see @larsen2019 for a succinct explanation of difference-in-difference estimators in ecological settings]. The key assumptions of this approach are that a) within the time-frame of the model there are no significant interaction effects between the targeted and non-targeted species (which in fact we do not detect, see SM), and that in the absence of the MPAs both the targeted and non-targeted groups of species would have exhibited similar trends in densities (the parallel-trends assumption). The advantage to this approach is that given the time-frame of the model (15 years), we believe that spillover effects of MPA placement on the non-targeted species are likely to be much less severe than the effects of spatial biological and economic spillover that bias the performance of estimators such as a density ratio or a spatial BACI design. 


<!-- Our strategy for identifying the effect of the MPAs in the Channel Islands is to use biomass densities of non-targeted species as our control for broader factors affecting biomass densities of fishes throughout the Islands besides the effect of the MPAs. Simply examining densities of tarted species throughout the islands before and after MPAs might confuse changes in regional densities that would have occurred anyway without the MPAs with MPA effects (since at the regional scale we do not have a spatial control for the effects of the MPAs). We assume that over the 13 years of MPA protection covered in this study non-targeted species were relatively unaffected by the MPAs (i.e. indirect effects of MPAs on species interactions are negligible), and can can serve as an indicator for the overall changes in fish abundance throughout the Channel Islands that would have occurred without the MPAs. Raw densities calculated by PISCO provide visual support for this hypothesis, in that both the targeted and non-targeted species groups share common trends (Fig.\ref{pop-trends}, see Materials and Methods for statistical support for this assumption). -->


## MPA Effects in the Channel Islands {#estimating .unnumbered}




\begin{figure}%[tbhp]
\centering
\includegraphics[width=1\linewidth]{figs/channel-islands.pdf}
\caption{Map of PISCO sampling locations within the the Channel Islands National Marine Sanctuary. Grey boxes indicated MPA, points sampling locations, with color representing the number of individual observations at that site}
\label{channel-islands}
\end{figure}





We applied this proposed difference-in-difference strategy using empirical kelp forest survey data from the Partnership for Interdisciplinary Studies of Coastal Oceans ([PISCO](http://www.piscoweb.org/)) monitoring of the Channel Islands National Marine Sanctuary to test our ability to detect the regional effect of MPAs in a real world context. A network of MPAs covering approximately 20% of the islands' waters was put in place in 2003. What sorts of regional MPA conservation effects does our simulation model suggest we might see in the Channel Islands after 13 years of protection (the time span covered by our model)? The median regional conservation effect produced by our simulation model after 13 years of protection by MPAs covering between 15%-20% of a population's range was 6%, with an interquartile range of 2% and 13%, though values as high as a 200% increase and as low as a 50% decrease were also produced. Our expectation then is that all else being equal we are likely looking for a modest but positive effect size. 

PISCO conducts visual SCUBA surveys at a large number of rocky-reef and kelp forest sites inside and outside of MPAs throughout the Channel Islands, producing estimates of densities of fishes that are both targeted and non-targeted by fishing (Fig.\ref{channel-islands}). 




\begin{figure}%[tbhp]
\centering
\includegraphics[width=1\linewidth]{figs/pop-trends.pdf}
\caption{Centered and scaled mean annual density of included species (faded lines) and smoothed means of targeted and non-targeted groups, and mean (darker lines) and confidence interval of the mean (ribbon) over time.}
\label{pop-trends}
\end{figure}

The raw trends shown in Fig.\ref{pop-trends} though could be caused by any number of confounding variables, from changes in observer skill to shifts in environmental conditions. We use a difference-in-difference style regression to account for some of these factors and estimate the difference in the biomass densities of targeted and non-targeted fishes in the Channel Islands post-MPA implementation. We find no significant difference in the densities of targeted and non-targeted fishes pre-MPA (before 2003), which provides support for the parallel trends assumption critical to the difference-in-difference method (though it cannot prove this). Following the implementation of the MPAs in 2003, we see evidence of an increasing trend in densities of targeted fishes relative to non-targeted, reaching a peak value in 2014. Following 2014 though, densities of targeted species appear to have declined relative to what we would expect based on the non-targeted group (Fig.\ref{did-plot}).





\begin{figure}%[tbhp]
\centering
\includegraphics[width=1\linewidth]{figs/did_plot.pdf}
\caption{Estimated divergence in biomass densities of targeted and non-targeted fishes throughout the Channel Islands (i.e. integrated across inside and outside of MPAs). MPAs are implemented in 2003 (red dashed line). Estimates are from a regression on log(abundance index), so estimated effects roughly correspond to percentage changes.}
\label{did-plot}
\end{figure}

Discussion {#discussion .unnumbered}
------


MPA science stands at a crossroad. As the number and size of global MPA networks increase, it is critical that we plan how we will monitor the success of these protected areas at achieving our objectives. While the history of MPA science has made important strides in helping us understand the dynamics of protected areas, the future must directly tackle the challenge of causal inference. Typically employed metrics such as density ratios may be applicable in some circumstances, but have severe shortcomings as metrics of regional conservation effects. Bioeconomic modeling can help frame community expectations, reducing the potential for a reduction in support if lofty conservation or fishery gains are not realized. Dependence on biased estimators of MPA effects may lead to incorrectly attributing negative environmental shocks as MPA failures, or interpreting data arising from scorched earth fishing outside MPAs as a conservation success. 

Failure to set expectations ca

As @larsen2019 demonstrates, there are potential alternatives to estimating the regional effects of MPAs that better account for the challenges of causal inference. We applied one such approach here (a difference-in-difference estimator), and yet were still unable to reach robust conclusions as to the effect of MPAs on the density of targeted species in the Channel Islands, due to the likely small size of the true effect relative to environmental drivers. **What then can we do?**

Re-frame objectives. Better incorporation of MPA monitoring data into stock assessment models

Studies such as @dinerstein2019 call for 30% of the oceans to be places in protected areas. What does simulation exercise suggest that the effects of such a closure might be on overall population biomass densities? XX. Suppose we assumed that all fisheries are both open-access and overfished (a clearly worst case scenario as many fisheries are well managed). In that case, we see that...

<!-- zeros may be an artifact of "error in variables", which can bias estimates towards zero [@larsen2019] -->


MPAs are an important part of the marine resource management toolbox. Under ideal circumstances they can protect both individual species and ecosystem linkages, safeguard critical habitat, and support local economies through tourism and fishing opportunities. However, our results show that the regional conservation and fishery benefits we should expect from MPAs are highly variable, and while we cannot assign probabilities to our simulated states of nature, given plausible states of nature most simulations produced small conservation effects (0-15% increases in biomass relative to what would have occurred without MPAs) and negative fishery effects (reduction in catches relative to what would have occurred without the MPAs) after fifteen years of protection. 

Our simulation results present a clear outcome from the perspective of fishery effects: MPAs should not be expected to provide improvements in fisheries catches unless the stock is experiencing substantial overfishing (Fig.\ref{catch-msy-effects}-B). This general result has been discussed before [@hilborn2004], but our results provide the most comprehensive simulation testing of this concept to date.  MPAs placed in overfished fisheries frequently produced fishery catch gains of 0-25% of MSY, though larger and smaller effects were still possible. MPA size also presents an interesting tradeoff from a fisheries perspective. "Small" MPAs (less than 25% of the population range) very rarely produced substantial fishery losses, but also never produced meaningful fishery gains. Medium sized MPAs (25%-50%) produced the potential for higher fishery gains, but also opened up risk of greater fishery looses. For MPAs covering more than 50%, fishery losses quickly become much more likely than fishery gains. 

We only measure one aspect of fishery outcomes here (catches). MPAs can affect many other outcomes of importance to fisheries, include profits (e.g. if MPAs improve catch per unit effort along the borders of reserves, potentially reducing costs of fishing to those), resiliency, and research. Our model does not account for potentially important factors such as inter-species effects. Our results though suggest a relatively simple rule of thumb: unless there is clear evidence of overfishing MPAs should not be expected to produce improvements in fishery catches without clear explanation for the mechanism for these increases (e.g. improvements in habitat). In assessing the potential fishery benefits of MPAs, stakeholders must make explicit the mechanisms by which these benefits are expected to be produced (for example through improved catch rates), and what evidence exists for the existence of those mechanisms within the local context.

MPAs produced regional conservation gains in 95% of simulations, though in most cases conservation gains were in the range of 0-15% increases in biomass (Fig.\ref{conservation-effects}) (XX Per Owen's thoughts, does anyone know of some references we could include here for prior thoughts on what this effect size might be?). Of particular note, MPAs covering less than 25% of the range were unlikely to produce substantial fishery harm, but also unlikely to produce regional conservation gains above 10% unless the stock was severely overfished without the MPA. Large MPAs protecting highly depleted stocks almost always produced large regional conservation gains. This result stands on sharp contrast to the large within-MPA effects on biomass densities reported by @halpern2003a and @lester2009. This different is due in part to to the fact that within-MPA effects are likely to be much larger than regional-MPA effects, but may also reflect a tendency to place MPAs in situations most likely to produce larger conservation benefits (e.g. in heavily overfished locations). 

<!-- While our results provide important insight on the expected fishery and conservation effects of MPAs, they also highlight the critical importance of explicitly modeling the links between the biological effects of MPAs and the ways that humans respond to them. One of our clearest findings was that MPAs can cause net conservation losses when implemented in a "constant catch" fishery, as fishers must dramatically increase their fishing effort in the waters still available to them to maintain their desired landings. The focus of much of the MPA design and modeling literature has historically been on biological and ecological such as growth rates and connectivity [citation], though studies such as @hastings1999 and @sanchirico2006b incorporate assumptions about outside-MPA fleet dynamics as well. Our results make clear that economic and ecological drivers must be included in any attempt assess the effects of MPAs MPAs: in particular, we need to explicitly understand the the behavior of fishing fleets if we hope to estimate the conservation or fishery effects of MPAs [see @costa2013 for an example of this process]. Large-scale empirical evidence confirms that predicting the effects of MPAs depends on understanding the human context in which they find themselves [@cinner2018].  -->

<!-- The question of what is a "meaningful" conservation gain is of course context dependent and depends on the priorities and preferences of stakeholders. However, under any set of preferences and objectives managers and stakeholders would of course like to know whether policy interventions such as MPAs are having their intended effects. While the importance of say a 0-10% regional conservation gain will vary, there can be little doubt that an effect size within this range will be very difficult to detect in a noisy natural system (xx citations on noise and effect size xx), and our empirical assessment of MPA conservation effects in the Channel Islands demonstrates this.  -->

<!-- . That we were unable to detect a significant divergence in the biomass densities of targeted species throughout the Channel Islands post MPA implementation, relative to the densities that the trends of the non-targeted species would suggest we should observe, should not come as a great surprise then.  -->

Our simulation model helped to bound expectations for our empirical assessment of MPA effects in the Channel Islands. The Channel Islands MPAs cover approximately 20% of the waters in the Channel Islands, and while formal stock assessments are not available for many of the targeted species in our analysis what evidence we have does not suggest that as a group they are heavily overfished. Our simulation analysis would suggest then that the percentage difference in densities of targeted species with and without MPAs should be on the smaller end (likely 30% or less), and therefore be challenging to detect given the large natural variation of marine ecosystems (especially temperate reefs) and the error inherent in visual survey programs such as those provided by PISCO.

While the "MPA effect" estimated by our model was not significant in any one year, the positive trend from 2005 to 2014 is evident, as is the sharp decline from 2015-2017. To what should we attribute this apparent shift? We cannot reject the parallel trends assumption between the targeted and non-targeted species in the years before the MPAs  (Fig.\ref{did-plot}). Our hypothesis might be then that the non-targeted species can serve as effective control for environmental drivers not included in the model. However, the Channel Islands region (and the entire West coast of the USA) experienced a dramatic 'marine heatwave' beginning in 2014 and persisting through 2016, resulting in part in extremely elevated water temperatures throughout the region [@gentemann2017]. Many of the non-targeted species have warm thermal affinities, and have increased in numbers since the heatwave (Freedman et al in prep XX). However, the targeted group is made up mostly of fishes with cold-water affinities, such as members of the genus *Sebastes*. As such, we hypothesize that the recent decline in densities of targeted species is due to environmental conditions that disproportionately affect the targeted group (and not for example due to concentrated fishing pressure outside the reserves). The Channel Islands case study demonstrates both the challenge of detecting small effect sizes in nature, and highlights the potential for small effect sizes to be overwhelmed by additional shocks to the system. 

Our simulation model accounts for many factors that theory suggest should be critical drivers of MPA effects, namely adult and larval movement rates, nature of density dependence, and fleet dynamics. However, currently our model does not contain many other potentially important factors, such as species interactions. If stakeholders expect an effect that our model says is unlikely or impossible given local context, they should provide a clear hypothesis and evidence as to what factors not included in this model would cause their expected effect. For example, stakeholders might assert that larger conservation effects than predicted by our simulation model might occur in a location due to protection of critical spawning aggregation sites [@roberts2002;@erisman2015], but relevant evidence supporting this belief must be presented. It is also important to remember that our conservation results refer to the regional effects of MPAs both inside and outside of their borders. The buildup of biomass within the border of well enforced reserves is well documented [@lester2009], we show though that the regional effects may be much smaller and harder to detect than these within-MPA outcomes. 

Our results provide a unique survey of the likely regional effects of MPAs to fisheries and conservation, and places our empirical assessment of the regional effects of the Channel Islands MPAs in context. The Channel Islands are an intensely studied system, and the challenge of identifying a clear regional effect of the network of MPAs placed there in 2003 may seem surprising. However, our results show that in fact a smaller effect size, from the perspective of regional conservation gains, is to be expected in this system, and therefore the true effect will be very challenging to separate from environmental noise. 

Modeling effort such as this can then help manager and stakeholders to set realistic expectations of regional effects for any given MPA network design, and importantly, help inform the design of monitoring programs. For example, monitoring may want to be targeted at the species and fleets that modeling suggests may provide the clearest indication of MPA-mediated effects. For cases where bio-economic modeling suggests small potential for MPA driven regional density effects, monitoring efforts can be targeted around detecting potential negative effects should they arise, i.e. evidence that the model is wrong, rather than exerting massive amounts of effort on what theory and modeling suggest may be a small and potentially undetectable effect size.

Policy making is inherently an exercise in utilizing best available theory, experience, and modeling to make decisions that are often extremely difficult to empirically test. Causal inference in coupled human and natural systems is incredibly challenging [@ferraro2018], and our results highlight the particular difficulties in estimating the causal effects of MPAs on regional conservation and fishery outcomes. Bio-economic simulation models such as ours can support the policy evaluation process by helping stakeholders and communities set realistic expectations for what MPAs might achieve, help managers understand the scale and magnitude of MPA effects, and help scientists design cost-effective monitoring plans that stand the best chance possible of detecting these effects. This process is a critical step in ensuring that MPAs can be effective tools for fisheries management and marine conservation.

<!-- Despite our best efforts we are unlikely to ever truly "know" the effect of our efforts to mitigate climate change, but must instead rely on comparisons to best available modeling outcomes to understand how effective our policies have been. Similarly, given the complexities of marine systems much of our decisions on MPA design will have to be based on effective modeling. While we are hardly the first to point out that bio-economic models are a critical tool for MPA design, our results help indicate a minimum floor of model complexity to provide candid assessments of regional MPA effects.  -->

<!-- While factors such as MPA size and degree of depletion are especially strong drivers, for all but the most extreme cases of each a wide array of effects, from negative to highly positive,  are possible based on the complex interaction of factors such as fleet dynamics, movement rates, and recruitment timing. Confronting these interactions by considering the likely parameter space for a given region is a critical step then in understanding what likely regional effects of MPAs are. While models such as ours do require large numbers of parameters that may be challenging to obtain, our results show that working with communities to confront these uncertainties is preferable to sweeping them under the rug in favor of simpler models that are easier to parameter but miss details that our results show can have dramatic effect on expected outcomes.  -->


<!-- We focus mostly on regional conservation gains in this paper. However, fisheries spillover is often another important factor to consider (i.e. are fisheries better off with the MPAs than they would have been without them). The fishery benefits of MPAs are just as (and likely more) intensely debated than the regional conservation outcomes [@hilborn2004; @roberts2001;@sala2018b;@hilborn2018]. We only address fisheries affects briefly in this study, but our results highlight important tradeoffs and synergies between conservation and fishery spillover effects of MPAs. The good news from a fisheries perspective is also fairly obvious: Both the regional conservation and fishery benefits are expected to be greatest when the fished population is in an extremely depleted state pre-MPA, even over a 15 year time horizon, even for larger MPAs (though further work is needed to compare MPAs to alternative fisheries management strategies in these cases). For cases where a valuable and formerly abundant species is overfished, a large MPA may then provide large conservation and fishery gains for that species, while potentially having smaller impacts on other less depleted species. Our simulation results also do identify though a large parameter space where MPAs create tradeoffs between moderate conservation gains and moderate fishing losses. This type of projection analysis can help managers consider where in this space they may be. The most critical point with regards to conservation and fishery effects from our simulation analysis is that the conservation or fishery effects of MPAs cannot be reliably estimated without some knowledge and consideration of the dynamics of the fishing fleet outside the MPAs: over the short-term open access vs constant catch dynamics can make the difference between a substantial conservation and fisheries win to a more depleted stock with more expensive fishing.  -->

<!-- This process provides a unique survey of the likely regional effects of MPAs to fisheries and conservation, and places our empirical assessment of the regional effects of the Channel Islands MPAs in context. The Channel Islands are an intensely studied system, and the challenge of identifying a clear regional effect of the network of MPAs placed there in 2003 may seem surprising. However, our results show that in fact a smaller effect size, from the perspective of regional conservation gains, is to be expected in this system, and therefore the true effect will be very challenging to separate from environmental noise. The solution then though is not to give up on detecting effects, but rather to shift focus from identifying a specific effect size and instead use simulation analysis to appropriately set expectations for conservation and fishing stakeholders, and design monitoring programs around the species and situations that serve as effective indicators of the ability of an MPA network to achieve its objectives.  -->


## Materials and Methods

We present here critical characteristics of our simulation model and regression approach. Further supporting material can be found in the [Supplementary Information](https://danovando.github.io/dissertation/2-zissou.html).

### Simulation Model

Our bio-economic simulation model follows the general structure outlined in @ovando2016. Readers can explore the functionality of the model using an online tool available [here](https://danovando.shinyapps.io/sraplus/). The model consists of 100 patches with wrapped edges (picture the waters around a circular island). For any one simulation we randomly pull a species and its associated life history (growth, mortality, maturity) from the `FishLife` [@thorson2017c] package in R [@rcoreteam2018]. We pair these data with randomly selected values between 0.6 and 0.9 for Beverton-Holt steepness [as parameterized in @mace1994], as well as larval and adult dispersal rates (where at the lowest values adults and larvae stay within the patch they were created, and at the highest have equal chance to move to any patch in the system). The simulated species is also randomly assigned whether adults have density dependent movement (meaning that adult biomass preferentially moves towards patches with lower adult biomass as opposed to random dispersal), as well as one of five potential types of density dependence [as specified in @babcock2011, allowing for example density dependence to happen pre or post larval settlement]. 

Along with the species, the simulation is assigned a random set of fleet dynamics from one of three categories: constant catch, constant harvest rate, or open-access. Under constant catch, the fleet attempts to catch a randomly selected multiplier of maximum sustainable yield (MSY) each year (note that values of MSY greater than 1 will crash the population eventually, but allows for overfishing dynamics to be observed over the short term periods used in this model). Under constant harvest rate the fleet captures a randomly selected fraction between 0.01\% and 99\% of the population in each time step. Under open access, fishing effort is allowed to expand and contract in response to the profitability of the fishery, where

\begin{equation}
  E_{t} = E_{t-1}\times\theta{Profits_{t-1}}
  \label{eqn:oa}
\end{equation}

and 

\begin{equation}
  Profits_{t} = pCatch - cE_{t}^\beta
  \label{eqn:profits}
\end{equation}

To shift the equilibrium of the open access model, we fix price *p* at 1 and $\beta$ at 2, and adjust the cost parameter to achieve a randomly selected open-access equilibrium population between 0\% and 100\% of carrying capacity (in the absence of the the MPA). These combinations of fleet models allow us each simulation to achieve randomly selected levels of fishing pressure through different processes. While at equilibrium in the absence of an MPA each of these fleet models can achieve the same level of depletion, each of these fleet models interacts with MPAs in a different manner. Along with the fleet dynamics model, each simulation is assigned a random fleet dispersal scenario: uniform dispersal (where the total effort of the fleet is divided evenly among all open patches), catch dispersal (where the total effort of the fleet is divided according to the catchable biomass in each available patch), and profit dispersal (where the total effort of the fleet is divided according to the available profits in each available patch). 

Lastly each simulation is assigned an MPA scenario, defined by the number and size of MPAs, the placement of those MPAs, and the year that the MPAs are put in place. Many MPA models assume equilibrium conditions prior to the MPA, and then measure equilibrium outcomes. While these are important scenarios to understand, they do not reflect the reality of many MPAs, which are often placed in non-equilibrium conditions, and evaluated over the first few years of their existence. Each simulation starts the population off at unfished equilibrium and then beings to apply the fleet model. The MPAs are then placed during the randomly selected start year, allowing some runs to explore how the early dynamics of the MPA play out when the fishery and population they are placed on is not already at equilibrium. 

Each simulation is run to equilibrium with and without the selected MPA strategy (holding all else constant). We then measure the difference in biomass and fishery catches in each time step in the scenario with and without the MPAs to calculate the conservation and fishery effects of the MPAs over time. 

### Difference in Difference Regression

We use a difference in difference regression style regression to estimate the difference between the biomass densities of targeted and non-targeted species in the Channel Islands. The simplified form of this model is 

\begin{equation}
  d_{i} = \beta_0 + \beta_1T_{i} +  \beta_2MPA_{i} + \beta_{3}T_iMPA_i + e_{i}
\label{eq:did}
\end{equation}

where $d_i$ is the biomass density at observation *i*, *T* indicates whether the observation *i* is for a targeted ($T = 1$) or non-targeted ($T = 0$) species, and *MPA* marks whether observation *i* is in a pre MPA ($MPA = 0$) or post MPA ($MPA = 1$) state. Under the assumptions of this model, $\beta_3$ is the causal effect of the treatment (*MPA*) on the treated (targeted species). 

The purpose of this regression approach is to control for unobserved variables that are correlated with the treatment (MPA) and affect the outcome  (biomass densities). For example, if densities would have declined in the absence of the MPA, simply measuring densities of fish before and after MPA would give a biased estimate of the MPA effect. This approach controls for scenarios such as this through the critical assumption that the the untreated group (in this case non-targeted species) serve as a proxy for the trend in post-treatment densities in the absence of the MPAs (where the intercept terms for the targeted group allows for different mean densities). 

We will briefly assess two of the most critical assumptions of this model: that the treated and non-treated groups have parallel trends, and that the effect of the treatment on the treated does not tangentially affect the untreated (i.e. that the MPAs do not indirectly affect the non-targeted group). While the parallel trends assumption cannot be proven, we can examine its validity using the data from the years before the MPAs were put in place in 2003 (since after that we no longer expect the trends in the observed data to be parallel). We do not detect any significant differences in the trends of the biomass densities of the targeted and non-targeted species in the years before the MPAs, meaning that we do not have evidence to reject the assumption that densities of targeted and non-targeted species were following similar trajectories before the MPAs. 

With regards to the second assumption, we can safely assume that it is violated on some level. All of the species in this empirical analysis exist within an ecosystem, and as such affect each other through mechanisms such as predation, competition, and habitat modification. Conceivably then, protection of carnivorous targeted species inside MPAs could drive down of non-targeted prey species, serving in that case to positively bias our estimate of the effect of MPAs on the targeted species. While we know dynamics such as this have to exist on some level, we find it unlikely that these effects have had enough time to manifest in the 13 years of post-MPA data used in our analysis [@babcock2010; @pershing2015a]. 

We used convergent cross mapping (CCM), in the manner of @clark2015, to test for the possibility of the trophic cascades biasing our results. Generalizations of Takens' theorem indicate that if two variables (in our case, species or physical variables) are part of the same dynamic system, their individual dynamics should reflect their relative causal influence. In other words, if one variable is causally forced by another, that forcing should leave a signature on the first time series. Convergent cross mapping (CCM) tests for causation by using the attractor/manifold built from the time series of one variable to predict another (hence the "cross-mapping"). In simple terms, the causal effect of A on B is determined by how well B cross-maps A. CCM then allows us to test for causal relationships in the timeseries of densities of targeted and non-targeted species. Our results found no significant cross-mappings between targeted and non-targeted species, indicating that while clearly there are interactions between these groups on some level, the effects within the timespan of the data are not pronounced enough to be of concern to our results (see [SI](https://danovando.github.io/dissertation/2-zissou.html#introduction-2)). 


While Equation.\ref{eq:did} presents the general form of our model, in practice the estimation model is much more involved. At the rawest level, the data are counts of finfish in 2cm length bins along a 30m x 2m transect at various sites and depths. These length bins are converted to biomass, and then biomass densities, by converting length to weights using available allometric data and dividing by the transect area. Our goal is to estimate the effect of the MPAs on these densities of fish throughout the Channel Islands. We fit this model using a hierarchical mixed-effect framework using Template Model Builder [TMB, @kristensen2016] in R [@rcoreteam2018]. The model consists of three levels, the first (starting from the "bottom") being transect-level densities of fish species observed by PISCO, which are standardized into a unit-less index of biomass abundance (which we will refer to as an abundance index from now now), accounting for both probability of detection and expected density as a result of changes in both abundance and covariates such as observer skill [see @maunder2004]. For the second stage, we break the abundance indices into targeted and non-targeted species (per the classifications in the PISCO data), and estimate the mean trend of each group (targeted and non-targeted) over time. In the third step, we estimate the difference in the mean trend between the targeted and non-targeted fishes, which under the right set of circumstances should reflect the causal effect of the MPAs on the outcome of interest (in this case regional biomass density of targeted fishes). All three of these steps are integrated into the same estimation model, in order to propagate uncertainty through the model correctly.

<!-- \showmatmethods -->
\showacknow

&nbsp;
&nbsp;
&nbsp;
