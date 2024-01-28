---
tags: Song  
banner: "![[The Very Best Of Smooth Jazz [Disc 1] (1954).jpg]]"
---
[Time:: 2:39]
[Artist:: [[Sarah Vaughan]] ]
[Genre:: Jazz]
[Played:: ]
[Album:: [[The Very Best Of Smooth Jazz [Disc 1] (1954)]]]
[Year:: 1954]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Make Yourself Comfortable]]
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
		intensity: page["Make_Yourself_Comfortable"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
