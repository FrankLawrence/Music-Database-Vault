---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[The Papas & The Mamas (1968).jpg]]"
---
[Time:: 3:16]
[Artist:: [[The Mamas & The Papas]] ]
[Genre:: Pop]
[Played:: 2]
[Album:: [[The Papas & The Mamas (1968)]]]
[Year:: 1968]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Dream a Little Dream of Me]]
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
		intensity: page["Dream_a_Little_Dream_of_Me"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
