---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Overloaded - The Singles Collection (2006).jpg]]"
---
[Time:: 3:40]
[Artist:: [[Sugababes]] ]
[Genre:: Electronic, Hip Hop, Rock, Pop]
[Played:: 1]
[Album:: [[Overloaded - The Singles Collection (2006)]]]
[Year:: 2006]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Hole In The Head]]
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
		intensity: page["Hole_In_The_Head"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
