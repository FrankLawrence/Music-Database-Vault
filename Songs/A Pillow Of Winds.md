---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Meddle (1971).jpg]]"
---
[Time:: 5:13]
[Artist:: [[Pink Floyd]] ]
[Genre:: Progressive Rock]
[Played:: 82]
[Album:: [[Meddle (1971)]]]
[Year:: 1971]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[A Pillow Of Winds]]
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
		intensity: page["A_Pillow_Of_Winds"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
