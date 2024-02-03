---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Toto (1978).jpg]]"
---
[Time:: 4:08]
[Artist:: [[Toto]] ]
[Genre:: Soft Rock]
[Played:: 45]
[Album:: [[Toto (1978)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Georgy Porgy]]
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
		intensity: page["Georgy_Porgy"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
