
<script>
export default{
    setup(){
      const StudentName = "Riya Diya Hiya"
const Roll = 2344
function AssignmentDate(){
  return "10th December, 2023"
}

//create object
const student = {  
  fname:"Riya",
  mname:"Diya",
  lname:"Hiya",
  getFullName(){
    return this.fname +" "+ this.mname + " "+ this.lname
  }
}
return{
  StudentName,Roll,AssignmentDate,student
}
    }
}
</script>
<template>
 <h1>Student Name: {{ StudentName }}</h1>
<h2>Student Roll: {{ Roll }}</h2>
<h3>Assignment Submission Date: {{ AssignmentDate() }}</h3>

<h4>First name is: {{ student.fname }}</h4>
<h4>Middle name is: {{ student.mname }}</h4>
<h4>Last name is: {{ student.lname }}</h4>
<h4>Full name is: {{ student.getFullName() }}</h4>
</template>

<style scoped>
</style>


