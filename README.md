# MovementOnTheWorld_TacoSupport
The Movement on the World tour map guides for guildwars 2 on Taco ! 

Simply put the "MoW.taco" into the POIs folder of the Taco App. 

In the Tactical Display Settings and submenu Toggle Visibility Behavior, I advise **hiding in-game and mini-map roads and only keep them on the map. Do the reverse for markers, hide them on map and mini-map, but let them appear in-game**. 

___List of Maps In The Pack___
- Caledon Forest
- Queensdale
- Wayfarer Foothills

___Trails without Informative Markers are also implemented for___
- Plains of Ashford
- Brisban Wildlands
- Diessa Plateau
- Kessex Hills
- Snowden Drifts 
- Metrica Province

These are not visible to the user unless they extract the achives and generate an associated .xml file with the following code :
```
<OverlayData>
	<MarkerCategory name="MoW" DisplayName="Movement On The World">
		<MarkerCategory name="Makers" iconFile="Data/MoWMaker.png" behavior="1" fadeNear="4000" fadeFar="5000" infoRange="10" autoTrigger="false"/>
		<MarkerCategory name="MakersWaypoint" iconFile="Data/MoWWPMaker.png" behavior="1" fadeNear="1000" fadeFar="1500" infoRange="10" autoTrigger="false"/>
		<!--For higher visibility Markers use fadeNear="4000" fadeFar="5000"-->
        <MarkerCategory name="Roads" texture="Data/MoWT.png"/>
    </MarkerCategory>
	<POIs>
    <!-- In the following line, modify the NameOfTrail as convenient -->
		<Trail trailData="Trails/NameOfTrail.trl" animSpeed="0.5" alpha="1" type="MoW.Roads" fadeNear="500" fadeFar="1000"/>
  </POIs>
</OverlayData>
```

## **Your feedback is appreciated!**
