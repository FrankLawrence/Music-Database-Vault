---
tags: Song ⭐⭐⭐⭐ 
banner: "![[The Graduate (1965).jpg]]"
---
[Time:: 3:06]
[Artist:: [[Simon & Garfunkel]] ]
[Genre:: Soundtrack]
[Played:: ]
[Album:: [[The Graduate (1965)]]]
[Year:: 1965]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[The Sound Of Silence]]
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
		intensity: page["The_Sound_Of_Silence"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
