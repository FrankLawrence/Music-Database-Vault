---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Everyday Life (2019).jpg]]"
---
[Time:: 5:42]
[Artist:: [[Coldplay]] ]
[Genre:: Pop Rock]
[Played:: 7]
[Album:: [[Everyday Life (2019)]]]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Arabesque]]
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
		intensity: page["Arabesque"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
