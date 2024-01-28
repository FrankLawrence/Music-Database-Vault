---
tags: Song ⭐⭐⭐⭐⭐ 

[Time:: 1:26:15]
[Artist:: [[hiphop]] ]
[Genre:: ]
[Played:: 7]
[Album:: ]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Chill Lo-fi Hip-Hop Beats ]]
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
		intensity: page["Chill_Lo-fi_Hip-Hop_Beats_"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
