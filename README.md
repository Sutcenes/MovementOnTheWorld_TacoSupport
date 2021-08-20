# MovementOnTheWorld_TacoSupport
The Movement on the World tour map guides for guildwars 2 on Taco ! 

Simply put the "MoW.taco" into the POIs folder of the Taco App. 

In the Tactical Display Settings and submenu Toggle Visibility Behavior, I advise **hiding in-game and mini-map roads and only keep them on the map. Do the reverse for markers, hide them on map and mini-map, but let them appear in-game**. 

___List of Maps In The Pack___
- Caledon Forest
- Queensdale
- Wayfarer Foothills
- Plains of Ashford
- Metrica Province

___Trails without Informative Markers are also implemented for___
- Brisban Wildlands
- Diessa Plateau
- Kessex Hills
- Snowden Drifts 


These are not visible to the user unless they extract the achives and generate an associated .xml file with the following code :
```
<OverlayData>
    <POIs>
    <!-- In the following line, modify the "NameOfTrail" as convenient -->
		<Trail trailData="Trails/NameOfTrail.trl" animSpeed="0.5" alpha="1" type="MoW.Roads" fadeNear="500" fadeFar="1000"/>
    </POIs>
</OverlayData>
```

## **Your feedback is appreciated!**
