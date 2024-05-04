---
tags: Song ⭐⭐⭐ 
banner: "![[Everyday Life (2019).jpg]]"
---
[Time:: 4:20]
[Artist:: [[Coldplay]] ]
[Genre:: Pop Rock]
[Played:: 9]
[Album:: [[Everyday Life (2019)]]]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Everyday Life]]
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
		intensity: page["Everyday_Life"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
