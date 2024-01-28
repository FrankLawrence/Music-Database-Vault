---
tags: Song  
banner: "![[Into the Gap (1984).jpg]]"
---
[Time:: 4:11]
[Artist:: [[The Thompson Twins]] ]
[Genre:: New Wave]
[Played:: ]
[Album:: [[Into the Gap (1984)]]]
[Year:: 1984]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Hold Me Now]]
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
		intensity: page["Hold_Me_Now"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
