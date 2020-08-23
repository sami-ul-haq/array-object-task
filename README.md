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
### [Students' Names and Hobbies Data]
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
### [Extensive Students' Data]
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
    
Q2. Print names of female students only.
Ans.   
    students.forEach(function(student){
      if(student.gender === "f"){
         console.log(student.name);
      } })
  
Q3. Print names of male students only.
Ans.
    students.forEach(function(student){
      if(student.gender === "m"){
         console.log(student.name);
      } })

Q4. Print names of students who have passed the admission test. Passing marks are 50.
Ans.
    students.forEach(function(student){
    if(student.admissionTestScore >= 50){
        console.log(student.name);
    }  })

Q5. Print names of eligible students only (students who have internet and live in Karachi are eligible)
Ans.
    students.forEach(function(student){
    if(student.hasInternet && student.address.city === "Karachi"){
        console.log(student.name);
    }  })

Q6. Print address of each student in this format:
      Amna's address:
      Gulistan-e-Johar in Karachi, Pakistan
Ans.
    students.forEach(function(student){
      console.log(`${student.name}'s Address \n${student.address.ilaqa} in ${student.address.city}, ${student.address.country}`);     
    })



Q7. Print names and phone number of students who have Ufone.
Ans.
    students.forEach(function(student){
    if(student.phoneNo.includes('0331')){
        console.log(`Names: ${student.name} \nPhone No: ${student.phoneNo}`);
    } })

Q8. Students who have a job or a class are placed in Group B. Print the names of students in Group A, and in Group B, in the below format:
      Group A:  name1, name2
      Group B:  name3, name4, name5
Ans.


Q9. Print age of each student in the below format:
      Amna's age is 29 years
Ans.


Q10. Print the name of the oldest student
Ans.

```
