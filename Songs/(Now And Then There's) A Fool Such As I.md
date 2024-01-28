---
tags: Song ⭐⭐⭐ 
banner: "![[30 #1 Hits (1959).jpg]]"
---
[Time:: 2:42]
[Artist:: [[Elvis Presley]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[30 #1 Hits (1959)]]]
[Year:: 1959]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[(Now And Then There's) A Fool Such As I]]
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
		intensity: page["(Now_And_Then_There's)_A_Fool_Such_As_I"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
