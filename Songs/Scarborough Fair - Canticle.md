---
tags: Song  
banner: "![[Parsley, Sage, Rosemary And Thyme (1968).jpg]]"
---
[Time:: 6:22]
[Artist:: [[Simon & Garfunkel]] ]
[Genre:: Rock]
[Played:: 5]
[Album:: [[Parsley, Sage, Rosemary And Thyme (1968)]]]
[Year:: 1968]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Scarborough Fair - Canticle]]
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
		intensity: page["Scarborough_Fair_-_Canticle"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
