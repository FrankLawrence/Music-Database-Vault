---
tags: Song  
banner: 
---
[Time:: 2:16]
[Artist:: [[Henryk Szeryng: English Chamber Orchestra]] ]
[Genre:: Classical]
[Played:: 2]
[Album:: [[Vivaldi: The Four Seasons, Etc. (1976)]]]
[Year:: 1976]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Vivaldi- Violin Concerto In F Minor, Op. 8-4, RV 297, "The Four Seasons (Winter)" - 2. Largo]]j
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
		intensity: page["Vivaldi-_Violin_Concerto_In_F_Minor,_Op._8-4,_RV_297,_"The_Four_Seasons_(Winter)"_-_2._Largo"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
