---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Magical Mystery Tour (1967).jpg]]"
---
[Time:: 4:36]
[Artist:: [[The Beatles]] ]
[Genre:: ]
[Played:: 2]
[Album:: [[Magical Mystery Tour (1967)]]]
[Year:: 1967]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I Am The Walrus]]
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
		intensity: page["I_Am_The_Walrus"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
