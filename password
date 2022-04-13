const readline = require('readline');

const reader = readline.createInterface({
  input: process.stdin,
  output: process.stdout,
});

//let password = []

console.log("Welcome to the passwoed validator tool")

reader.question("Please enter a password to validate?", function(input){

    
    password = input.split('');

    firstCharacter = password[0].toUpperCase()

    // console.log(password.length)

    if (password.length >= 10 && password[0] === firstCharacter){
        console.log(" succes, you created a password")
    }  else if (password.length <= 10 && password[0] != firstCharacter){ 
        console.log(" warning, first character should be  a letter and upper case")
    } else {
        console.log(" warning, you password should be at least 10 characters")
    }

    reader.close()
});