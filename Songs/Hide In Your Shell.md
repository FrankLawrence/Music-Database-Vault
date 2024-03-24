---
tags: Song  
banner: "![[Crime of the Century (1974).jpg]]"
---
[Time:: 6:16]
[Artist:: [[Supertramp]] ]
[Genre:: Progressive Rock]
[Played:: 3]
[Album:: [[Crime of the Century (1974)]]]
[Year:: 1974]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Hide In Your Shell]]
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
		intensity: page["Hide_In_Your_Shell"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
