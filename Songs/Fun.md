---
tags: Song  
banner: "![[A Head Full of Dreams (2015).jpg]]"
---
[Time:: 4:28]
[Artist:: [[Coldplay]] [[Tove Lo]] ]
[Genre:: Pop Rock]
[Played:: 2]
[Album:: [[A Head Full of Dreams (2015)]]]
[Year:: 2015]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Fun]]
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
		intensity: page["Fun"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
