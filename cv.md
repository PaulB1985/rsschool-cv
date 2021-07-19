
# Paul Bogdanovsky 

### Contacts: 
+  Belarus, Minsk
+  Mobile phone: +375339105021
+  Instagram: paulpriest1985
+  Telegram: @paulpriest
+  E-mail: paulpriest1985@gmail.com

* * *

### About Me 
My general target is to become front end developer. Last year I decided to change my professional field and start studying as a developer. I started with self-study: I watched courses on YouTube, read books, resolved tasks. The next degree was course "Web-application development basics" in BelHard Academy. We studied HTML & CSS there. But on that moment, I understood that I know more in these disciplines and became learn Javascript. These year I graduated course of basic Javascript in Belhard Academy. Everyday I spend about two hours for study, every day I trying to know something new, to take some experience. I consider myself a purposeful person and will do everything possible to realize my dream.

*** 

### My skills 
1.    HTML (advanced level)
2.    CSS (advanced)
3.    SCSS (basic)
4.    BEM
5.    JavaScript (basic)
6.    React (start)
7.    Git&Github (basic)

* * *

### Sample code
_I recently completed this task in Belhard Academy. By pressing the button, a specified number of blocks with a random background is displayed on the screen and a specified number of images are displayed inside each of the blocks_    
>Javascript code section:    
let blocksQuantity = document.getElementById('blocksQ');    
let picturesQuantity = document.getElementById('picturesQ');    
let buttonGet = document.getElementById('buttonGet');    
let container = document.getElementById('container');    
let pics = document.getElementById("pics");    
let color = [0, 1, 2, 3, 4, 5, 6, 7, 8, 9,     
			'a','b', 'c', 'd', 'e', 'f'];    
function getResultOperation() {    
s1 = '';    
for (n=0; n< 6; n++) {    
	result = Math.floor(Math.random()*color.length);    
	s1 += color[result];     	  
}     
let colorResult = '#' + s1;      
let blockValue = blocksQuantity.value;    
let s = '';    
let s3 = "";    
let picturesValue = picturesQuantity.value;    
for (l=1; l<=picturesValue; l++){    
	s3 += `<img src="../images/${l}.jpg" alt="pic"     
//  	style="width: 150px; height: 75px;">`     
};    
for (i=1; i<=blockValue; i++) {     
	s += `<div class="getColor" style="background:      
	${colorResult}">${s3}</div>`    
}    	
container.innerHTML = s;     	
} 

***

### Work experience
I haven't commercial development experience, but I took part in development of mobile app. My task was to write a javascript code section for swiping product cards. I have solved this problem, but soon project was closed. Also I have experience in creation of web sites: I wrote landing pages, worked with CMS. Now, I am here to take a new experience & somewhen deliver it to next generation...

***

### Education
| Years | Institution | Specialization |   
|-------|-------------|----------------|
| 2003-2008 | BSEU | Accounting, analysis and audit in industry |    
| 2020 | Belhard Academy | Basics of web application development |    
| 2021 | Belhard Academy | HTML5, Javascript & actual Front End |

***

### English   
I graduated school with advanced study of English, and then studied english about two years in university. At that moment my english was nearby B1. now it is important for me to return to this level.

