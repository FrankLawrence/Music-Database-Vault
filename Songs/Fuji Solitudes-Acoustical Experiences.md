---
tags: Song  
banner: "![[Fuji Solitudes - Acoustical Experiences (1986).jpg]]"
---
[Time:: 47:01]
[Artist:: [[Solitudes]] ]
[Genre:: ]
[Played:: ]
[Album:: [[Fuji Solitudes - Acoustical Experiences (1986)]]]
[Year:: 1986]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Fuji Solitudes-Acoustical Experiences]]
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
		intensity: page["Fuji_Solitudes-Acoustical_Experiences"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
