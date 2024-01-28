---
tags: Song  
banner: "![[Jazz (1989).jpg]]"
---
[Time:: 4:25]
[Artist:: [[The Rippingtons]] ]
[Genre:: Jazz]
[Played:: ]
[Album:: [[Jazz (1989)]]]
[Year:: 1989]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Tourist In Paradise]]
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
		intensity: page["Tourist_In_Paradise"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
