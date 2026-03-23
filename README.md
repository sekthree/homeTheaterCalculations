# homeTheaterCalculations
Calculations used when building a home theater

NOTE: I am NOT an expert, nor are these absoluate. I created these using empircal data. Please verify all calculations. I am not responsible for any issues encountered.


RSIC-1 Calculator - Calculates the amount of clips needed for given area (ceiling), the amount of hat channel needed, and where to place those channels. 
Background: I know that spec and install sheets are provided when purchasing RSIC-1 clips as well as available online, however I like when things are just made easier for me. Pac international also provides a calculator here: https://pacinternationalllc.com/calculator/. I wanted something to tell me not only how many clips I would need but also how much channel is needed AND where to place those channel rows to meet space (16" o.c. or 24" o.c.).


Baffle Box Calculator - Calculates the size of box needed to meet a rooms recommended air exchanges per hour. Provides two ways for a box to be built: 1 box with dimension restrictions, and 1 box with no restrictions. It's recommended to build a return box 20% larger than the supply, i did not incorporate that into the calc.
Background: I've found the SIMs online available from SoundProofingCompany, but they don't seem to provide details on measurements. Whether they assist with this when calling them I don't know as I've yet to contact them. I also didn't find any threads on this either, that go into detail. SOO I went down a really deep rabbit hole. As most would know HVAC systems can be very precise, so i didn't want to just slap a box together. This might work but I'm not entirely sure. For the second box calculations I followed the guide by Soundproof your studio: How to build a baffle box like a pro (https://www.youtube.com/watch?v=YEUq1nzaD-c).

----------------------How to USE ------------------------

----RSIC-1--------
1. Enter Length and width of ceiling. Width can also be height of a wall however placement does not incorporate 3"-6" placement of top and bottom rows.
2. Change units accordinlgy on length and width: feet, inches
3. Add type of hat channel available to you.e.g. 10' or 12'

The clip quantity calculations are based off the PAC international tables.
The Hat Channel calculations incorporate 6" overlap and ~10% extra, rounded up.
Minimum rows should allow for proper spacing.
Inner rows are those rows that are NOT the end (top and bottom) rows. 
Placement should allow for end rows on each side within 8" from edge and within 24" from next/previous row.
Row placements are measured from edge.
As with wood working and ALL things, DOUBLE & TRIPLE check all calculations

-----Baffle Box-------
Description: Calculate the baffle box size needed for a rooms requirements for HVAC vents. Standard requirements for a home residents is that the air in a room should be exchanged 6 times per hour. By providing a rooms dimensions (LxWxH) the Cubit Fee per Minute (CFM) that is needed is calculated for this exchange to take place. For every occupant of a room it's also recommended for 15 CFM to occur, for six people that's 90 CFM, so unless crowded in a closet most Loads should suffice.
When air is supplied a rushing/wooshing sound and sometimes a whistle can be audible by the fast moving air. This is due to the speed of the air being supplied within a given boxed area. To alleviate this issue the air velocity can be lowered and surfaces can be affixed with sound absorbing material. The recommended velocity for air to be supplied so as to not be audible is roughly 300 Feet Per Minute (FPM). By providing this value the box is calculated to meet this requirement, however this is not a static value and can be changed if desired. Think of water moving through and releasing from a pipe: when minimum slow moving water there's no noise (other than the drip hitting a surface), but when tons of water is rushing through a small pipe it makes a garbbablebblebele sound, lik a firehose, shower, or faucet.

When calculating a box, it's assumed to be using 3/4"" plywood and 1"" ductboard. These values are not static and can be updated. Two types of boxes are calculated. 

The 1st is calculated based on size restrictions provided, but only two values: Width and Height, This is because the third value (Length) is what is calculated in order to meet CFM & FPM requirements. Recommended for instances of placing baffle boxes between ceiling joists or in soffits. The amount of baffles can also be given which will affect the box size. Each baffle provides reduction in decibels, however I've read diminishing returns occurs beyond three baffles. The golden ratio is also used to calculate baffle placement. Staggered baffles help disrupt air and sound to reduce static pressure and standing waves. Baffle placement is provided in the Absoluate On Center Position column. This is to be measured from the entrance side on the inside of the box against the wood not the liner. The measurement marks the CENTER of the wood baffle. Baffles should be placed along the wider part (width or height) of the box, the calculations try to take this into considerations. Ex. if you have a box 20""x13"", the baffle will be cut and placed against the 20"" side giving an ~11"" baffle (wood)  with ~4"" gap (between liners). Lastely included is to calculate from the ""Load CFM"" or from ""CFM minus soffit"" area. If soffits are in the room this technically takes away from a rooms cubic area and thus from it's CFM. It's recommended to use the Load CFM as occupancy and heat from equipment factor into room comfort, but in the event you're working with a small area for baffle placement and want to squeeze out as much as you can, removing soffit area can be done. Soffits assume to be identical.

The 2nd is calculated based on internal duct size being equal throughout the box with no external measurement restrictions. This is used for instances when placing the baffle box outside of the room like in an adjacent room. The website provided should provide the exact measurements for internal duct area to meet the CFM & FPM requirements. These variables are then transferred to this sheet to provide the box size needed to match the internal duct size. Although the sheet also validates measurements by calculating the FPM from the internal duct size provided; green - good, red - bad. Duct sizes can be entered without visiting the website, and the sheet will show if requirements are met or not. Baffle count can also be entered, see above for baffle count explaination.
