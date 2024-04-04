---
tags: Song  
banner: "![[Wahnsinn (1997).jpg]]"
---
[Time:: 5:50]
[Artist:: [[BAP]] ]
[Genre:: German Rock-Pop]
[Played:: ]
[Album:: [[Wahnsinn (1997)]]]
[Year:: 1997]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Alexandra, Nit Nur Do]]
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
		intensity: page["Alexandra,_Nit_Nur_Do"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
