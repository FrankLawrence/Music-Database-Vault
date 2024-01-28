---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Dawn FM (2020).jpg]]"
---
[Time:: 3:45]
[Artist:: [[The Weeknd]] ]
[Genre:: Disco]
[Played:: 54]
[Album:: [[Dawn FM (2020)]]]
[Year:: 2020]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Take My Breath]]
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
		intensity: page["Take_My_Breath"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
