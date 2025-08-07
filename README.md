# 🚀 Object-Oriented Programming (OOPs) in Kotlin

This project demonstrates the core **Object-Oriented Programming (OOPs)** principles using **Kotlin**. OOP is a programming paradigm that revolves around objects and classes, promoting code reusability, scalability, and modularity.

---

## 🧠 What I was Learn

* 🔸 Classes and Objects
* 🔸 Constructors
* 🔸 Inheritance
* 🔸 Polymorphism
* 🔸 Abstraction
* 🔸 Encapsulation
* 🔸 Interfaces
* 🔸 Access Modifiers

---

## 🧱 Concepts & Examples

### ✅ 1. **Class & Object**

```kotlin
class Person(val name: String, var age: Int) {
    fun greet() {
        println("Hello, my name is $name and I am $age years old.")
    }
}

val person = Person("Tanzeela", 22)
person.greet()
```

---

### ✅ 2. **Inheritance**

```kotlin
open class Animal {
    fun sound() {
        println("Animal makes sound")
    }
}

class Dog : Animal() {
    fun bark() {
        println("Dog barks")
    }
}
```

---

### ✅ 3. **Polymorphism**

```kotlin
open class Shape {
    open fun draw() {
        println("Drawing shape")
    }
}

class Circle : Shape() {
    override fun draw() {
        println("Drawing circle")
    }
}
```

---

### ✅ 4. **Abstraction**

```kotlin
abstract class Vehicle {
    abstract fun startEngine()
}

class Car : Vehicle() {
    override fun startEngine() {
        println("Car engine started")
    }
}
```

---

### ✅ 5. **Encapsulation**

```kotlin
class BankAccount {
    private var balance: Int = 0

    fun deposit(amount: Int) {
        if (amount > 0) balance += amount
    }

    fun getBalance(): Int {
        return balance
    }
}
```

---

### ✅ 6. **Interface**

```kotlin
interface Drawable {
    fun draw()
}

class Rectangle : Drawable {
    override fun draw() {
        println("Drawing rectangle")
    }
}
```

---

## 🛠️ How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/YourUsername/OOP-Kotlin-Examples.git
   ```
2. Open in Android Studio or IntelliJ IDEA.
3. Run individual files to see examples in action.

---

## 📚 Resources

* [Kotlin OOPs Documentation](https://kotlinlang.org/docs/object-oriented-programming.html)
* [Kotlin Playground](https://play.kotlinlang.org/)

---

## 👩‍💻 Author

**Tanzeela Fatima**
📧 [codequeen765@gmail.com](mailto:codequeen765@gmail.com)
🌐 [LinkedIn](https://www.linkedin.com/in/tanzeela-fatima-47861b2b7/)
💻 [GitHub](https://github.com/Fatima-progmmer)

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

Let me know if you want this README customized for a specific Kotlin file or project structure.
