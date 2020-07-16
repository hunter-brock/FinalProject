# FinalProject

#### Project Description
  This project will use the public API for the game Halo 5 Guardians to compare and analyze player stats. This data can be used to see which maps and/or gametypes the players perform best on, their favorite weapons, how they compare to each other and possibly determine what kind of role the player would have on a competitive team.

This standard python project will have:

  At least 3 classes: One that will access the player stats API and gather the needed data based on the player gamertags given, one that will access the metadata API and replace the data from the previous class with more accurate maps and gametype names, and a third that will compare and visualize that data.

In the Halo 5.ipynb file in this repo, I access the API and take a sample data set for one player that is organized by gametypes. Some of the entries in this dataset such as the column 'GameBaseVariantId' would need to be edited by calling the metadata API and replacing those entries with what is retrieved. I would like to use data from the API such as this example and be able to compare players.
