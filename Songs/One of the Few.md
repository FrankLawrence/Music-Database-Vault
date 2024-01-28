---
tags: Song ⭐⭐⭐ 
banner: "![[The Final Cut (1983).jpg]]"
---
[Time:: 1:14]
[Artist:: [[Pink Floyd]] ]
[Genre:: Art rock]
[Played:: 12]
[Album:: [[The Final Cut (1983)]]]
[Year:: 1983]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[One of the Few]]
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
		intensity: page["One_of_the_Few"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
