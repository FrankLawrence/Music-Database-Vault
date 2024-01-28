---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Kaleidoscope (2017).jpg]]"
---
[Time:: 4:31]
[Artist:: [[Coldplay]] ]
[Genre:: Rock, Pop]
[Played:: 97]
[Album:: [[Kaleidoscope (2017)]]]
[Year:: 2017]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[All I Can Think About Is You]]
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
		intensity: page["All_I_Can_Think_About_Is_You"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
