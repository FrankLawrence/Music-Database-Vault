---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Lifetime (2021).jpg]]"
---
[Time:: 3:07]
[Artist:: [[Swedish House Mafia]] ]
[Genre:: Electronic, Hip Hop]
[Played:: 73]
[Album:: [[Lifetime (2021)]]]
[Year:: 2021]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Lifetime]]
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
		intensity: page["Lifetime"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
