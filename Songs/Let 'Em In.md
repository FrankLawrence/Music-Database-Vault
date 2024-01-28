---
tags: Song ⭐⭐⭐⭐ 💛
banner: "![[Back in the World (2003).jpg]]"
---
[Time:: 5:10]
[Artist:: [[Paul McCartney]] ]
[Genre:: Pop]
[Played:: 21]
[Album:: [[Back in the World (2003)]]]
[Year:: 2003]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Let 'Em In]]
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
		intensity: page["Let_'Em_In"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
