# SpellingBee

The New York Times has a daily game called _Spelling Bee_ in which you are given seven letters, with one letter that is at the center of the "hive". Players enter words based on the seven letters that need to be at least four letters long and contain the letter at the center of the hive at least once. Points are given according to how long the words are. Pangrams (words that use all seven letters at least once) are given extra points.

The game also has levels that go up to *Genius*, and there are point values that must be reached for each level. Since there are new spelling bee letters and configurations each day, the points levels for each day also change. 

If someone enters in every word on the NYT's list they attain the status of _Queen Bee_, however the points level (or number of words) for this achievement is not provided in the game. 

This seems like a fun opportunity for some regression to use the points for the _Genius_ level to predict the total number of points (that would get you to _Queen Bee_) and also the total number of words. 

Data were collected from https://nytbee.com/
