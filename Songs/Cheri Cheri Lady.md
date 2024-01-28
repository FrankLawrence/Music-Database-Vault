---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Let's Talk About Love (1985).jpg]]"
---
[Time:: 3:17]
[Artist:: [[Modern Talking]] ]
[Genre:: Dance-pop]
[Played:: 26]
[Album:: [[Let's Talk About Love (1985)]]]
[Year:: 1985]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Cheri Cheri Lady]]
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
		intensity: page["Cheri_Cheri_Lady"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
