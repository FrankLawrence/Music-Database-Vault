---
tags: Song ⭐⭐⭐ 
banner: "![[Armageddon: The Album (1998).jpg]]"
---
[Time:: 4:59]
[Artist:: [[Aerosmith]] ]
[Genre:: Hard Rock]
[Played:: 2]
[Album:: [[Armageddon: The Album (1998)]]]
[Year:: 1998]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I Don't Want to Miss a Thing]]
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
		intensity: page["I_Don't_Want_to_Miss_a_Thing"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
