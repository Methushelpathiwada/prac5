// let user = {
//     age: 30,
//     name: 'Rahul',
//     sayHi: function () {
//         console.log('hi!')
//     }
// }

// function sayHi() {
//     console.log("hi from normal function")
// }
// // a function bound to an object is called a method

// sayHi()

// console.log(user.sayHi)

// user.sayHi()

// let user = {
//     age: 30,
//     firstName: 'Rahul',
//     sayHi: function () {
//         console.log('hi', this.firstName)
//     }
// }

// let admin = user
// user = null
// // console.log(admin.sayHi)
// admin.sayHi()

// let user = {
//     firstName: 'rahul',
//     score: 0,
//     incrementScore() {
//         this.score++
//     }
// }

// // console.log(user.score)

// user.incrementScore()
// user.incrementScore()
// user.incrementScore()

// console.log(user.score)

// var firstName = 'Aditi'
// function sayHi() {
//     console.log(this) //inside a normal function, "this" refers to the global object
//     console.log(this.firstName)
// }
// let user = {
//     firstName: 'rahul',
//     objectType: 'USER'
// }
// let admin = {
//     firstName: 'shruti',
//     objectType: 'ADMIN'
// }

// let user2 = {
//     firstName: 'Bhanu',
//     sayHi: () => {
//         console.log(this.firstName) //"this" inside an arrow function refers to the WINDOW object
//     }
//     // sayHi: function () {
//     //     console.log(this.firstName) //"this" refers to user2
//     // }
// }

// user.funcUser = sayHi
// admin.funcAdmin = sayHi

// user.funcUser()
// admin.funcAdmin()

//value of "this" is defined during runtime and it refers to the object from where it was called.

// sayHi()

// user2.sayHi()




// question

// let ladder = {
//     step: 0,
//     up() {
//         // this.step++
//         console.log(this.step++)
//     },
//     down() {
//         this.step--
//         console.log('decremented')
//     },
//     showStep() {
//         console.log(this.step)
//     }
// }

// ladder.up()
// ladder.up()
// ladder.down()
// ladder.down()
// ladder.down()
// ladder.showStep()//-1
// ladder.up()
// ladder.up()
// ladder.up()
// ladder.showStep()//2


// const obj = {
//     message: 'Hello, World',
//     getMessage() {
//         const message = 'Hello, Earth'
//         return this.message
//     }
// }

// let result = obj.getMessage()
// console.log(result) //


// let obj = {
//     who: 'World',
//     greet: function () {
//         console.log(`Hello, ${this.who}`)
//     },
//     farewell: () => {
//         console.log(`Goodbye, ${this.who}`)
//     }
// }

// obj.greet()
// obj.farewell()