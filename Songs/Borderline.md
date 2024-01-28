---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[The Slow Rush (2020).jpg]]"
---
[Time:: 3:58]
[Artist:: [[Tame Impala]] ]
[Genre:: Electronic, Rock, Pop]
[Played:: 107]
[Album:: [[The Slow Rush (2020)]]]
[Year:: 2020]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Borderline]]
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
		intensity: page["Borderline"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
