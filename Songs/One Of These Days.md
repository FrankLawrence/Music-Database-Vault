---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Meddle (1971).jpg]]"
---
[Time:: 5:56]
[Artist:: [[Pink Floyd]] ]
[Genre:: Progressive Rock]
[Played:: 65]
[Album:: [[Meddle (1971)]]]
[Year:: 1971]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[One Of These Days]]
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
		intensity: page["One_Of_These_Days"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
