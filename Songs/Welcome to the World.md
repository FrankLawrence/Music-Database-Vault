---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Plastic Beach (2010).jpg]]"
---
[Time:: 3:35]
[Artist:: [[Gorillaz]] [[Snoop Dogg]] ]
[Genre:: Pop]
[Played:: 79]
[Album:: [[Plastic Beach (2010)]]]
[Year:: 2010]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Welcome to the World]]
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
		intensity: page["Welcome_to_the_World"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
