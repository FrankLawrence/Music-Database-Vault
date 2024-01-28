---
tags: Song  
banner: "![[Best Of Bowie (2002).jpg]]"
---
[Time:: 4:46]
[Artist:: [[David Bowie]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[Best Of Bowie (2002)]]]
[Year:: 2002]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Loving The Alien]]
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
		intensity: page["Loving_The_Alien"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
