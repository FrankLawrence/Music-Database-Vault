---
tags: Song  
banner: "![[Best Of Bowie (1977).jpg]]"
---
[Time:: 3:37]
[Artist:: [[David Bowie]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[Best Of Bowie (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Heroes]]
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
		intensity: page["Heroes"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
