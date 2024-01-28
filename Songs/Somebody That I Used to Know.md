---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Making Mirrors (2011).jpg]]"
---
[Time:: 4:04]
[Artist:: [[Gotye]] ]
[Genre:: Art pop]
[Played:: 3]
[Album:: [[Making Mirrors (2011)]]]
[Year:: 2011]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Somebody That I Used to Know]]
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
		intensity: page["Somebody_That_I_Used_to_Know"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
