---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Beggars Banquet (2007).jpg]]"
---
[Time:: 6:19]
[Artist:: [[The Rolling Stones]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[Beggars Banquet (2007)]]]
[Year:: 2007]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Sympathy For The Devil]]
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
		intensity: page["Sympathy_For_The_Devil"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
