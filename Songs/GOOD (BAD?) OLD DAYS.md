---
tags: Song ⭐⭐⭐⭐ 
banner: "![[An Insatiable High (1977).jpg]]"
---
[Time:: 5:26]
[Artist:: [[Masayoshi Takanaka (高中正義)]] ]
[Genre:: Jazz]
[Played:: 14]
[Album:: [[An Insatiable High (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[GOOD (BAD?) OLD DAYS]]
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
		intensity: page["GOOD_(BAD?)_OLD_DAYS"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
