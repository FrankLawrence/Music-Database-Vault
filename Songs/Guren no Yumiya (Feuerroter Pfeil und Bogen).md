---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Attack on Titan Original Soundtrack ().jpg]]"
---
[Time:: 5:16]
[Artist:: [[Linked Horizon]] ]
[Genre:: J-Pop]
[Played:: 5]
[Album:: [[Attack on Titan Original Soundtrack ()]]]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Guren no Yumiya (Feuerroter Pfeil und Bogen)]]
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
		intensity: page["Guren_no_Yumiya_(Feuerroter_Pfeil_und_Bogen)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
