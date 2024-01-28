---
tags: Song  
banner: "![[Greatest Hits - Das Beste (1970).jpg]]"
---
[Time:: 4:27]
[Artist:: [[Les Humphries Singers]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[Greatest Hits - Das Beste (1970)]]]
[Year:: 1970]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Soolaimon]]
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
		intensity: page["Soolaimon"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
