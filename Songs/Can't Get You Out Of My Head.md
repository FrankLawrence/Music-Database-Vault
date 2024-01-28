---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Ultimate Kylie [Disc 2] (2001).jpg]]"
---
[Time:: 3:51]
[Artist:: [[Kylie Minogue]] ]
[Genre:: Pop]
[Played:: 2]
[Album:: [[Ultimate Kylie [Disc 2] (2001)]]]
[Year:: 2001]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Can't Get You Out Of My Head]]
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
		intensity: page["Can't_Get_You_Out_Of_My_Head"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
