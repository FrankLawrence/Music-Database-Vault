---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[The Wall (1979).jpg]]"
---
[Time:: 1:27]
[Artist:: [[Pink Floyd]] ]
[Genre:: Progressive Rock]
[Played:: 18]
[Album:: [[The Wall (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Bring the Boys Back Home]]
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
		intensity: page["Bring_the_Boys_Back_Home"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
