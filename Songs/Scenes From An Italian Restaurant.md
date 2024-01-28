---
tags: Song  
banner: "![[Piano Man (1977).jpg]]"
---
[Time:: 7:34]
[Artist:: [[Billy Joel]] ]
[Genre:: Pop]
[Played:: 1]
[Album:: [[Piano Man (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Scenes From An Italian Restaurant]]
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
		intensity: page["Scenes_From_An_Italian_Restaurant"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
