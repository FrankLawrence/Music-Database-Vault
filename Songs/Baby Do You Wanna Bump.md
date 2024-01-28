---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Take the Heat off Me (1975).jpg]]"
---
[Time:: 2:27]
[Artist:: [[Boney M]] ]
[Genre:: Pop]
[Played:: 39]
[Album:: [[Take the Heat off Me (1975)]]]
[Year:: 1975]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Baby Do You Wanna Bump]]
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
		intensity: page["Baby_Do_You_Wanna_Bump"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
