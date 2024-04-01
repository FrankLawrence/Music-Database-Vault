---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[The Original Soundtrack (1975).jpg]]"
---
[Time:: 6:00]
[Artist:: [[10cc]] ]
[Genre:: Soft Rock]
[Played:: 61]
[Album:: [[The Original Soundtrack (1975)]]]
[Year:: 1975]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I'm Not in Love]]
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
		intensity: page["I'm_Not_in_Love"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
