---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Innuendo (1977).jpg]]"
---
[Time:: 4:08]
[Artist:: [[Queen]] ]
[Genre:: Rock]
[Played:: 38]
[Album:: [[Innuendo (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I'm Going Slightly Mad]]
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
		intensity: page["I'm_Going_Slightly_Mad"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
