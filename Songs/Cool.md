---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[I (2018).jpg]]"
---
[Time:: 3:11]
[Artist:: [[Felix Jaehn]] [[Marc E. Bassy]] [[Gucci Mane]] ]
[Genre:: Dance]
[Played:: 20]
[Album:: [[I (2018)]]]
[Year:: 2018]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Cool]]
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
		intensity: page["Cool"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
