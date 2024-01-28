---
tags: Song ⭐⭐⭐⭐ 💛
banner: "![[American Gigolo (1980).jpg]]"
---
[Time:: 2:15]
[Artist:: [[Blondie]] ]
[Genre:: New Wave]
[Played:: 14]
[Album:: [[American Gigolo (1980)]]]
[Year:: 1980]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Call Me]]
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
		intensity: page["Call_Me"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
