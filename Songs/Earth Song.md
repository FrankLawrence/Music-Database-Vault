---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[HIStory: Past, Present and Future, Book I (1995).jpg]]"
---
[Time:: 6:45]
[Artist:: [[Michael Jackson]] ]
[Genre:: Blues]
[Played:: 19]
[Album:: [[HIStory: Past, Present and Future, Book I (1995)]]]
[Year:: 1995]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Earth Song]]
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
		intensity: page["Earth_Song"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
