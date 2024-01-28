---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Love At First Sting (1984).jpg]]"
---
[Time:: 4:13]
[Artist:: [[Scorpions]] ]
[Genre:: Metal]
[Played:: 3]
[Album:: [[Love At First Sting (1984)]]]
[Year:: 1984]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Rock You Like A Hurricane]]
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
		intensity: page["Rock_You_Like_A_Hurricane"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
