---
tags: Song ⭐ 💔
banner: "![[Heile Welt (1978).jpg]]"
---
[Time:: 2:28]
[Artist:: [[Loriot]] ]
[Genre:: Spoken & Audio]
[Played:: ]
[Album:: [[Heile Welt (1978)]]]
[Year:: 1978]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Der Vampyr]]
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
		intensity: page["Der_Vampyr"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
