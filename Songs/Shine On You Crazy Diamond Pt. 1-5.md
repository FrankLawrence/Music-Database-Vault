---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Wish You Were Here (1975).jpg]]"
---
[Time:: 13:22]
[Artist:: [[Pink Floyd]] ]
[Genre:: Progressive Rock]
[Played:: 100]
[Album:: [[Wish You Were Here (1975)]]]
[Year:: 1975]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Shine On You Crazy Diamond Pt. 1-5]]
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
		intensity: page["Shine_On_You_Crazy_Diamond_Pt._1-5"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
