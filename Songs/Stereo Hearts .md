---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[The Papercut Chronicles II (2011).jpg]]"
---
[Time:: 3:37]
[Artist:: [[Gym Class Heroes]] [[Adam Levine]] ]
[Genre:: Pop]
[Played:: 4]
[Album:: [[The Papercut Chronicles II (2011)]]]
[Year:: 2011]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Stereo Hearts ]]
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
		intensity: page["Stereo_Hearts_"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
