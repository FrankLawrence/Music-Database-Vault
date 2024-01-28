---
tags: Song ⭐⭐⭐ 
banner: "![[Heile Welt (1978).jpg]]"
---
[Time:: 2:46]
[Artist:: [[Loriot]] ]
[Genre:: Spoken & Audio]
[Played:: 2]
[Album:: [[Heile Welt (1978)]]]
[Year:: 1978]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Kleinsparer]]
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
		intensity: page["Kleinsparer"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
