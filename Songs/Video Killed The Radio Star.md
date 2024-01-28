---
tags: Song  
banner: "![[The Age of Plastic (1979).jpg]]"
---
[Time:: 3:15]
[Artist:: [[The Buggles]] ]
[Genre:: New Wave]
[Played:: 1]
[Album:: [[The Age of Plastic (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Video Killed The Radio Star]]
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
		intensity: page["Video_Killed_The_Radio_Star"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
