---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Plastic Beach (2010).jpg]]"
---
[Time:: 3:10]
[Artist:: [[Gorillaz]] [[Gruff Rhys & De La Soul]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 15]
[Album:: [[Plastic Beach (2010)]]]
[Year:: 2010]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Superfast Jellyfish]]
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
		intensity: page["Superfast_Jellyfish"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
