---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[America (1972).jpg]]"
---
[Time:: 4:08]
[Artist:: [[America (2)]] ]
[Genre:: Rock]
[Played:: 11]
[Album:: [[America (1972)]]]
[Year:: 1972]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[A Horse With No Name]]
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
		intensity: page["A_Horse_With_No_Name"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
