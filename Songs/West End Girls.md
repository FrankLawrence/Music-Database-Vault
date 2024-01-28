---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Please (1984).jpg]]"
---
[Time:: 3:54]
[Artist:: [[Pet Shop Boys]] ]
[Genre:: Synth-Pop]
[Played:: 31]
[Album:: [[Please (1984)]]]
[Year:: 1984]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[West End Girls]]
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
		intensity: page["West_End_Girls"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
