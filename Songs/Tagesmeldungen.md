---
tags: Song ⭐⭐⭐⭐⭐ 💔
banner: "![[Heile Welt (1988).jpg]]"
---
[Time:: 1:26]
[Artist:: [[Loriot]] ]
[Genre:: Spoken & Audio]
[Played:: 5]
[Album:: [[Heile Welt (1988)]]]
[Year:: 1988]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Tagesmeldungen]]
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
		intensity: page["Tagesmeldungen"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
