---
tags: Song ⭐ 💔
banner: "![[Heile Welt (1978).jpg]]"
---
[Time:: 2:21]
[Artist:: [[Loriot]] ]
[Genre:: Spoken & Audio]
[Played:: ]
[Album:: [[Heile Welt (1978)]]]
[Year:: 1978]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Mondbewohner]]
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
		intensity: page["Mondbewohner"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
