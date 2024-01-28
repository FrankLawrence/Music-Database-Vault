---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[IHY2LN + Marinate (2020).jpg]]"
---
[Time:: 5:53]
[Artist:: [[Zack Fox]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 27]
[Album:: [[IHY2LN + Marinate (2020)]]]
[Year:: 2020]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[IHY2LN]]
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
		intensity: page["IHY2LN"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
