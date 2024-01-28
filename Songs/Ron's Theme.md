---
tags: Song ⭐⭐⭐⭐ 
banner: "![[BlacKkKlansman (Original Motion Picture Soundtrack) (2019).jpg]]"
---
[Time:: 5:19]
[Artist:: [[Terence Blanchard]] ]
[Genre:: Classical, Stage & Screen]
[Played:: 22]
[Album:: [[BlacKkKlansman (Original Motion Picture Soundtrack)]]]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Ron's Theme]]
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
		intensity: page["Ron's_Theme"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
