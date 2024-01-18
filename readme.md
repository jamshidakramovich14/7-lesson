//////////////////////////   7-DARS  ////////////////////////

### switsh - taqoslash operatori

let a = +prompt("Bahoyingizni kiriting");
if(Number.isInteger(a) && a >0 && a < 6){
    switch (a){
        case 1 :
            console.log(`Sizning bahoyingiz(' ${a} ')  yomon `);
            break;
        case 2 :
            console.log(`Sizning bahoyingiz(' ${a} ')  qoniqarsiz `);
            break;
        case 3 :
            console.log(`Sizning bahoyingiz(' ${a} ')  qoniqarli `);
            break;
         case 4 :
            console.log(`Sizning bahoyingiz(' ${a} ')  yahshi `);
            break;
        case 5 :
            console.log(`Sizning bahoyingiz(' ${a} ')  alo `);
            break;   
    }
}else{
    console.log("Xato !");
}


### if else -shartli operator

let a = +prompt("a sonini kiriting");
let b = +prompt("b sonini kiriting");
if (a % 2 == 1 && b % 2 == 1){
    console.log("siz kiritga ikkala son ham tog son");
}else{
    console.log("sizkiritgan sonlar ten tog bo'lishligi kerak")
}

### Global scope

// let a = 3;

// var b = 4;

// const c = 5;

// if (true) {

//   console.log(a);

//   console.log(b);

//   console.log(c);
// }

// switch (a) {

//   case 3:

//     console.log(a);

//     console.log(b);

//     console.log(c);

//     break;
// }


### Local or Function scope

// function add() {

//   let a = 3;

//   var b = 4;

//   const c = 5;

// }

// add();

// console.log(a);

// console.log(b);

// console.log(c);


### For loop

// for (initializer; condition; iterator) {

//   // statements

// }

// for (let i = 1; i <= 10; i++) {

//   console.log(i);

// }

// for (let i = 2; i <= 10; i += 2) {

//   console.log(i);

// }

### While loop

 // while (condition) {

//   // code block to be executed

// }

// let i = 1;

// while (i <= 10) {

//   console.log(i);

//   i++;

// }

// let count = 1;

// while (count <= 10) {

//   console.log(count);

//   count += 1;

// }