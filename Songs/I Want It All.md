---
tags: Song ⭐⭐⭐⭐ 
banner: "![[The Miracle (1977).jpg]]"
---
[Time:: 4:02]
[Artist:: [[Queen]] ]
[Genre:: Rock]
[Played:: 1]
[Album:: [[The Miracle (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I Want It All]]
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
		intensity: page["I_Want_It_All"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
