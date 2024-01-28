---
tags: Song ⭐⭐⭐ 
banner: "![[The Very Best Of Smooth Jazz [Disc 1] (1996).jpg]]"
---
[Time:: 5:02]
[Artist:: [[Luther Vandross]] ]
[Genre:: Jazz]
[Played:: ]
[Album:: [[The Very Best Of Smooth Jazz [Disc 1] (1996)]]]
[Year:: 1996]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Goin' Out Of My Head]]
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
		intensity: page["Goin'_Out_Of_My_Head"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
