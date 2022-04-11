# Beso Shubitidze
## My Contact Info

-	Mobile  +995 598 30 60 73
-	E-mail besoshubitidze93@gmail.com
-	Git https://github.com/BShubitidze
-	Facebook https://www.facebook.com/besoshubitidze93/

---

# Summary

- My name is Beso Shubitidze I live in Georgia Rustavi, 28 years old. I worked in another field for years, but I became interested in programming and decided to change my job. I have no experience in programming but I have a great desire to learn.


---

## Skills
-	Html5
-	Css
-	Javascript
-	C#
-	SQL
-	Git 
-	Figma (For web development) 
-	Editors: VSCode, Visual studio .

## Education
-	w3school
-	freecodecamp


## Languages
-	Georgian – native
-	English - A2
-	Russian - B1

---
# Experience
- no experience in programming

# Code Example
```
function Car(mName, mYear){
    this.name = mName;
    this.year = mYear;
};
function User(pName, pAge) {
    this.name = pName;
    this.age = pAge;
    this.driveCar = function(car){
        console.log(this.name + " ატარებს მანქანას მარკით " + car.name + " გამოშვების წელი " + car.year);
    };
    this.displayInfo = function(){
        console.log("სახელი: " + this.name + "; ასაკი: " + this.age);
    };
};
 
var giorgi = new User("გიორგი", 26);
giorgi.displayInfo();
var bently = new Car("ბენტლი", 2014);
giorgi.driveCar(bently);

```