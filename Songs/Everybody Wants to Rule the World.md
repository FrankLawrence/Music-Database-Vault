---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Songs from the Big Chair (1985).jpg]]"
---
[Time:: 4:13]
[Artist:: [[Tears For Fears]] ]
[Genre:: Synth-Pop]
[Played:: 161]
[Album:: [[Songs from the Big Chair (1985)]]]
[Year:: 1985]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Everybody Wants to Rule the World]]
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
		intensity: page["Everybody_Wants_to_Rule_the_World"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
