---
tags: Song ⭐⭐⭐ 
banner: "![[The Very Best Of Smooth Jazz [Disc 1] (1987).jpg]]"
---
[Time:: 4:50]
[Artist:: [[Larry Carlton]] ]
[Genre:: Jazz]
[Played:: ]
[Album:: [[The Very Best Of Smooth Jazz [Disc 1] (1987)]]]
[Year:: 1987]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Minute By Minute]]
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
		intensity: page["Minute_By_Minute"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
