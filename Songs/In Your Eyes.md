---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[After Hours (2020).jpg]]"
---
[Time:: 3:58]
[Artist:: [[The Weeknd]] ]
[Genre:: Synth-Pop]
[Played:: 29]
[Album:: [[After Hours (2020)]]]
[Year:: 2020]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[In Your Eyes]]
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
		intensity: page["In_Your_Eyes"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
