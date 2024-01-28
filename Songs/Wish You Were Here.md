---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Wish You Were Here (1975).jpg]]"
---
[Time:: 5:40]
[Artist:: [[Pink Floyd]] ]
[Genre:: Pop]
[Played:: 9]
[Album:: [[Wish You Were Here (1975)]]]
[Year:: 1975]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Wish You Were Here]]
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
		intensity: page["Wish_You_Were_Here"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
