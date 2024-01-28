---
tags: Song ⭐⭐ 
banner: "![[My Generation - The Very Best Of The Who (1971).jpg]]"
---
[Time:: 5:09]
[Artist:: [[The Who]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[My Generation - The Very Best Of The Who (1971)]]]
[Year:: 1971]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Baba O'Riley]]
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
		intensity: page["Baba_O'Riley"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
