---
tags: Song  
banner: "![[Greatest Hits - Das Beste (1970).jpg]]"
---
[Time:: 3:37]
[Artist:: [[Les Humphries Singers]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[Greatest Hits - Das Beste (1970)]]]
[Year:: 1970]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I'm From The South, I'm From Ge-O-Orgia]]
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
		intensity: page["I'm_From_The_South,_I'm_From_Ge-O-Orgia"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
