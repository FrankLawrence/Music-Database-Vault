---
tags: Song ⭐⭐⭐⭐ 
banner: "![[30 #1 Hits (1957).jpg]]"
---
[Time:: 2:37]
[Artist:: [[Elvis Presley]] ]
[Genre:: Rock]
[Played:: 2]
[Album:: [[30 #1 Hits (1957)]]]
[Year:: 1957]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Jailhouse Rock]]
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
		intensity: page["Jailhouse_Rock"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
