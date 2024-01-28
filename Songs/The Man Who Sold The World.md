---
tags: Song  
banner: "![[Best Of Bowie (2002).jpg]]"
---
[Time:: 3:58]
[Artist:: [[David Bowie]] ]
[Genre:: Rock]
[Played:: 1]
[Album:: [[Best Of Bowie (2002)]]]
[Year:: 2002]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[The Man Who Sold The World]]
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
		intensity: page["The_Man_Who_Sold_The_World"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
