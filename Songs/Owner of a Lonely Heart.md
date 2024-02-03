---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[90125 (1983).jpg]]"
---
[Time:: 4:28]
[Artist:: [[Yes]] ]
[Genre:: Dance-rock]
[Played:: 66]
[Album:: [[90125 (1983)]]]
[Year:: 1983]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Owner of a Lonely Heart]]
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
		intensity: page["Owner_of_a_Lonely_Heart"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
