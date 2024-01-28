---
tags: Song ⭐ 
banner: "![[The Very Best Of Smooth Jazz [Disc 1] (1963).jpg]]"
---
[Time:: 5:11]
[Artist:: [[Astrud Gilberto]] ]
[Genre:: Jazz]
[Played:: ]
[Album:: [[The Very Best Of Smooth Jazz [Disc 1] (1963)]]]
[Year:: 1963]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[The Girl From Ipanema]]
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
		intensity: page["The_Girl_From_Ipanema"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
