---
tags: Song  
banner: "![[The Very Best Of Smooth Jazz [Disc 1] (1963).jpg]]"
---
[Time:: 2:37]
[Artist:: [[TAMBA TRIO]] ]
[Genre:: Jazz]
[Played:: ]
[Album:: [[The Very Best Of Smooth Jazz [Disc 1] (1963)]]]
[Year:: 1963]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Mas Que Nada]]
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
		intensity: page["Mas_Que_Nada"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
