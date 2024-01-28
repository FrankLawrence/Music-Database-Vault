---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[長江水 (Water of the Yangtze River) (2020).jpg]]"
---
[Time:: 3:00]
[Artist:: [[費玉清 (Fei Yu-ching)]] ]
[Genre:: ]
[Played:: 10]
[Album:: [[長江水 (Water of the Yangtze River) (2020)]]]
[Year:: 2020]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[剪梅 (Yi Jian Mei) Trap Remix]]
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
		intensity: page["剪梅_(Yi_Jian_Mei)_Trap_Remix"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
