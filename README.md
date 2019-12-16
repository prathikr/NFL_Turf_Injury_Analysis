# NFL_Turf_Injury_Analysis

Ideas:
  - Use clustering algorithms to find similarities among athletes based on the length of their injuries (ie. feed parameters about game condition and play type and player, group on if injury was <1day, <7 days, <28 days, or <42 days - data is present in InjuryRecord.csv). Compare turf-type (in InjuryRecord.csv) along with game condition and player data (data can be found in PlayList.csv) and see how significant turf-type is. Try a bunch of models to see in which one turf-type is a high indicator of injury time. Write up analysis on theories behind this behavior.


Potential Tasks
  - Understand our entire set of features and figure out which ones we can use in our model
  - Convert 3 files into one massive csv holding one row per entry to feed to our dataset. This will require some joining on game/play IDs.
  - Figuring out a use for the spacial data on player movement during the plays. Maybe come up with a plotting algorithm that'll show us the path the player took to see if that had anything to do with their injury. Maybe plot the paths of players who suffered similar length injuries to look for patterns.
  - Brainstorn clustering algorithms to give us differnet sets of feature importance
  
  Prathik's Tasks
    - Learn how Tensorflow can be applied to this project
  
  Gavin's Tasks
  
  Kaushik's Tasks
