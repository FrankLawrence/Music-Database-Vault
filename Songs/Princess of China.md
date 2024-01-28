---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Mylo Xyloto (2011).jpg]]"
---
[Time:: 3:59]
[Artist:: [[Coldplay]] [[Rihanna]] ]
[Genre:: Pop]
[Played:: 24]
[Album:: [[Mylo Xyloto (2011)]]]
[Year:: 2011]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Princess of China]]
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
		intensity: page["Princess_of_China"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
