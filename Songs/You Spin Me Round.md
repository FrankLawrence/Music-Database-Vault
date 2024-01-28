---
tags: Song ⭐⭐⭐ 
banner: "![[Youthquake (1984).jpg]]"
---
[Time:: 3:17]
[Artist:: [[Dead or Alive]] ]
[Genre:: Synth-Pop]
[Played:: 2]
[Album:: [[Youthquake (1984)]]]
[Year:: 1984]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[You Spin Me Round]]
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
		intensity: page["You_Spin_Me_Round"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
