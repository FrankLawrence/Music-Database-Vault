---
tags: Song ⭐⭐⭐⭐ 
banner: "![[KC And The Sunshine Band (1975).jpg]]"
---
[Time:: 3:13]
[Artist:: [[K.C. & The Sunshine Band]] ]
[Genre:: Disco]
[Played:: 3]
[Album:: [[KC And The Sunshine Band (1975)]]]
[Year:: 1975]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Get Down Tonight]]
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
		intensity: page["Get_Down_Tonight"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
