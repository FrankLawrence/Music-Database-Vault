---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Footloose: Original Soundtrack of the Paramount Motion Picture (1984).jpg]]"
---
[Time:: 2:56]
[Artist:: [[Kenny Loggins]] ]
[Genre:: Pop Rock]
[Played:: ]
[Album:: [[Footloose: Original Soundtrack of the Paramount Motion Picture (1984)]]]
[Year:: 1984]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Footloose]]
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
		intensity: page["Footloose"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
