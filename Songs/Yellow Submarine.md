---
tags: Song  
banner: "![[1 (2000).jpg]]"
---
[Time:: 2:45]
[Artist:: [[The Beatles]] ]
[Genre:: ]
[Played:: 2]
[Album:: [[1 (2000)]]]
[Year:: 2000]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Yellow Submarine]]
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
		intensity: page["Yellow_Submarine"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
