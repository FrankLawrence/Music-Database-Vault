---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Hunting High and Low (1985).jpg]]"
---
[Time:: 4:39]
[Artist:: [[A-ha]] ]
[Genre:: Synth-Pop]
[Played:: 3]
[Album:: [[Hunting High and Low (1985)]]]
[Year:: 1985]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[The Sun Always Shines on T.V.]]
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
		intensity: page["The_Sun_Always_Shines_on_T.V."]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
