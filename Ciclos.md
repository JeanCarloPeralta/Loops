//while
let i = 0;
while (i < 850) {
  console.log("Hola mundo");
  i = i + 1;
}

//for

for (var i=0; i < 850; i++) {
  console.log("Hola mundo");
}

// do ... while

let i = 0;
do {
  i += 1;
  console.log(i);
} while (i < 5);

//for statement

for ([initialExpression]; [conditionExpression]; [incrementExpression])
  statement

//labeled

for (let i = 0; i < a.length; i++) {
  if (a[i] === theValue) {
    break;
  }
}

//for...in 

function dump_props(obj, obj_name) {
  let result = '';
  for (let i in obj) {
    result += obj_name + '.' + i + ' = ' + obj[i] + '<br>';
  }
  result += '<hr>';
  return result;
}

//for ... of

const arr = [3, 5, 7];
arr.foo = 'hola';

for (let i in arr) {
   console.log(i); // logs "0", "1", "2", "foo"
}

for (let i of arr) {
   console.log(i); // logs 3, 5, 7
}

//continue 

let i = 0;
let n = 0;
while (i < 5) {
  i++;
  if (i === 3) {
    continue;
  }
  n += i;
  console.log(n);
}
//1,3,7,12


let i = 0;
let n = 0;
while (i < 5) {
  i++;
  if (i === 3) {
     // continue;
  }
  n += i;
  console.log(n);
}