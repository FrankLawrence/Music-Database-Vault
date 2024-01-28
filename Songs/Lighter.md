---
tags: Song ⭐⭐⭐ 
banner: "![[Lighter (2020).jpg]]"
---
[Time:: 4:30]
[Artist:: [[Nathan Dawe (feat. KSI)]] ]
[Genre:: House]
[Played:: 1]
[Album:: [[Lighter (2020)]]]
[Year:: 2020]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Lighter]]
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
		intensity: page["Lighter"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
