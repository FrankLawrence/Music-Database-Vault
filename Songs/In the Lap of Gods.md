---
tags: Song  
banner: "![[Sheer Heart Attack (1974).jpg]]"
---
[Time:: 3:28]
[Artist:: [[Queen]] ]
[Genre:: ]
[Played:: ]
[Album:: [[Sheer Heart Attack (1974)]]]
[Year:: 1974]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[In the Lap of Gods]]
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
		intensity: page["In_the_Lap_of_Gods"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
