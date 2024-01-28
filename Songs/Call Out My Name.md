---
tags: Song ⭐⭐⭐⭐ 
banner: "![[My Dear Melancholy (2018).jpg]]"
---
[Time:: 3:49]
[Artist:: [[The Weeknd]] ]
[Genre:: Alternative]
[Played:: 4]
[Album:: [[My Dear Melancholy (2018)]]]
[Year:: 2018]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Call Out My Name]]
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
		intensity: page["Call_Out_My_Name"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
