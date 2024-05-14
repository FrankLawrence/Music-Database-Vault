---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[A Rush of Blood To The Head (2002).jpg]]"
---
[Time:: 4:25]
[Artist:: [[Coldplay]] ]
[Genre:: Alternative Rock]
[Played:: 10]
[Album:: [[A Rush of Blood To The Head (2002)]]]
[Year:: 2002]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[The Scientist]]
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
		intensity: page["The_Scientist"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
