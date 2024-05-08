---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Sacred Hearts Club (2017).jpg]]"
---
[Time:: 4:05]
[Artist:: [[Foster the People]] ]
[Genre:: Indie pop]
[Played:: 27]
[Album:: [[Sacred Hearts Club (2017)]]]
[Year:: 2017]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Sit Next to Me]]
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
		intensity: page["Sit_Next_to_Me"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
