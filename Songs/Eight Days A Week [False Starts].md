---
tags: Song  
banner: "![[Anthology 1 [Disc 2] (1964).jpg]]"
---
[Time:: 1:25]
[Artist:: [[The Beatles]] ]
[Genre:: Rock]
[Played:: 2]
[Album:: [[Anthology 1 [Disc 2] (1964)]]]
[Year:: 1964]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Eight Days A Week [False Starts]]]
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
		intensity: page["Eight_Days_A_Week_[False_Starts]"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
