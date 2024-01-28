---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[With The Beatles (1963).jpg]]"
---
[Time:: 2:14]
[Artist:: [[The Beatles]] ]
[Genre:: Rock]
[Played:: 1]
[Album:: [[With The Beatles (1963)]]]
[Year:: 1963]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[It Won't Be Long]]
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
		intensity: page["It_Won't_Be_Long"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
