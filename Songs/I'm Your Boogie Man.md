---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Part 3 (1977).jpg]]"
---
[Time:: 4:03]
[Artist:: [[K.C. & The Sunshine Band]] ]
[Genre:: Pop]
[Played:: 3]
[Album:: [[Part 3 (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I'm Your Boogie Man]]
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
		intensity: page["I'm_Your_Boogie_Man"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
