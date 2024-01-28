---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Like Drawing Blood (2006).jpg]]"
---
[Time:: 4:40]
[Artist:: [[Gotye]] ]
[Genre:: Indie Rock]
[Played:: 59]
[Album:: [[Like Drawing Blood (2006)]]]
[Year:: 2006]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Hearts A Mess]]
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
		intensity: page["Hearts_A_Mess"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
