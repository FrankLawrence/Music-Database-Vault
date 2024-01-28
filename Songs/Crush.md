---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[The Very Best Of Smooth Jazz [Disc 1] (2001).jpg]]"
---
[Time:: 3:29]
[Artist:: [[Richard Elliot]] ]
[Genre:: Jazz]
[Played:: 43]
[Album:: [[The Very Best Of Smooth Jazz [Disc 1] (2001)]]]
[Year:: 2001]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Crush]]
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
		intensity: page["Crush"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
