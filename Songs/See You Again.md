---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Flower Boy (2017).jpg]]"
---
[Time:: 3:23]
[Artist:: [[Tyler, the Creator]] [[Kali Uchis]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 83]
[Album:: [[Flower Boy (2017)]]]
[Year:: 2017]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[See You Again]]
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
		intensity: page["See_You_Again"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
