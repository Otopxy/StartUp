# StartUp
let listA = [];
let listB = [];
for (let i = 1; i <= 200; i++) {
if (i % 2 === 0) {
// number is even
listA.push(i);
} else {
// number is not even (=odd)
listB.push(i);
} }console.log("Total number of listA =" + listA.length);
console.log("Total number of listB =" + listB.length);
