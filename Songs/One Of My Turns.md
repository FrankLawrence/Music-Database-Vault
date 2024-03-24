---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[The Wall (1979).jpg]]"
---
[Time:: 3:37]
[Artist:: [[Pink Floyd]] ]
[Genre:: Progressive Rock]
[Played:: 36]
[Album:: [[The Wall (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[One Of My Turns]]
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
		intensity: page["One_Of_My_Turns"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
