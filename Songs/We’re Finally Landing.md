---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Before The Night (2014).jpg]]"
---
[Time:: 4:32]
[Artist:: [[HOME]] ]
[Genre:: Instrumental]
[Played:: 19]
[Album:: [[Before The Night (2014)]]]
[Year:: 2014]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[We’re Finally Landing]]
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
		intensity: page["We’re_Finally_Landing"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
