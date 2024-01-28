---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[The Division Bell (1994).jpg]]"
---
[Time:: 4:22]
[Artist:: [[Pink Floyd]] ]
[Genre:: Progressive Rock]
[Played:: 52]
[Album:: [[The Division Bell (1994)]]]
[Year:: 1994]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[What Do You Want From Me]]
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
		intensity: page["What_Do_You_Want_From_Me"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
