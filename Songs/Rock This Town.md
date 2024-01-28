---
tags: Song  
banner: "![[Stray Cats (1981).jpg]]"
---
[Time:: 3:22]
[Artist:: [[Stray Cats]] ]
[Genre:: Rockabilly]
[Played:: ]
[Album:: [[Stray Cats (1981)]]]
[Year:: 1981]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Rock This Town]]
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
		intensity: page["Rock_This_Town"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
