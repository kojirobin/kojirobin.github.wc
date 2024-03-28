# Node Marking (kojirobin github)

This is a project involving Wynntils 1.19.4 push "Artemis" waypoints system. It is a WIP.

The premise is to mark all of the gathering profession "nodes" into a waypoint file. Basically.


## How to use

There is a file for each material that you can import into your Artemis mod.

### map poiProvider

Artemis has this neat command to import Waypoints from online raw files:

/map poiProvider

To use this command, pick the file of the material you want, click on the "Raw" button on the right upper side of the page. That will take you to the URL of the raw code. Copy that URL and do:

/map poiProvider add "<any name you want/the name of the material you're importing>" "<URL of the raw code>"

The quotation marks are vital when prompting this command.

You can toggle the waypoints you import from this command via:

/map poiProvider toggle <choose from your list of added waypoint sets>

You can update (reload) the imported sets in your game if the raw codes here in GitHub get updated. This is useful for new nodes that I've included in the file or nodes that have been removed from the maingame.

/map poiProvider reload

The remaining commands are self-explanatory:

/map poiProvider list
/map poiProvider remove <choose from your list of added waypoint sets>

That's basically it!
