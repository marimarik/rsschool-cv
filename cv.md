
# Mari Kipshidze

## Contact Info
**Mobile:**  577 95 58 12

**E-mail:**  m.kipshidze@sangu.edu.ge

**GitHub:** [marimarik](https://github.com/marimarik)

**Discord:** [Mari-ami#5378](https://discord.com/channels/@me) 


## Summary 

I am interested in web development. My wish is to gain new knowledge and skills to solve software issues quickly and efficiently.

For me it is important to have a quiet, friendly environment. My strengths are that I am hard working, responsible, problem-solving and a team player. I am a careful listener and a fast learner.

My goal is to enter the international IT market and to gain appropriate experience in Frond-End development starting as a Junior Developer. Currently I am following the Rolling Scopes Training Program and at the end of this course I hope to have an opportunity to join EPAM team. 


## Education 

I graduated from St. Andrew the First-Called Georgian University and got a Master's Degree in psychology, psycho diagnostics and consulting.


## Skills

- HTML, CSS
- JS, JSON, AJAX and jQuery Basics
- Version control: Git (remote service GitHub).
- VS Code


## Courses

- W3school html & CSS courses: 
https://www.w3schools.com/html/
https://www.w3schools.com/css/
- W3School Javascript coursee:
https://www.w3schools.com/js/
- Udemy’s “Web Developer Bootcamp” online course (in progress):
https://www.udemy.com/course/the-web-developer-bootcamp/
- Georgia`s Innovation & Technology Agency (GITA) - “JavaScript and Front-End Frameworks”.
- RS Schools Course «JS/FE Course EN 2022. Stage 1» (in progress)


## English Level: Intermediate (B1)

- 2021 fall semester – Intermediate Level course at LTD “International House (IH) Tbilisi”
- Currently - I am taking a 4-month intensive English language Upper-Intermediate Level course at LTD “International House (IH) Tbilisi”.
-  P.S. I practice my language skills everywhere I can. 
  Plus, I have a foreigner teacher at “International House Tbilisi”.
  
## Experience 

-	Here is my profile on Khanacademy:  
[https://www.khanacademy.org](https://www.khanacademy.org/profile/marimarik/projects) 
-	Here is my profile on Codewars:  
[https://www.codewars.com](https://www.codewars.com/users/Mari-Am)
-	Here is my profile on Codehs:
[https://www.codehs.com/](https://codehs.com/student/3360716/section/305886/assignments) 
-	Also, I`ve done some exercises and coding tests online on the web sites: 
[https://www.w3schools.com](https://www.w3schools.com/) 
[https://www.freecodecamp.org](https://www.freecodecamp.org/) 
-	I`ve a well written (85% mark) Final Coding Test in GITA final exam.    

## Code examples 

Given a string, turn each character into its ASCII character code and join them together to create a number - let's call this number total1. Then replace any incidence of the number 7 with the number 1, and call this number 'total2'. Then return the difference between the sum of the digits in total1 and total2:
```js
function calc(x){
  var total1 = '';
  var total2 = '';
  var sum = 0;
  for (let i = 0; i < x.length; i++) {
    total1 += x.charCodeAt(i);
  }
  total2 = total1.replace(/7/g, "1");
  for (let i = 0; i < total1.length; i++) {
    sum += total1[i] - total2[i];
  }
  return sum;
}
```

