# project-app
script.jss
const form=document.getelementById("student form");
cons table=document.getElementBYId("student table");
let student=JSON. prse(local storage.getItem("student") ||[];
function display students() {
table.innnerHTML= " ";
student. foreach((student,index)=>{ const row=
<tr>
<td>${student.name}</td>
<td>${student.age}</td>
<td>${student.course}</td>
<td><button class="delete" onclick="delete student (${index})"delete</button></td>
</tr>;
table.innerHTMl +=row;
});
Local storage=setItem("student.JSON.string;(student))
}
form.addEventListener("submit", function(e))
{
e.preventDefault();
const name=document.getElementById("name").value;
const age=document.getElementById("age").value;
const course=document.getElementById("course").value;
student.push({name,age,course});
display student();
form.rest();
}}
funtion


const 

