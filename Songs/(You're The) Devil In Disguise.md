---
tags: Song ⭐ 💔
banner: "![[30 #1 Hits (1963).jpg]]"
---
[Time:: 2:22]
[Artist:: [[Elvis Presley]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[30 #1 Hits (1963)]]]
[Year:: 1963]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[(You're The) Devil In Disguise]]
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
		intensity: page["(You're_The)_Devil_In_Disguise"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
