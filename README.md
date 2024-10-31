# PolyTrack Rainbow car
```javascript
// ==UserScript==
// @name         New Userscript
// @namespace    http://tampermonkey.net/
// @version      2024-10-25
// @description  try to take over the world!
// @author       You
// @match        https://app-polytrack.kodub.com/*/*
// @icon         https://www.google.com/s2/favicons?sz=64&domain=kodub.com
// @grant        none
// ==/UserScript==

let url = "https://raw.githubusercontent.com/Candorada/TamperMonkey/refs/heads/main/polyCartRainbowCar.js"
async function tamper() {
	try{
	await fetch(url)
	document.body.parentElement.innerHTML =`
	<!DOCTYPE html>

	<html>
		<head>
			<link rel="manifest" href="manifest.json" />
			<meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1, maximum-scale=1, user-scalable=no">
		</head>
		<body>
			<canvas id="screen"></canvas>
			<div id="ui"></div>
			<div id="transition-layer"></div>
		</body>
	</html>
	`
	let s = document.createElement("script")
	s.textContent = await (await fetch(url)).text()
	document.body.appendChild(s)
	}catch{

	}
}
tamper()

```
rainbow Mclarin
```javascript
// ==UserScript==
// @name         New Userscript
// @namespace    http://tampermonkey.net/
// @version      2024-10-25
// @description  try to take over the world!
// @author       You
// @match        https://app-polytrack.kodub.com/*/*
// @icon         https://www.google.com/s2/favicons?sz=64&domain=kodub.com
// @grant        none
// ==/UserScript==

let url = "https://raw.githubusercontent.com/Candorada/TamperMonkey/refs/heads/main/RainBowMclarin.js"
async function tamper() {
	try{
	await fetch(url)
	document.body.parentElement.innerHTML =`
	<!DOCTYPE html>

	<html>
		<head>
			<link rel="manifest" href="manifest.json" />
			<meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1, maximum-scale=1, user-scalable=no">
		</head>
		<body>
			<canvas id="screen"></canvas>
			<div id="ui"></div>
			<div id="transition-layer"></div>
		</body>
	</html>
	`
	let s = document.createElement("script")
	s.textContent = await (await fetch(url)).text()
	document.body.appendChild(s)
	}catch{

	}
}
tamper()

```
