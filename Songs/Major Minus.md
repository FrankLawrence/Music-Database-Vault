---
tags: Song  
banner: "![[Mylo Xyloto (2011).jpg]]"
---
[Time:: 3:30]
[Artist:: [[Coldplay]] ]
[Genre:: Pop]
[Played:: 2]
[Album:: [[Mylo Xyloto (2011)]]]
[Year:: 2011]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Major Minus]]
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
		intensity: page["Major_Minus"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
