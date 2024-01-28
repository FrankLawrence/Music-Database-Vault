---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Wish You Were Here (1975).jpg]]"
---
[Time:: 5:08]
[Artist:: [[Pink Floyd]] [[Roy Harper]] ]
[Genre:: Progressive Rock]
[Played:: 36]
[Album:: [[Wish You Were Here (1975)]]]
[Year:: 1975]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Have A Cigar]]
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
		intensity: page["Have_A_Cigar"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
