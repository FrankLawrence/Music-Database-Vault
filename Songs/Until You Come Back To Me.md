---
tags: Song ⭐⭐ 
banner: "![[The Very Best Of Smooth Jazz [Disc 1] (2000).jpg]]"
---
[Time:: 3:08]
[Artist:: [[Hil St. Soul]] ]
[Genre:: Jazz]
[Played:: 1]
[Album:: [[The Very Best Of Smooth Jazz [Disc 1] (2000)]]]
[Year:: 2000]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Until You Come Back To Me]]
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
		intensity: page["Until_You_Come_Back_To_Me"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
