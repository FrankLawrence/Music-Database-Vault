---
tags: Song ⭐⭐ 
banner: "![[Plastic Beach (2010).jpg]]"
---
[Time:: 3:44]
[Artist:: [[Gorillaz]] [[Bashy & Kano]] ]
[Genre:: Pop]
[Played:: 2]
[Album:: [[Plastic Beach (2010)]]]
[Year:: 2010]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[White Flag]]
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
		intensity: page["white_flag"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
