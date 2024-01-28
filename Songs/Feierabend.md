---
tags: Song ⭐⭐⭐⭐⭐ 💔
banner: "![[Heile Welt (1978).jpg]]"
---
[Time:: 3:15]
[Artist:: [[Loriot]] ]
[Genre:: Spoken & Audio]
[Played:: 4]
[Album:: [[Heile Welt (1978)]]]
[Year:: 1978]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Feierabend]]
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
		intensity: page["Feierabend"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
