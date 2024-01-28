---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Dschinghis Khan (1979).jpg]]"
---
[Time:: 4:29]
[Artist:: [[Dschinghis Khan]] ]
[Genre:: Disco]
[Played:: 6]
[Album:: [[Dschinghis Khan (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Moskau 1979]]
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
		intensity: page["Moskau_1979"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
