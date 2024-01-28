---
tags: Song  
banner: "![[Best Of Bowie (2002).jpg]]"
---
[Time:: 3:35]
[Artist:: [[David Bowie]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[Best Of Bowie (2002)]]]
[Year:: 2002]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Scary Monsters (& Super Creeps)]]
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
		intensity: page["Scary_Monsters_(Eyes_Without_A_Face_Super_Creeps)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
