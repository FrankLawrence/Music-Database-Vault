---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Eldorado (1974).jpg]]"
---
[Time:: 4:24]
[Artist:: [[Electric Light Orchestra]] ]
[Genre:: Rock]
[Played:: 6]
[Album:: [[Eldorado (1974)]]]
[Year:: 1974]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Can't Get It Out Of My Head]]
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
		intensity: page["Can't_Get_It_Out_Of_My_Head"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
