---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Faith (1987).jpg]]"
---
[Time:: 5:53]
[Artist:: [[George Michael]] ]
[Genre:: Electronic, Rock, Funk / Soul, Pop]
[Played:: 42]
[Album:: [[Faith (1987)]]]
[Year:: 1987]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[One More Try]]
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
		intensity: page["One_More_Try"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
