---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[The Works (1977).jpg]]"
---
[Time:: 5:43]
[Artist:: [[Queen]] ]
[Genre:: Rock]
[Played:: 6]
[Album:: [[The Works (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Radio Ga Ga]]
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
		intensity: page["Radio_Ga_Ga"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
