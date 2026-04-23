Original Code/Miner Behavior
Miner had 3 states:
  Mining
  Drinking
  Banking
Miner became parched at thirst >= 15
Miner’s pockets were full at gold >= 5
Drinking reduced thirst by 1 every tick that isn't drinking
Miner deposited gold one nugget at a time

My Changes-
Parched Threshhold changed from 15 to 6, so that the drinking/parched action would actually happen
Drink action changed from -1 thrist to -2 thirst, to reduce drink tick spam
Pocket Threshold changed from 5 to 7
