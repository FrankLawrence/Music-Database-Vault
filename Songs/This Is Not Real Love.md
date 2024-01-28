---
tags: Song  
banner: "![[Twenty Five (2006).jpg]]"
---
[Time:: 4:57]
[Artist:: [[George Michael]] [[Mutya]] ]
[Genre:: Pop]
[Played:: 5]
[Album:: [[Twentyfive (2006)]]]
[Year:: 2006]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[This Is Not Real Love]]
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
		intensity: page["This_Is_Not_Real_Love"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
