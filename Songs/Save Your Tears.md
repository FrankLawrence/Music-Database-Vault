---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[After Hours (2020).jpg]]"
---
[Time:: 4:09]
[Artist:: [[The Weeknd]] ]
[Genre:: Synth-Pop]
[Played:: 36]
[Album:: [[After Hours (2020)]]]
[Year:: 2020]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Save Your Tears]]
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
		intensity: page["Save_Your_Tears"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
