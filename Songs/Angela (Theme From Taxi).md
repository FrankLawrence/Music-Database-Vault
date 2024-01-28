---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[The Very Best Of Smooth Jazz [Disc 1] (1978).jpg]]"
---
[Time:: 5:39]
[Artist:: [[Bob James]] ]
[Genre:: Jazz]
[Played:: 8]
[Album:: [[The Very Best Of Smooth Jazz [Disc 1] (1978)]]]
[Year:: 1978]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Angela (Theme From Taxi)]]
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
		intensity: page["Angela_(Theme_From_Taxi)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
