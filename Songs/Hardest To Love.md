---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[After Hours (2020).jpg]]"
---
[Time:: 3:32]
[Artist:: [[The Weeknd]] ]
[Genre:: Synth-Pop]
[Played:: 50]
[Album:: [[After Hours (2020)]]]
[Year:: 2020]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Hardest To Love]]
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
		intensity: page["Hardest_To_Love"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
