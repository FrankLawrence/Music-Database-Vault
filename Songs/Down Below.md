---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Feed Tha Streets II (2018).jpg]]"
---
[Time:: 3:44]
[Artist:: [[Roddy Ricch]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 5]
[Album:: [[Feed Tha Streets II (2018)]]]
[Year:: 2018]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Down Below]]
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
		intensity: page["Down_Below"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
