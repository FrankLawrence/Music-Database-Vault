---
tags: Song ⭐⭐⭐⭐ 
banner: "![[IGOR (2019).jpg]]"
---
[Time:: 2:41]
[Artist:: [[Tyler, the Creator]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 10]
[Album:: [[IGOR (2019)]]]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I DON'T LOVE YOU ANYMORE]]
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
		intensity: page["I_DON'T_LOVE_YOU_ANYMORE"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
