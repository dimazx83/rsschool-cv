# Resume

## Dzmitry Piskunenka
## Contact Info
* Email: [dimazx83@gmail.com](dimazx83@gmail.com)
* Phone: +375299544383
* Telegram: @dimazx83
## Summary
One of my main **goals** during this course is to implement my knowledge on course assignments and future projects. I am **interested** in understanding how to apply information about *JavaScript* in real life. I also expect to find information that I haven't seen on other Internet resources.
I am able to learn programming myself, and if necessary I can find answers to almost all the questions I have. I know how to work together in the team, perform joint tasks and be responsible for the changes I have made in the project.
## Skills
* Languages: HTML & CSS, Javascript, C++ *(also a little less knowledge of C#, SQL, Python)*
* Graphic: Photoshop, Figma
* English level: B1
* Web Design of landing pages, banners, interfaces. [Portfolio](https://freelance.ru/dimazx83)
* SMM (setting up ads in Facebook)
## Code Example
**Представить число в бухгалтерском виде (Вставлять пробел через каждые 3 цифры, с конца числа)**
```javascript
var x=+prompt("Введите число: ");
var copy=x;
var copy2=x;
var fir;

   var check=function (x){
   var len=0;
   if(x!==0){
   while (x) 
   {
        var lastNum = x % 10;
        x = (x - lastNum) / 10;
        len++;
       
    }
    return len;
    }
    else{len=1; return len;} 
   };
  
while(copy>0)
{
var len=check(copy);
console.log(len);

if(len%3==0)
     {
       fir=Math.trunc(copy/10**(len-3)); //123  456
       console.log(fir+"a")
       document.write(fir+" ");
       copy%=10**(len-3);
       console.log(copy+"b");
     };
     if(copy==0)
     {
     document.write(" ");
     }

else if(len%3==1)
     {
       fir=Math.trunc(copy/10**(len-1)); //1
       console.log(fir+"c")
       document.write(fir+" ");
       copy%=10**(len-1);//234567
       console.log(copy+"d");
     };
     if(copy==0)
     {
     document.write(" ");
     }
     
else if(len%3==2)
     {
       fir=Math.trunc(copy/10**(len-2)); //1
       console.log(fir+"e")
       document.write(fir+" ");
       copy%=10**(len-2);//234567
       console.log(copy+"f");
     };
     if(copy==0)
     {
     document.write(" ");
     }
}
```
## Education
* Currently studying in BSU, Managemet of Information Resourses
* Have experience of solving different algorithmic tasks
* Past courses in Html Academy, Codeacademy, read literature from different internet sources about *Javascript*
