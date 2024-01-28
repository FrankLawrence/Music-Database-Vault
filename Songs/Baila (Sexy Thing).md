---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Shake (2001).jpg]]"
---
[Time:: 4:10]
[Artist:: [[Zucchero]] ]
[Genre:: Rock/Pop]
[Played:: 2]
[Album:: [[Shake (2001)]]]
[Year:: 2001]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Baila (Sexy Thing)]]
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
		intensity: page["Baila_(Sexy_Thing)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
