# TRBC-Implementation <br>
## An attempt to create a automated digital verson of the Thompson Reuters Business classification.<br>

Thompson Reuters Business classification is a detailed map of the business sectors, with and an elegant classification into Sectors, groups, Activity etc, it presents an amazing oppertunity for incorporation into a library style package for further applications. We intend to implement adnaved NLP methodologies to extract this classification information from the website of the respective businesses. Currently TRBC classifies over 70,000 businees across the globe, although impressive it is nowhere nere the scale of businesses operational across the globe, an automated screening mechanism makes this problem within reach.

**Process flow (intended):** <br>
- Scrap websites, <br>
  Now: basic scraping, from files <br>
  Longterm: use distributed crawler systems crawlers in the furture) <br>
- Scoop relevant text from the pages <br>
- Determine classification of the text <br>
- (Percentage of overall operation in a conglomerate, Dominant and other sectors) <br>


**Appraoch** <br>
- We lack classified data for training. <br>
- Presently going with a dataset with similar lengths of text as found in a website to demonstarte calssification capabilities of the model.
   Going with The AG news excerpts datset. <br>
   Used the master dataset, Super unclean data.<br>
   
   
   Update: 14/10/2020
