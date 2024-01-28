---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Jazz (1997).jpg]]"
---
[Time:: 4:50]
[Artist:: [[Candy Dulfer]] ]
[Genre:: Jazz]
[Played:: 4]
[Album:: [[Jazz (1997)]]]
[Year:: 1997]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[For The Love Of You]]
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
		intensity: page["For_The_Love_Of_You"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
