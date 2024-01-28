---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Jermaine Jackson (1984).jpg]]"
---
[Time:: 4:10]
[Artist:: [[Jermaine Jackson]] [[Pia Zadora]] ]
[Genre:: Synth-Pop]
[Played:: 30]
[Album:: [[Jermaine Jackson (1984)]]]
[Year:: 1984]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[When the Rain Begins to Fall]]
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
		intensity: page["When_the_Rain_Begins_to_Fall"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
