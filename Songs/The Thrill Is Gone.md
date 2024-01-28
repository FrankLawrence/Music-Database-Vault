---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Completely Well (1969).jpg]]"
---
[Time:: 5:27]
[Artist:: [[B.B. King]] ]
[Genre:: Blues]
[Played:: 50]
[Album:: [[Completely Well (1969)]]]
[Year:: 1969]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[The Thrill Is Gone]]
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
		intensity: page["The_Thrill_Is_Gone"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
