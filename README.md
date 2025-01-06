java c
CEG8526: Hydrosystems modelling and management
Assignment 2024-2025
Coursework 2
Background
The UK   water supply industry   faces several challenges due   to climate change, including            increased   water scarcity   from   warmer   temperatures, changing rainfall patterns, and more   frequent and severe droughts.   According   to the 3rd   UK Climate Change Risk   Assessment            ‘Future   projections of   more frequent   and   intense dry   periods lead to concerns around the      availability   of   public water   supplies in future, especially   in England   and   parts of   Wales.
Private water   supplies are   also   at   risk.   ’   The UK also   faces an increased demand   for   water,   particularly in the southeast of England,   where demand is already high.
Assignment
Your overall   task is   to assess   the impacts of climate change on flow regime and   water            resources on   the Derwent catchment (National River Flow   Archive ref. no. 28001).   You         should provide a   written summary of   your approach and analysis of   the   future change in   catchment   flow regime under climate   change and   the implications   for   water resources,   providing useful planning information   to   the   water resources sector.
A)      Rainfall simulation
You should construct a synthetic time-series of rainfall data using a stochastic   time-series   model,   with statistical properties consistent   with   the historical rainfall data   for   the
catchment, representing a baseline   for   the climate change assessment.   You should   then         apply appropriate climate change projections   to derive downscaled, perturbed   time series   of projected   future rainfall (we recommend   you assume   the   transition probabilities remainunchanged).   You should use   these simulations   to provide an assessment of changes in   rainfall under climate change and its impacts on   the catchment’s hydrology and   water      resources.
You should select ONE appropriate product   from UKCP18 (e.g.   from   the probabilistic
projections or land projections   from an appropriate resolution model), explaining   your         choice, and   then analyse the projected changes   for   TWO scenarios - RCP8.5 plus one            other scenario.   You should also quantify the uncertainties in each scenario   by exploring
the range of climate change projections   for each e.g. an upper and lower estimate of   change.
B)      Modelling catchment river   flow
You should   then run   your rainfall series (baseline plus   future scenarios)   through   the
calibrated SHETRAN catchment model   for   the Derwent   from   which   you   will derive baseline   and projected   future   flows. Using   the outputs   from   the model   you should discuss   the
change in catchment   flow regime, for example changes   in extreme or low   flows.
C)   Assessment of   water resource
You should   then run   the baseline and projected   future flows through a Pywr   water
resources simulation model   for   the Upper Derwent reservoirs, using   the online platform               WaterStrategy. Building on   your understanding   from the projected changes in rainfall and      flows,   you should   then analyse   the outputs   from   the   water simulation to evaluate changes   in   water resource availability,   for example in minimum and mean simulated reservoir
storage levels.   You should describe and explain   the projected changes, including an   analysis of   the unc代 写CEG8526: Hydrosystems modelling and management Assignment 2024-2025 Coursework 2
代做程序编程语言ertainties.
Your report should explain   your methodology and   justify   the methodological approach. It   should be structured in a logical manner.   Your conclusions should summarise   your
findings in   the context of guidance   to a   water resources planner looking   to quantify climate   risk   to   water supplies, along   with any methodological limitations and uncertainties in   your      approach and how   you might address   these in   further   work.   You should also reflect on
additional   factors   that   you might consider important   to improve modelling in   future   assessments and decision-making.
A summary of   the   workflow   for   this assignment is provided on   the last page   for   your   guidance.
Formatting and indicative marking schedule
Report   format: the report should be a maximum of 4,000   words (excluding   titles/contents,   figure and   table captions,   and references) and use 11pt   font   with normal spacing.Marking   criteria   and   schedule:   this   coursework   comprises   65%   of   the   overall   module   assessment. It will be marked according to the standard SAgE faculty marking criteria (see   information provided on Canvas) taking into account   the   following:
•             presentation and structure of   the report, including clear   figures;
•             ability   to investigate a problem using an appropriate experimental approach.   Credit   will be given   for going beyond   the   taught material, including additional   methodological developments;
•             ability   to understand and apply relevant hydro-informatic models   to derive
appropriate quantitative outputs   to support management of   water resources;
•             understanding of   the basis   for application of outputs   from climate models   to   assess hydrological impacts;
•             clarity of overall argument, supported by evidence   from modelling, and   supported by references where appropriate.
Marks   will be allocated as   follows:
Item
Percent   Allocated
Introduction
5%
Stochastic rainfall model and analysis
15%
Hydrological impact analysis
25%
Water system impact analysis
40%
Conclusion
15%
Submission date: Monday 20th   January 2025, 2.00pm
Summary of   workflow and models:
A.   Stochastic rainfall model                                                                   Comparison   with
•          Historical rainfall simulation of N   years of synthetic data
   
•          Climate change   rainfall
simulation(s) of N   years using   perturbed synthetic data
Observed rainfall statistics   for baseline   period
   
Simulated rainfall from the baseline   period
B. Shetran model
Comparison   with
•          Climate change baseline   simulation
No comparison needed, as   this is   the
baseline run (there is   no river flow record   corresponding   to   the synthetic rainfall)
•          Climate change scenario   simulations
(multiple   simulations)
Simulated river   flow   from   the climate            change baseline run. (Note:   you   do not   need   to use   the objective   functions   for   these comparisons).
C.      Pywr   water resources model
Comparison   with
•          Climate change baseline   simulation
No comparison needed
•          Climate change scenario   simulations
(multiple   simulations)
Simulated   water resource outputs   from   the climate change baseline run.
   

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
