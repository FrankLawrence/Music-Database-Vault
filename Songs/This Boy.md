---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Anthology 1 [Disc 2] (1963).jpg]]"
---
[Time:: 2:22]
[Artist:: [[The Beatles]] ]
[Genre:: Rock]
[Played:: 3]
[Album:: [[Anthology 1 [Disc 2] (1963)]]]
[Year:: 1963]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[This Boy]]
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
		intensity: page["This_Boy"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
