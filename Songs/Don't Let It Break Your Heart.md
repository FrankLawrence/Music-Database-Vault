---
tags: Song  
banner: "![[Mylo Xyloto (2011).jpg]]"
---
[Time:: 3:54]
[Artist:: [[Coldplay]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[Mylo Xyloto (2011)]]]
[Year:: 2011]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Don't Let It Break Your Heart]]
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
		intensity: page["Don't_Let_It_Break_Your_Heart"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
