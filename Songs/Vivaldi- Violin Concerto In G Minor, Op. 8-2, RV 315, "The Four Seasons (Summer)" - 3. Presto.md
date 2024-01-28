---
tags: Song  
banner: 
---
[Time:: 3:22]
[Artist:: [[Henryk Szeryng: English Chamber Orchestra]] ]
[Genre:: Classical]
[Played:: 1]
[Album:: [[Vivaldi: The Four Seasons, Etc. (1976)]]]
[Year:: 1976]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Vivaldi- Violin Concerto In G Minor, Op. 8-2, RV 315, "The Four Seasons (Summer)" - 3. Presto]]
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
		intensity: page["Vivaldi-_Violin_Concerto_In_G_Minor,_Op._8-2,_RV_315,_"The_Four_Seasons_(Summer)"_-_3._Presto"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
