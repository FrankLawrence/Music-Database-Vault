---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[The Very Best Of Smooth Jazz [Disc 1] (1971).jpg]]"
---
[Time:: 2:04]
[Artist:: [[Bill Withers]] ]
[Genre:: Jazz]
[Played:: 3]
[Album:: [[The Very Best Of Smooth Jazz [Disc 1] (1971)]]]
[Year:: 1971]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Ain't No Sunshine]]
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
		intensity: page["Ain't_No_Sunshine"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
