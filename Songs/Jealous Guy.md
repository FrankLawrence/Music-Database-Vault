---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[The John Lennon Collection (1971).jpg]]"
---
[Time:: 4:18]
[Artist:: [[John Lennon]] ]
[Genre:: Rock]
[Played:: 29]
[Album:: [[The John Lennon Collection (1971)]]]
[Year:: 1971]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Jealous Guy]]
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
		intensity: page["Jealous_Guy"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
