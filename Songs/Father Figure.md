---
tags: Song ⭐⭐⭐ 
banner: "![[Twentyfive: For Loving [Disc 2] (1987).jpg]]"
---
[Time:: 5:41]
[Artist:: [[George Michael]] ]
[Genre:: Pop]
[Played:: 8]
[Album:: [[Twentyfive: For Loving [Disc 2] (1987)]]]
[Year:: 1987]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Father Figure]]
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
		intensity: page["Father_Figure"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
