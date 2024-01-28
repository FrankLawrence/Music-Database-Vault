---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[The Very Best Of Smooth Jazz [Disc 1] (1999).jpg]]"
---
[Time:: 5:25]
[Artist:: [[David Benoit]] ]
[Genre:: Jazz]
[Played:: 43]
[Album:: [[The Very Best Of Smooth Jazz [Disc 1] (1999)]]]
[Year:: 1999]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Miles After Dark]]
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
		intensity: page["Miles_After_Dark"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
