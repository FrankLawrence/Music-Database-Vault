---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Plastic Beach (2010).jpg]]"
---
[Time:: 4:33]
[Artist:: [[Gorillaz]] [[Mos Def & Bobby Womack]] ]
[Genre:: Synth-Pop]
[Played:: 3]
[Album:: [[Plastic Beach (2010)]]]
[Year:: 2010]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Stylo]]
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
		intensity: page["Stylo"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
