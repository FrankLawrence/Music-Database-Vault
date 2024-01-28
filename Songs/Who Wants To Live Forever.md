---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[A Kind of Magic (1977).jpg]]"
---
[Time:: 4:57]
[Artist:: [[Queen]] ]
[Genre:: Rock]
[Played:: 4]
[Album:: [[A Kind of Magic (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Who Wants To Live Forever]]
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
		intensity: page["Who_Wants_To_Live_Forever"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
