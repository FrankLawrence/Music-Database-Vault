---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[After Hours (2020).jpg]]"
---
[Time:: 3:20]
[Artist:: [[The Weeknd]] ]
[Genre:: R&B/Soul]
[Played:: 5]
[Album:: [[After Hours (2020)]]]
[Year:: 2020]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Blinding Lights]]
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
		intensity: page["Blinding_Lights"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
