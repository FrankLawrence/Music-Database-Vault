---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Payback (2017).jpg]]"
---
[Time:: 4:04]
[Artist:: [[Aftermarket & Max Adrian]] ]
[Genre:: Electro House]
[Played:: 4]
[Album:: [[Payback (2017)]]]
[Year:: 2017]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Payback (Original Mix)]]
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
		intensity: page["Payback_(Original_Mix)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
