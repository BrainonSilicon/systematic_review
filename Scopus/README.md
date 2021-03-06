# Scopus

## Progress
- [x] execute search in database
- [x] limit search within database
- [x] download results
- [x] duplicate file for filtering
- [x] create filters
- [x] update papercounts
- [ ] screen titles
- [ ] screen abstracts
- [ ] sort filtered results


## Results

| Search   |     Results   |
|----------|:-------------:|
| first search | 93,656 |
| limit (1) applied | 65,641 |
| limit (2) applied | 62,537 |
| limit (3) applied | 55,557 |
| limit (4) applied | 25,006 |
| limits (5-7) applied | 2,632 |
| manual search: Specific Term Search Results  | 1,877  |
| combined search 6 with manual search | 4,509 |
| duplicates removed | 3,994 |
| filter applied | 991 |
| titles screened   |   |
| abstracts screened |  |
| final included papers   |   |

## Search strategy
- (ANY{VR terms}) AND (ANY{transfer terms}) AND (ANY{learning terms})
- NOT ("neural network" OR "deep learning"  OR  "molecular")
- Limits {1-7}
- Results downloaded
- Specific Term Search Results applied
- Additional Results Downloaded
- Filter applied
- Titles and abstracts screened

### Search Terms
1. VR Terms: { Augmented reality, Mixed reality, Virtual reality, virtual environment, immersive reality, immersive environment, simulat*, screen, Head mounted display, HMD, VR }
2. Transfer Terms: { Generali* , Transfer }
3. Learning Terms: { skill*, learn*,  train*, adapt*, acquisition, action, motor, visuomotor, sensorimotor,  interaction, memory }

#### Boolean Example(s)
( TITLE-ABS-KEY ( "augmented reality"  OR  "mixed reality"  OR  "virtual reality"  OR  "virtual environment"  OR  "immersive reality"  OR  "immersive environment"  OR  simulat*  OR  screen  OR  "head mounted display"  OR  hmd  OR  vr )  AND  TITLE-ABS-KEY ( generali*  OR  transfer )  AND  TITLE-ABS-KEY ( skill*  OR  learn*  OR  train*  OR  adapt*  OR  acquisition  OR  action  OR  motor  OR  visuomotor  OR  sensorimotor  OR  interaction  OR  memory ) )

## Exclusion Criteria

#### Exclusion Terms
- "neural network" OR "deep learning"  OR  "molecular"

#### Limit To
1) limit by subject area
2) limit by Document Type (Article, Conference, Undefined) and Source Type (Article, Conference Proceedings)
3) limit to English
4) limit by Subject Area
5) limit by Keyword
6) limit by Source Type (exclude non-topical journals and conferences)
7) limit by year (2000-2021)


## Specific Term Search Results
A "within results" specific term search was completed on Search 6 (limits (5-7) applied, results returned: 2,632). The specific terms and their returned results counts are below. 

| Term     |     Results   |
|----------|:-------------:|
| head mounted display | 160 |
| HMD | 80 |
| virtual reality | 3112 |
| VR | 836 |
| augmented reality | 627 |
| immersive| 254 |
| immersion| 268 |


#### Filter Papers of Relevance
The review specifically focuses on HMD based VR (which comes under different names). Papers are filtered with abstracts being searched for the following terms
- "immersive","immersion","hmd","HMD","head mounted display","VR","rift","vive","virtual reality","headset"
