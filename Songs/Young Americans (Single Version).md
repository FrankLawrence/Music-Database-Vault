---
tags: Song  
banner: "![[Best Of Bowie (1975).jpg]]"
---
[Time:: 3:15]
[Artist:: [[David Bowie]] ]
[Genre:: Rock]
[Played:: 1]
[Album:: [[Best Of Bowie (1975)]]]
[Year:: 1975]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Young Americans (Single Version)]]
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
		intensity: page["Young_Americans_(Single_Version)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
