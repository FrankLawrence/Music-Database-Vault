---
tags: Song  
banner: "![[Parachutes (2000).jpg]]"
---
[Time:: 7:16]
[Artist:: [[Coldplay]] ]
[Genre:: Alternative Rock]
[Played:: 5]
[Album:: [[Parachutes (2000)]]]
[Year:: 2000]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Everything's Not Lost (Includes Hidden Track 'Life Is For Living')]]
````
  ```dataviewjs
const calendarData = { 
	colors: { 
		blue: ["#9ccfd8", "#5BAAB8", "#57A1BB", "#5da8c7", "#3e8fb0"] 
	}, 
	entries: [] 
}; 

for (let page of dv.pages('"Daily Notes"')) { 
	calendarData.entries.push({ 
		date: page.file.name, 
		intensity: page["Everything's_Not_Lost_(Includes_Hidden_Track_'Life_Is_For_Living')"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
