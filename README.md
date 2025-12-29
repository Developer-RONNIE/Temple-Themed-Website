<div align="center">
  <br />
    <a href="" target="_blank">
      <img src="/assets/img/preview.png" alt="Project Banner">
    </a>
  <br />

  <div>
    <img src="https://img.shields.io/badge/-HTML_5-E34F26?style=for-the-badge&logoColor=white&logo=html5" alt="html5" />
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logoColor=white&logo=css3" alt="css3" />
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white" alt="javascript" />


  </div>

  <h3 align="center">Temple Themed Website</h3>
    <div align="center">
     Welcome to the source code of this Temple Themed Website — refer to <a href="#snippets" ><b>code snippets</b></a> if you find it difficult to navigate or copy specific CSS sections.
     </div>

</div>

## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🕸️ [Snippets](#snippets)
6. 🔗 [Links](#links)
7. 🚀 [More](#more)

## <a name="introduction">🤖 Introduction</a>

Develop a Christmas Themed Website using HTML and CSS with smooth subtle animations using GSAP. 

<p align="center">
  <a href="https://developer-ronnie.hashnode.dev" target="_blank">
    <img src="https://img.shields.io/badge/Read%20My%20Blog-Hashnode-blueviolet?style=for-the-badge&logo=internet-explorer&logoColor=white" alt="Read Blog on Hashnode"/>
  </a>
</p>


## <a name="tech-stack">⚙️ Tech Stack</a>

- HTML 5
- CSS 3
- GSAP

## <a name="features">🔋 Features</a>

👉 **CSS Variables**: Utilize CSS variables to maintain a consistent and easily adjustable styling approach throughout the project

👉 **Importing CSS Files**: Import CSS files into others, promoting modularity and organization in styling.

👉 **Flex and Position Properties**: Use of flex and position properties in CSS to create responsive and well-structured layouts.

👉 **Rendering HTML through JavaScript**: Rendering HTML through JavaScript using reusable functions, enhancing code efficiency.

👉 **Smooth Animations**: Smooth and subtle animations to enhance the overall user experience, focusing on fluid transitions.

👉 **BEM Method**: Follow the Block Element Modifier (BEM) methodology for naming classes, promoting a clear and maintainable structure.

👉 **Organized File and Folder Structure**: Maintain a well-organized file and folder structure for easy navigation and management of project assets.

👉 **Responsive Design**: The application is completely responsive across all devices, employing responsive design techniques such as media queries and fluid layouts.

all these while creating the sushi website with,
* Navigation Bar
* Creative Hero Section
* About Us Section


## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Liveserver](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

**Cloning the Repository**

```bash
git clone https://github.com/Developer-RONNIE/Temple-Themed-Website.git
cd project_html_css_website
```

**Running the Project**

Run the [live server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension 

Open [http://localhost:5173](http://localhost:5173) in your browser to view the project.

## <a name="snippets">🕸️ Snippets</a>


<details>
<summary><code>sakura.min.js</code></summary>
```javascript
/*!
 * Sakura.js 1.1.1
 * Vanilla JS version of jQuery-Sakura: Make it rain sakura petals.
 * https://github.com/jhammann/sakura
 *
 * Copyright 2019-2022 Jeroen Hammann
 *
 * Released under the MIT License
 *
 * Released on: March 4, 2022
 */
"use strict";function _slicedToArray(t,e){return _arrayWithHoles(t)||_iterableToArrayLimit(t,e)||_unsupportedIterableToArray(t,e)||_nonIterableRest()}function _nonIterableRest(){throw new TypeError("Invalid attempt to destructure non-iterable instance.\nIn order to be iterable, non-array objects must have a [Symbol.iterator]() method.")}function _iterableToArrayLimit(t,e){var r=null==t?null:"undefined"!=typeof Symbol&&t[Symbol.iterator]||t["@@iterator"];if(null!=r){var n,a,o=[],i=!0,l=!1;try{for(r=r.call(t);!(i=(n=r.next()).done)&&(o.push(n.value),!e||o.length!==e);i=!0);}catch(t){l=!0,a=t}finally{try{i||null==r.return||r.return()}finally{if(l)throw a}}return o}}function _arrayWithHoles(t){if(Array.isArray(t))return t}function _createForOfIteratorHelper(t,e){var r,n="undefined"!=typeof Symbol&&t[Symbol.iterator]||t["@@iterator"];if(!n){if(Array.isArray(t)||(n=_unsupportedIterableToArray(t))||e&&t&&"number"==typeof t.length)return n&&(t=n),r=0,{s:e=function(){},n:function(){return r>=t.length?{done:!0}:{done:!1,value:t[r++]}},e:function(t){throw t},f:e};throw new TypeError("Invalid attempt to iterate non-iterable instance.\nIn order to be iterable, non-array objects must have a [Symbol.iterator]() method.")}var a,o=!0,i=!1;return{s:function(){n=n.call(t)},n:function(){var t=n.next();return o=t.done,t},e:function(t){i=!0,a=t},f:function(){try{o||null==n.return||n.return()}finally{if(i)throw a}}}}function _unsupportedIterableToArray(t,e){if(t){if("string"==typeof t)return _arrayLikeToArray(t,e);var r=Object.prototype.toString.call(t).slice(8,-1);return"Map"===(r="Object"===r&&t.constructor?t.constructor.name:r)||"Set"===r?Array.from(t):"Arguments"===r||/^(?:Ui|I)nt(?:8|16|32)(?:Clamped)?Array$/.test(r)?_arrayLikeToArray(t,e):void 0}}function _arrayLikeToArray(t,e){(null==e||e>t.length)&&(e=t.length);for(var r=0,n=new Array(e);r<e;r++)n[r]=t[r];return n}var Sakura=function(t,e){var u=this;if(void 0===t)throw new Error("No selector present. Define an element.");this.el=document.querySelector(t);var r,n;function o(t){return t[Math.floor(Math.random()*t.length)]}function i(t,e){return Math.floor(Math.random()*(e-t+1))+t}this.settings=(r={className:"sakura",fallSpeed:1,maxSize:14,minSize:10,delay:300,colors:[{gradientColorStart:"rgba(255, 183, 197, 0.9)",gradientColorEnd:"rgba(255, 197, 208, 0.9)",gradientColorDegree:120}],lifeTime:0},n=e,Object.keys(r).forEach(function(t){n&&Object.prototype.hasOwnProperty.call(n,t)&&(r[t]=n[t])}),r),this.petalsWeak=new Map,setInterval(function(){if(u.settings.lifeTime){var t,e=[],r=Date.now(),n=_createForOfIteratorHelper(u.petalsWeak);try{for(n.s();!(t=n.n()).done;){var a=_slicedToArray(t.value,2),o=a[0],i=a[1];o+u.settings.lifeTime<r&&(e.push(o),i.remove())}}catch(t){n.e(t)}finally{n.f()}for(var l=0,s=e;l<s.length;l++){var c=s[l];u.petalsWeak.delete(c)}}},1e3),this.el.style.overflowX="hidden";var l=["webkit","moz","MS","o",""];function s(t,e,r){for(var n=0;n<l.length;n+=1){var a=e;l[n]||(a=e.toLowerCase()),t.addEventListener(l[n]+a,r,!1)}}function c(t){t=t.getBoundingClientRect();return 0<=t.top&&0<=t.left&&t.bottom<=(window.innerHeight||document.documentElement.clientHeight)&&t.right<=(window.innerWidth||document.documentElement.clientWidth)}this.createPetal=function(){u.el.dataset.sakuraAnimId&&setTimeout(function(){window.requestAnimationFrame(u.createPetal)},u.settings.delay);var t=["sway-0","sway-1","sway-2","sway-3","sway-4","sway-5","sway-6","sway-7","sway-8"],e=o(["blow-soft-left","blow-medium-left","blow-soft-right","blow-medium-right"]),t=o(t),r=(.007*document.documentElement.clientHeight+Math.round(5*Math.random()))*u.settings.fallSpeed,e=["fall ".concat(r,"s linear 0s 1"),"".concat(e," ").concat((30<r?r:30)-20+i(0,20),"s linear 0s infinite"),"".concat(t," ").concat(i(2,4),"s linear 0s infinite")].join(", "),n=document.createElement("div"),r=(n.classList.add(u.settings.className),i(u.settings.minSize,u.settings.maxSize)),t=r-Math.floor(i(0,u.settings.minSize)/3),a=o(u.settings.colors);n.style.background="linear-gradient(".concat(a.gradientColorDegree,"deg, ").concat(a.gradientColorStart,", ").concat(a.gradientColorEnd,")"),n.style.webkitAnimation=e,n.style.animation=e,n.style.borderRadius="".concat(i(u.settings.maxSize,u.settings.maxSize+Math.floor(10*Math.random())),"px ").concat(i(1,Math.floor(t/4)),"px"),n.style.height="".concat(r,"px"),n.style.left="".concat(Math.random()*document.documentElement.clientWidth-100,"px"),n.style.marginTop="".concat(-(Math.floor(20*Math.random())+15),"px"),n.style.width="".concat(t,"px"),s(n,"AnimationEnd",function(){c(n)||n.remove()}),s(n,"AnimationIteration",function(){c(n)||n.remove()}),u.petalsWeak.set(Date.now(),n),u.el.appendChild(n)},this.el.setAttribute("data-sakura-anim-id",window.requestAnimationFrame(this.createPetal))};Sakura.prototype.start=function(){if(this.el.dataset.sakuraAnimId)throw new Error("Sakura is already running.");this.el.setAttribute("data-sakura-anim-id",window.requestAnimationFrame(this.createPetal))},Sakura.prototype.stop=function(){var e=this,t=0<arguments.length&&void 0!==arguments[0]&&arguments[0],r=this.el.dataset.sakuraAnimId;r&&(window.cancelAnimationFrame(r),this.el.setAttribute("data-sakura-anim-id","")),t||setTimeout(function(){for(var t=document.getElementsByClassName(e.settings.className);0<t.length;)t[0].parentNode.removeChild(t[0])},this.settings.delay+50)};
```
</details>


<details>
<summary><code>sakura.min.js</code></summary>
```css 
/*!
 * Sakura.js 1.1.1
 * Vanilla JS version of jQuery-Sakura: Make it rain sakura petals.
 * https://github.com/jhammann/sakura
 *
 * Copyright 2019-2022 Jeroen Hammann
 *
 * Released under the MIT License
 *
 * Released on: March 4, 2022
 */@-webkit-keyframes fall{0%{opacity:.9;top:0}100%{opacity:.2;top:100%}}@keyframes fall{0%{opacity:.9;top:0}100%{opacity:.2;top:100%}}@-webkit-keyframes blow-soft-left{0%{margin-left:0}100%{margin-left:-50%}}@keyframes blow-soft-left{0%{margin-left:0}100%{margin-left:-50%}}@-webkit-keyframes blow-medium-left{0%{margin-left:0}100%{margin-left:-100%}}@keyframes blow-medium-left{0%{margin-left:0}100%{margin-left:-100%}}@-webkit-keyframes blow-soft-right{0%{margin-left:0}100%{margin-left:50%}}@keyframes blow-soft-right{0%{margin-left:0}100%{margin-left:50%}}@-webkit-keyframes blow-medium-right{0%{margin-left:0}100%{margin-left:100%}}@keyframes blow-medium-right{0%{margin-left:0}100%{margin-left:100%}}@-webkit-keyframes sway-0{0%{-webkit-transform:rotate(-5deg);transform:rotate(-5deg)}40%{-webkit-transform:rotate(28deg);transform:rotate(28deg)}100%{-webkit-transform:rotate(3deg);transform:rotate(3deg)}}@keyframes sway-0{0%{-webkit-transform:rotate(-5deg);transform:rotate(-5deg)}40%{-webkit-transform:rotate(28deg);transform:rotate(28deg)}100%{-webkit-transform:rotate(3deg);transform:rotate(3deg)}}@-webkit-keyframes sway-1{0%{-webkit-transform:rotate(10deg);transform:rotate(10deg)}40%{-webkit-transform:rotate(43deg);transform:rotate(43deg)}100%{-webkit-transform:rotate(15deg);transform:rotate(15deg)}}@keyframes sway-1{0%{-webkit-transform:rotate(10deg);transform:rotate(10deg)}40%{-webkit-transform:rotate(43deg);transform:rotate(43deg)}100%{-webkit-transform:rotate(15deg);transform:rotate(15deg)}}@-webkit-keyframes sway-2{0%{-webkit-transform:rotate(15deg);transform:rotate(15deg)}40%{-webkit-transform:rotate(56deg);transform:rotate(56deg)}100%{-webkit-transform:rotate(22deg);transform:rotate(22deg)}}@keyframes sway-2{0%{-webkit-transform:rotate(15deg);transform:rotate(15deg)}40%{-webkit-transform:rotate(56deg);transform:rotate(56deg)}100%{-webkit-transform:rotate(22deg);transform:rotate(22deg)}}@-webkit-keyframes sway-3{0%{-webkit-transform:rotate(25deg);transform:rotate(25deg)}40%{-webkit-transform:rotate(74deg);transform:rotate(74deg)}100%{-webkit-transform:rotate(37deg);transform:rotate(37deg)}}@keyframes sway-3{0%{-webkit-transform:rotate(25deg);transform:rotate(25deg)}40%{-webkit-transform:rotate(74deg);transform:rotate(74deg)}100%{-webkit-transform:rotate(37deg);transform:rotate(37deg)}}@-webkit-keyframes sway-4{0%{-webkit-transform:rotate(40deg);transform:rotate(40deg)}40%{-webkit-transform:rotate(68deg);transform:rotate(68deg)}100%{-webkit-transform:rotate(25deg);transform:rotate(25deg)}}@keyframes sway-4{0%{-webkit-transform:rotate(40deg);transform:rotate(40deg)}40%{-webkit-transform:rotate(68deg);transform:rotate(68deg)}100%{-webkit-transform:rotate(25deg);transform:rotate(25deg)}}@-webkit-keyframes sway-5{0%{-webkit-transform:rotate(50deg);transform:rotate(50deg)}40%{-webkit-transform:rotate(78deg);transform:rotate(78deg)}100%{-webkit-transform:rotate(40deg);transform:rotate(40deg)}}@keyframes sway-5{0%{-webkit-transform:rotate(50deg);transform:rotate(50deg)}40%{-webkit-transform:rotate(78deg);transform:rotate(78deg)}100%{-webkit-transform:rotate(40deg);transform:rotate(40deg)}}@-webkit-keyframes sway-6{0%{-webkit-transform:rotate(65deg);transform:rotate(65deg)}40%{-webkit-transform:rotate(92deg);transform:rotate(92deg)}100%{-webkit-transform:rotate(58deg);transform:rotate(58deg)}}@keyframes sway-6{0%{-webkit-transform:rotate(65deg);transform:rotate(65deg)}40%{-webkit-transform:rotate(92deg);transform:rotate(92deg)}100%{-webkit-transform:rotate(58deg);transform:rotate(58deg)}}@-webkit-keyframes sway-7{0%{-webkit-transform:rotate(72deg);transform:rotate(72deg)}40%{-webkit-transform:rotate(118deg);transform:rotate(118deg)}100%{-webkit-transform:rotate(68deg);transform:rotate(68deg)}}@keyframes sway-7{0%{-webkit-transform:rotate(72deg);transform:rotate(72deg)}40%{-webkit-transform:rotate(118deg);transform:rotate(118deg)}100%{-webkit-transform:rotate(68deg);transform:rotate(68deg)}}@-webkit-keyframes sway-8{0%{-webkit-transform:rotate(94deg);transform:rotate(94deg)}40%{-webkit-transform:rotate(136deg);transform:rotate(136deg)}100%{-webkit-transform:rotate(82deg);transform:rotate(82deg)}}@keyframes sway-8{0%{-webkit-transform:rotate(94deg);transform:rotate(94deg)}40%{-webkit-transform:rotate(136deg);transform:rotate(136deg)}100%{-webkit-transform:rotate(82deg);transform:rotate(82deg)}}.sakura{pointer-events:none;position:absolute}
```

</details>


## <a name="links">🔗 Links</a>

Assets used in the project are [here](/assets/)

## <a name="more">🚀 More</a>

**Build more clean and creative HTML & CSS projects like this**

Enjoyed creating this project? Dive deeper into more projects for a richer learning adventure. They're packed with detailed cool features, and exercises to boost your skills. Give it a go!


<p align="center">
  <a href="https://github.com/Developer-RONNIE/">
    <img src="https://img.shields.io/badge/HTML--CSS-Projects-black?style=for-the-badge&logo=github&logoColor=white" alt="HTML-CSS Projects Badge" />
  </a>
</p>


