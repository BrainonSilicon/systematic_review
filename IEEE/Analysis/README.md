# IEEE Analysis Notes

Selected all data in table and deduplicate (NOTE: do not deduplicate using a unique identifier like doi)

- 1958 duplicate values found and removed
- 4365 unique values remain.

### Filtering Code
The following formula was writen to find the papers which used immersive virtual reality devices (HMDs) which is the focus on this review.

'=IF(<cell>="","",IF(SUMPRODUCT(--(NOT(ISERR(SEARCH({"immersive","immersion","hmd","HMD","head mounted display","VR","rift","vive","virtual reality","headset"},<cell>)))))>0,"Keep","Not relevant"))
