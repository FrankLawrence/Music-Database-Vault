---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Let's Love (2020).jpg]]"
---
[Time:: 3:33]
[Artist:: [[David Guetta]] [[Sia]] ]
[Genre:: Synth-Pop]
[Played:: 32]
[Album:: [[Let's Love (2020)]]]
[Year:: 2020]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Let's love]]
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
		intensity: page["Let's_love"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
