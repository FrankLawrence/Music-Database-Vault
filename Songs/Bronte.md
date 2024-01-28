---
tags: Song ⭐⭐⭐ 
banner: "![[Making Mirrors (2011).jpg]]"
---
[Time:: 3:14]
[Artist:: [[Gotye]] ]
[Genre:: Indie Rock]
[Played:: 1]
[Album:: [[Making Mirrors (2011)]]]
[Year:: 2011]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Bronte]]
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
		intensity: page["Bronte"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
