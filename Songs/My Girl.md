---
tags: Song  
banner: "![[The Very Best Of Smooth Jazz [Disc 1] (1964).jpg]]"
---
[Time:: 2:40]
[Artist:: [[The Temptations]] ]
[Genre:: Jazz]
[Played:: 3]
[Album:: [[The Very Best Of Smooth Jazz [Disc 1] (1964)]]]
[Year:: 1964]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[My Girl]]
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
		intensity: page["My_Girl"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
