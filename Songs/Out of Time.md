---
tags: Song  
banner: "![[Aftermath (1966).jpg]]"
---
[Time:: 5:37]
[Artist:: [[The Rolling Stones]] ]
[Genre:: Pop Rock]
[Played:: ]
[Album:: [[Aftermath (1966)]]]
[Year:: 1966]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Out Of Time]]
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
		intensity: page["Out_of_Time"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
