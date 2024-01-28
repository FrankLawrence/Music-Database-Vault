---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Life for rent (2003).jpg]]"
---
[Time:: 3:55]
[Artist:: [[Dido]] ]
[Genre:: Pop]
[Played:: 7]
[Album:: [[Life for rent (2003)]]]
[Year:: 2003]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[do you have a little time]]
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
		intensity: page["do_you_have_a_little_time"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
