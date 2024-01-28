---
tags: Song  
banner: "![[Free as a Bird (1987).jpg]]"
---
[Time:: 7:50]
[Artist:: [[Supertramp]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[Free as a Bird (1987)]]]
[Year:: 1987]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[An Awful Thing To Waste]]
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
		intensity: page["An_Awful_Thing_To_Waste"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
