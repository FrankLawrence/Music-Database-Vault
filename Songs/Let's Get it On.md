---
tags: Song ⭐⭐⭐ 
banner: "![[Let's get it on (1973).jpg]]"
---
[Time:: 4:51]
[Artist:: [[Marvin Gaye]] ]
[Genre:: Soul]
[Played:: ]
[Album:: [[Let's get it on (1973)]]]
[Year:: 1973]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Let's Get it On]]
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
		intensity: page["Let's_Get_it_On"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
