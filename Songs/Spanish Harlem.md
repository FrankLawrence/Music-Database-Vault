---
tags: Song  
banner: "![[The Best Of Aretha Franklin (1984).jpg]]"
---
[Time:: 3:32]
[Artist:: [[Aretha Franklin]] ]
[Genre:: R&B]
[Played:: 2]
[Album:: [[The Best Of Aretha Franklin (1984)]]]
[Year:: 1984]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Spanish Harlem]]
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
		intensity: page["Spanish_Harlem"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
