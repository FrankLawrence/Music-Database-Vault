---
tags: Song ⭐⭐⭐⭐ 
banner: "![[The John Lennon Collection (1975).jpg]]"
---
[Time:: 3:28]
[Artist:: [[John Lennon]] ]
[Genre:: Rock]
[Played:: 2]
[Album:: [[The John Lennon Collection (1975)]]]
[Year:: 1975]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Stand By Me]]
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
		intensity: page["Stand_By_Me"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
