---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Twentyfive: For Loving [Disc 2] (2006).jpg]]"
---
[Time:: 6:50]
[Artist:: [[George Michael]] ]
[Genre:: Pop]
[Played:: 17]
[Album:: [[Twentyfive: For Loving [Disc 2] (2006)]]]
[Year:: 2006]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Jesus To A Child]]
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
		intensity: page["Jesus_To_A_Child"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
