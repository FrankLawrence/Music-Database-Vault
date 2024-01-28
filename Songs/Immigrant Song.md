---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Led Zeppelin III (1970).jpg]]"
---
[Time:: 2:27]
[Artist:: [[Led Zeppelin]] ]
[Genre:: Hard Rock]
[Played:: 27]
[Album:: [[Led Zeppelin III (1970)]]]
[Year:: 1970]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Immigrant Song]]
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
		intensity: page["Immigrant_Song"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
