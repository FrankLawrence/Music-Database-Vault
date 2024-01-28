---
tags: Song ⭐⭐⭐ 
banner: "![[Twentyfive: For Loving [Disc 2] (1990).jpg]]"
---
[Time:: 4:42]
[Artist:: [[George Michael]] ]
[Genre:: Pop]
[Played:: 4]
[Album:: [[Twentyfive: For Loving [Disc 2] (1990)]]]
[Year:: 1990]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Praying For Time]]
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
		intensity: page["Praying_For_Time"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
