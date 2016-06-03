# Geofence-Me-Version-1.2
This is a more robust form of the Gepfence-Me project in my repo.
The core idea:
User can create an event (a closed region) in a map.
this map can be vissible to other user(only if connected) or invissible to every one except the owener.
user can initiate connection and end connectin from both side.
the event has title, coordinates of location, strt date. promotion start date, promotion end date and a hidden field.
if the hidden field of the event is false, then the map will not be vissible to others, either connected or disconneted.
even though the event is hidden, dosent mean that its not there. When the connected users enter the location of the event, invitation is sent.


entity diagram for database can be found in relatedStuff folder.

using parse.com as a database for now.
using facebook login with parse.



Features: 
1. Authentication with facebook
2. Backend with parse.
2. interactive maps.

