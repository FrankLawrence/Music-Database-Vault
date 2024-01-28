---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Woodstock (2017).jpg]]"
---
[Time:: 4:07]
[Artist:: [[Portugal. The Man]] ]
[Genre:: Pop Rock]
[Played:: 14]
[Album:: [[Woodstock (2017)]]]
[Year:: 2017]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Live in the Moment]]
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
		intensity: page["Live_in_the_Moment"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
