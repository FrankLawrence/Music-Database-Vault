---
tags: Song ⭐⭐⭐ 
banner: "![[IGOR (2019).jpg]]"
---
[Time:: 6:15]
[Artist:: [[Tyler, the Creator]] ]
[Genre:: Hip-Hop Rap]
[Played:: 25]
[Album:: [[IGOR (2019)]]]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[GONE, GONE - THANK YOU]]
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
		intensity: page["GONE,_GONE_-_THANK_YOU"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
