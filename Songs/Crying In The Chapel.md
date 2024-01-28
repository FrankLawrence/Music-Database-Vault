---
tags: Song ⭐⭐⭐ 
banner: "![[30 #1 Hits (1965).jpg]]"
---
[Time:: 2:26]
[Artist:: [[Elvis Presley]] ]
[Genre:: Rock]
[Played:: 1]
[Album:: [[30 #1 Hits (1965)]]]
[Year:: 1965]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Crying In The Chapel]]
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
		intensity: page["Crying_In_The_Chapel"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
