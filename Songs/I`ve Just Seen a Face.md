---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Help! (1965).jpg]]"
---
[Time:: 2:07]
[Artist:: [[The Beatles]] ]
[Genre:: Rock]
[Played:: 1]
[Album:: [[Help! (1965)]]]
[Year:: 1965]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I`ve Just Seen a Face]]
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
		intensity: page["I`ve_Just_Seen_a_Face"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
