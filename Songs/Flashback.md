---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Pure Disco (1981).jpg]]"
---
[Time:: 3:42]
[Artist:: [[Imagination]] ]
[Genre:: Pop]
[Played:: 2]
[Album:: [[Pure Disco (1981)]]]
[Year:: 1981]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Flashback]]
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
		intensity: page["Flashback"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
