---
tags: Song ⭐⭐⭐⭐ 
banner: "![[The Dark Side of the Moon (1973).jpg]]"
---
[Time:: 1:07]
[Artist:: [[Pink Floyd]] ]
[Genre:: Progressive Rock]
[Played:: 14]
[Album:: [[The Dark Side of the Moon (1973)]]]
[Year:: 1973]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Speak To Me]]
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
		intensity: page["Speak_To_Me"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
