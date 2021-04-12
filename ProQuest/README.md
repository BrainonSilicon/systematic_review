# ProQuest


## Progress
- [x] execute search in database
- [x] limit search within database
- [x] download results
- [x] copy file for filtering
- [x] deduplicate results
- [x] create filters
- [x] update papercounts
- [ ] screen titles
- [ ] screen abstracts


## Results

| Search   |     Results   |
|----------|:-------------:|
| Search results | 7,182 results |
| Exclusion terms applied | 2,203 results |
| Filter Applied | 136 results |


Note: no duplicates found

## Search strategy
Search Terms
Limit to Source Type
Apply Exclusion Terms
Download Results
Deduplicate
Apply Filter
Manually Screen Titles and Abstracts

### Search Terms
{ Augmented reality, Mixed reality, Virtual reality, virtual environment, immersive reality, immersive environment, simulat*, screen, Head mounted display, HMD }
{ Generali* , Transfer }
{ skill*, learn*,  train*, adapt*, acquisition, action, motor, visuomotor, sensorimotor,  interaction, memory }

#### Search Boolean
(ab((skill* OR learn* OR train* OR adapt* OR acqui* OR action OR motor OR sensorimotor OR visuomotor OR interaction OR memory)) AND ab((transfer OR generali*)) AND ab(("augmented reality" OR "mixed reality" OR "virtual reality" OR "virtual environment" OR "immersive virtual reality" OR "immersive reality" OR "immersive environment" OR "immersive virtual environment" OR simulat* OR screen OR "head mounted display" OR HMD))) AND (stype.exact(("Working Papers" OR "Scholarly Journals" OR "Conference Papers & Proceedings") NOT ("Wire Feeds" OR "Trade Journals" OR "Dissertations & Theses" OR "Magazines" OR "Other Sources" OR "Newspapers")) AND la.exact("ENG"))

## Exclusion Criteria

#### Limit To
NOT ("Wire Feeds" OR "Trade Journals" OR "Dissertations & Theses" OR "Magazines" OR "Other Sources" OR "Newspapers"

#### Exclusion Terms
NOT (algorithms AND mathematical models AND machine learning AND neural networks AND computational fluid dynamics AND optimization AND mathematical analysis AND radiative transfer AND fluid flow AND artificial neural networks AND finite element method AND molecular dynamics AND heat transfer AND proteins AND parameters AND turbulent flow AND energy transfer AND organic chemistry AND three dimensional models AND domains AND regression analysis AND artificial intelligence AND dependence AND energy dissipation AND evolution AND bayesian analysis AND accuracy AND economic models AND modelling AND statistical models AND time dependence AND transfer functions AND boundary conditions AND monte carlo simulation AND hydrodynamics AND mass transfer AND energy AND charge transfer AND approximation AND momentum transfer AND wireless networks AND atmospheric models AND galaxies AND quantum theory AND generalized linear models AND phase transitions AND data transfer (computers) AND dynamic tests AND star & galaxy formation AND fluid dynamics AND star formation AND monte carlo method AND genomes)

#### Filter
'=IF(<cell>="","",IF(SUMPRODUCT(--(NOT(ISERR(SEARCH({"immersive","immersion","hmd","HMD","head mounted display","VR","rift","vive","virtual reality","headset"},<cell>)))))>0,"Keep","Not relevant"))
