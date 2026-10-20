# activity5
class Animal { speak() { console.log("..."); } } class Dog extends Animal { speak() { console.log("Woof!"); } } class Cat extends Animal { speak() { console.log("Meow!"); } } class Cow extends Animal { speak() { console.log("Moo!"); } } new Dog().speak(); new Cat().speak(); new Cow().speak();
class Animal { eat() { console.log("Barking..."); } } class Dog extends Animal { bark() { console.log("wooof!"); } } const dog = new Dog(); dog.eat(); dog.bark();
class Animal {
    constructor(name) {
        this.name = name;
    }
}

class Cat extends Animal {
    constructor(name) {
        super(name);
    }
}

const cat = new Cat("kallong");
console.log(cat.name);
class Product {
    constructor(name, price) {
        this.name = name;
        this.price = price;
    }

    get price() {
        return this._price;
    }

    set price(value) {
        if (value < 0) {
            console.log("No negative prices!");
        } else {
            this._price = value;
        }
    }
}

const pen = new Product("Notebook", 25);
pen.price = -10;
console.log(notebook.price);
class Student {
    constructor(score) {
        this.score = score;
    }

    get score() {
        return this._score;
    }

    set score(value) {
        if (value < 0) {
            console.log("No negative scores!");
        } else {
            this._score = value;
        }
    }
}

const ana = new Student(90);
ana.score = -5;
console.log(ana.score);
