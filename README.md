# CheaterList
List of TF2 Cheaters that were found via known cheater steam groups (and other methods)

# How it works
We query Steam API to give us all ID's of members in these groups
afterwords we do our conversions, dupe checks, and so forth.

After done we then query Steam API once more to give us the friends of known cheaters
then we see how many shared friends these ID's have and add them accordingly.

# Logic
If you are in a known cheater group you are added to the Group list

If you share >= 8 friends of known cheaters then you are added to the CheaterFriend list

If you share >= 4 friends of known cheaters and you yourself have a VACBan then you are added to the VAC list

# What list you should use
Group list if you wish for guaranteed accuracy

CheaterFriend list if you wish for semi-high accuracy (shouldn't have false positives)

VAC list if you wish to get everyone that was missed in the first two lists (This may have false positives)
