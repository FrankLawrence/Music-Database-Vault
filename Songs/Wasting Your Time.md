---
tags: Song ⭐⭐⭐ 
banner: "![[The Very Best Of Smooth Jazz [Disc 1] (2000).jpg]]"
---
[Time:: 4:09]
[Artist:: [[Frank McComb]] ]
[Genre:: Jazz]
[Played:: 3]
[Album:: [[The Very Best Of Smooth Jazz [Disc 1] (2000)]]]
[Year:: 2000]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Wasting Your Time]]
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
		intensity: page["Wasting_Your_Time"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
