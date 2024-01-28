---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Animals (1977).jpg]]"
---
[Time:: 10:19]
[Artist:: [[Pink Floyd]] ]
[Genre:: Progressive Rock]
[Played:: 40]
[Album:: [[Animals (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Sheep]]
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
		intensity: page["Sheep"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
