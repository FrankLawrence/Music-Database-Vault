---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Scoundrel Days (1986).jpg]]"
---
[Time:: 4:16]
[Artist:: [[a-ha]] ]
[Genre:: Electronic, Rock, Pop]
[Played:: 30]
[Album:: [[Scoundrel Days (1986)]]]
[Year:: 1986]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Manhattan Skyline]]
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
		intensity: page["Manhattan_Skyline"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
