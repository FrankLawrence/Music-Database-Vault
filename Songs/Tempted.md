---
tags: Song  
banner: "![[East Side Story (1981).jpg]]"
---
[Time:: 3:58]
[Artist:: [[Squeeze]] ]
[Genre:: Blue eyed soul]
[Played:: 1]
[Album:: [[East Side Story (1981)]]]
[Year:: 1981]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Tempted]]
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
		intensity: page["Tempted"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
