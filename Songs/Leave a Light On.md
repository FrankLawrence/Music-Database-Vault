---
tags: Song ⭐⭐⭐⭐ 
banner: "![[What a Time to Be Alive (2017).jpg]]"
---
[Time:: 3:08]
[Artist:: [[Tom Walker]] ]
[Genre:: ]
[Played:: 12]
[Album:: [[What a Time to Be Alive (2017)]]]
[Year:: 2017]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Leave a Light On]]
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
		intensity: page["Leave_a_Light_On"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
