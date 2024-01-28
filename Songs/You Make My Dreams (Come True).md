---
tags: Song ⭐⭐⭐ 
banner: "![[Voices (1981).jpg]]"
---
[Time:: 3:11]
[Artist:: [[Daryl an Oates]] ]
[Genre:: Yacht rock]
[Played:: 1]
[Album:: [[Voices (1981)]]]
[Year:: 1981]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[You Make My Dreams (Come True)]]
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
		intensity: page["You_Make_My_Dreams_(Come_True)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
