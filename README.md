# JavaSripts.js


try{
    let a =10;
    let b = 0;
    console.log(typeof b);
    if  (b == 0) throw new error("You cannot devide by zero");
    if(typeof b == "str")throw new error("Entry is not a number");
// let c = a/b;
console.log(a/b);
}catch(error){
    console.log(error.message);
}finally{
    console.log("Attend to divide processed...");
}



const student = {
    fullname:"Lawrence Arube",
    yob: 1962,
    accessno: "B33232",
    regno: "M25B13/25"
    gender: "Male",
    phone:"0754762767",
};
console.log(Student.accessno);

class student {
    constructor(fullname, yob, accessno, regno, gender, phone, isregistered){
        this.fullname = fullname
        this.yob = yob
        this.accessno = accessno
        this.regno = regno
        this.gender = gender
        this.phone = phone
        this.isregistered = isregistered
    }
}
