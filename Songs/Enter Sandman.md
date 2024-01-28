---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Metallica (1991).jpg]]"
---
[Time:: 5:31]
[Artist:: [[Metallica]] ]
[Genre:: Heavy metal]
[Played:: 39]
[Album:: [[Metallica (1991)]]]
[Year:: 1991]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Enter Sandman]]
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
		intensity: page["Enter_Sandman"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
