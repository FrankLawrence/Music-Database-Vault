---
tags: Song  
banner: "![[December's Children (2007).jpg]]"
---
[Time:: 2:46]
[Artist:: [[The Rolling Stones]] ]
[Genre:: Rock]
[Played:: 2]
[Album:: [[December's Children (2007)]]]
[Year:: 2007]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[As Tears Go By]]
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
		intensity: page["As_Tears_Go_By"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
