# Honors Thesis
This repo walks through the R code that I wrote and executed as part of my research and analysis for my undergraduate thesis.

**Files:**
The files in this repo include the following:

* 4 Rmd files, titled in order, that walk through the R code that supported each phase of the project;
* A zip file containing the original datasets that I used to create a bespoke dataframe for the purposes of my analysis;
* Most of those bespoke dataframes - excluding, unfortunately, the files I created for, input to, and derived from my spatial analysis process, as these have been too large to upload and I am still developing my Git LFS skills; and
* A sample and the complete copy of the final product that these datasets and models supported - my undergraduate honors thesis.

## Background
In 2020, I completed my undergraduate honors thesis in government, which examined the apolitical crisis conditions under which armed non-state actors (ANSAs) accrue power. My research hinged on a tripartite methodology to ascertain the crisis conditions under which ANSAs accrue power: a series of linear regression models, a spacial analysis component, and three qualitative case studies. This R Markdown (Rmd) file first outlines how I cleaned and wrangled publicly available data regarding apolitical crises and ANSA attacks to produce unique datasets for quantitative analysis. The document then lays out the statistical models that I constructed to analyze those datasets.

For those interested in some "light" reading on ANSAs and/or the particularities of and justifications for my methodological approach, the full text of my honors thesis is available [here](https://github.com/samkanej/Honors-Thesis/blob/46237e07e037c2af32838b8116078ecc7a9a8fea/Kane_Honors%20Thesis.pdf), and an excerpt of it is available [here](https://github.com/samkanej/Honors-Thesis/blob/d213e2a38b4f604d53a10674be249ac7860d6db2/Kane_Writing%20Sample_%20ANSA%20Power%20Accrual%20Mechanisms.pdf).

## Abstract
This thesis seeks to ascertain the apolitical crisis conditions under which armed non-state actors (ANSAs) accrue power. Existing literature examines the structures that nurture ANSA power, including territorial control, group legitimacy, and access to resources. A monopoly on the use of force enables groups to sustain these structures. I explore whether ANSAs instrumentalize moments of apolitical national crisis to nurture these pillars of power and expect that groups will decrease their reliance on the use of force, instead utilizing catastrophes as opportunities to bolster legitimacy among local populations. Statistical, spatial, and qualitative analyses buttress this pursuit. In short, this research suggests that groups do try to accrue power in times of crisis, though not through service provision. Instead, they rely on force initially, and with an interaction effect between the temporal and spatial variation of their use of force – a curious finding that necessitates further investigation. As well, inter-group competition does not increase; groups instead seek to build alliances when threatened. Lastly, some groups rely on performativity sometimes – namely, politically motivated ANSAs use symbolic appeals. The duration and expansiveness of a disaster might also affect which groups make these appeals.

## Dataset bibliography
I sourced data from Uppsala Conflict Data Program's Georeferenced Event Dataset, the World Bank's Data Bank, the Emergency Events Database, and Harvard Business School's Global Crises Data to create my own 41-variable dataset for analysis. Here are the applicable sources:
* Sundberg, Ralph, and Erik Melander. “Introducing the UCDP Georeferenced Event Dataset.” Journal of Peace Research 50, no. 4 (2013).
* World Bank, World Development Indicators (2020).
* Global Crises Data, Harvard Business School (2020).
* International Disaster Database, Centre for Research on the Epidemiology of Disasters (2020).

## License
BSD 3-Clause License

Copyright (c) 2024, Sam Kane

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this
   list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice,
   this list of conditions and the following disclaimer in the documentation
   and/or other materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its
   contributors may be used to endorse or promote products derived from
   this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
