# IEEE

## Progress
- [x] execute search in database
- [x] limit search within database
- [x] download results
- [x] create filters
- [x] update papercounts
- [ ] screen titles
- [ ] screen abstracts


## Results

| Search   |     Results   |
|----------|:-------------:|
| vr terms | 1,100,815 |
| transfer | 49,090 |
| general*  | 88,519 |
| limit to conferences, journals, early access articles | 50,813 |
| topic limits applied | 6,239 |
| duplicates removed  | 4,365 |
| filters applied | 743 |
| abstracts screened |   |


## Search strategy
Search VR terms in Advanced Search, then 'within results' for each additional term
Apply Topic Limits to Search Results
Deduplicate
Apply filters
Screen Abstracts

### Search Terms
1. { Augmented reality, Mixed reality, Virtual reality, virtual environment, immersive reality, immersive environment, simulat*, screen, Head mounted display, HMD, VR }
2. { Generali* , Transfer }
3. { skill*, learn*,  train*, adapt*, acquisition, action, motor, visuomotor, sensorimotor,  interaction, memory }

#### Boolean Example
(1) VR terms
("All Metadata":"augmented reality") OR ("All Metadata":"mixed reality") OR ("All Metadata":"virtual reality") OR ("All Metadata":"immersive reality") OR ("All Metadata":"virtual environment") OR ("All Metadata":"immersive environment") OR ("All Metadata":screen) OR ("All Metadata":simulat*) OR ("All Metadata":"head mounted display") OR ("All Metadata":HMD) OR ("All Metadata":VR)

(2) VR + transfer
("All Metadata":"augmented reality") OR ("All Metadata":"mixed reality") OR ("All Metadata":"virtual reality") OR ("All Metadata":"immersive reality") OR ("All Metadata":"virtual environment") OR ("All Metadata":"immersive environment") OR ("All Metadata":screen) OR ("All Metadata":simulat*) OR ("All Metadata":"head mounted display") OR ("All Metadata":HMD) OR ("All Metadata":VR)transfer

(3) VR + transfer + skill
("All Metadata":"augmented reality") OR ("All Metadata":"mixed reality") OR ("All Metadata":"virtual reality") OR ("All Metadata":"immersive reality") OR ("All Metadata":"virtual environment") OR ("All Metadata":"immersive environment") OR ("All Metadata":screen) OR ("All Metadata":simulat*) OR ("All Metadata":"head mounted display") OR ("All Metadata":HMD) OR ("All Metadata":VR)transferskill*


## Exclusion Criteria

#### Limit To
Conferences, Journals, Early Access Articles

#### Exclusion Terms
Stage 1)
Select exclusion/inclusion topics within each search.
See [exclusion_topics_counts](exclusion_topics_counts.csv) for details.

#### Filter Papers of Relevance
The review specifically focuses on HMD based VR (which comes under different names). Papers are filtered with abstracts being searched for the following terms
- "immersive","immersion","hmd","HMD","head mounted display","VR","rift","vive","virtual reality","headset"

### Note:
- the IEEE database allows searches to be constrained by topic.
- it was noted on 28/3/21 that constraining search 'action_t_vr' by topics missed paper [this key paper][20b28581]
- I have flagged this paper in EndNote locker to be added in during "manual search" stage of the systematic review.
- Due to the nature of how exclusion criteria is applied, papers can slip through.
- At this time, advice is to use the exclusion abilities within a database before manually screening and there has bee no justification for **not** using the inbuilt 'exclusion by topic' feature of IEEE.

  [20b28581]: https://doi.org/10.1109/ROMAN.2005.1513829 "Augmented reality for skill transfer in assembly task"
