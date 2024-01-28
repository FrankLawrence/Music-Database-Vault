---
tags: Song  
banner: "![[Jazz (1978).jpg]]"
---
[Time:: 3:51]
[Artist:: [[Queen]] ]
[Genre:: Hard Rock]
[Played:: 1]
[Album:: [[Jazz (1978)]]]
[Year:: 1978]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Fat Bottomed Girls]]
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
		intensity: page["Fat_Bottomed_Girls"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
