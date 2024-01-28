---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Backsteet's Back (1997).jpg]]"
---
[Time:: 4:07]
[Artist:: [[Backstreet Boys]] ]
[Genre:: Dance-pop]
[Played:: 3]
[Album:: [[Backsteet's Back (1997)]]]
[Year:: 1997]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Everybody (Backstreet's Back)]]
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
		intensity: page["Everybody_(Backstreet's_Back)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
