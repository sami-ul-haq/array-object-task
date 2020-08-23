# array-object-task
array-object-task

# Level 01 - Basic [Access Methods Questions]
### How will you access the third position of the following array?
```
Question: let arr = [5, 10, 15]
Answer: console.log(arr[2]);
```
### How will you access the second element, degree from the following object?
```
Question:   let obj = { name: "Maimoona", degree: "MBBS" }
Answer:  console.log(obj.degree)
```
### How will you access all elements of the following array using loops?
```
Question:   let arr = [1, 2, 3, 4, 5, 6, 7]
Answer:  arr.forEach( element => console.log(element));
```
### How will you access all elements of the following object using loops?
```
Question:   let obj = { name: "Maimoona", degree: "MBBS", age: 25 }
Answer:  for (const i in obj) {
              console.log(obj[i]); }
```
# Level 02 - Intermediate 
[Students' Names and Hobbies Data]
```
Question:Print the following to the console:
let students = [{name: "Amna",hobbies: ["eating", "cooking"]},
    {name: "Daniyal",hobbies: ["arts", "shopping"]},
    {name: "Fahad",hobbies: ["coding", "cooking"]},
    {name: "Hajra",hobbies: ["sleep", "reading"]}];

Answer:
    students.forEach(function(student){
        console.log(`Hobies Of ${student.name}`);

    student.hobbies.forEach(function(hobby , index){
        console.log(`${index+1}. ${hobby}`)
        });
    })
```
[Extensive Students' Data]
Array Can Be Found At [Here](https://github.com/techkaro-circle/JS-Arrays-and-Objects-Tasks/wiki/Extensive-Student-Data-Task)
```
Q1. Print each student in this format:
    Name: Amna
    Gender: Female
    City: Karachi
    Score: 56 marks
Ans.
    students.forEach(function(student){
      console.log(`Name: ${student.name}`);
      console.log(`Gender: ${student.gender}`);
      console.log(`City: ${student.address.city}`);
      console.log(`Score: ${student.admissionTestScore}`);
    })
 ```

