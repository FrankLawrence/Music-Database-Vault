---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Listen Without Prejudice Vol. 1 (2006).jpg]]"
---
[Time:: 4:44]
[Artist:: [[Paul McCartney & George Michael]] ]
[Genre:: Pop]
[Played:: 49]
[Album:: [[Listen Without Prejudice Vol. 1 (2006)]]]
[Year:: 2006]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Heal The Pain]]
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
		intensity: page["Heal_The_Pain"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
