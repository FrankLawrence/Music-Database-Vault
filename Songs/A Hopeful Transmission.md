---
tags: Song ⭐ 
banner: "![[Mylo Xyloto (2011).jpg]]"
---
[Time:: 0:33]
[Artist:: [[Coldplay]] ]
[Genre:: Pop]
[Played:: 2]
[Album:: [[Mylo Xyloto (2011)]]]
[Year:: 2011]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[A Hopeful Transmission]]
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
		intensity: page["A_Hopeful_Transmission"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
