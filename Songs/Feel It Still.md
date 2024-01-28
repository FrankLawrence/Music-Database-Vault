---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Woodstock (2017).jpg]]"
---
[Time:: 2:43]
[Artist:: [[Portugal. The Man]] ]
[Genre:: Psychedelic Pop]
[Played:: 1]
[Album:: [[Woodstock (2017)]]]
[Year:: 2017]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Feel It Still]]
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
		intensity: page["Feel_It_Still"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
