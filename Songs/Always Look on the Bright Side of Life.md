---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Monty Python's Life of Brian (1979).jpg]]"
---
[Time:: 3:38]
[Artist:: [[Monty Python]] ]
[Genre:: Comedy Music]
[Played:: 10]
[Album:: [[Monty Python's Life of Brian (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Always Look on the Bright Side of Life]]
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
		intensity: page["Always_Look_on_the_Bright_Side_of_Life"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
