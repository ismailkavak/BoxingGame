# Fighter Battle Simulator

This Java project implements a simple fighter battle simulator where users can create instances of fighters with different attributes and watch them engage in a match. The project consists of three main classes:

## Fighter Class

The `Fighter` class represents a combatant with attributes such as name, damage, health, weight, and dodge. The constructor ensures valid dodge values, and methods simulate attacks and dodges.

## Main Class

The `Main` class serves as the entry point, creating instances of fighters (e.g., Muhammed and Poyraz) and initiating a match.

## Match Class

The `Match` class orchestrates the battle between two fighters, considering factors like dodge chance and weight constraints. The simulation progresses through rounds until one fighter's health reaches zero or a specified number of rounds is completed.

## Usage

To run the simulation, create instances of the `Fighter` class, initialize a `Match`, and call the `run` method.

```java
public static void main(String[] args) {
    Fighter muhammed = new Fighter("Mohad", 10, 120, 100, 99);
    Fighter poyraz = new Fighter("Poyraz", 8, 110, 80, 50);

    Match match = new Match(muhammed, poyraz, 60, 150);
    match.run();
}
```

## Learnings

During the implementation, key concepts such as Object-Oriented Programming, conditional statements, looping structures, and randomization were practiced. The project provides an introductory hands-on experience in Java programming, offering flexibility for further customization and exploration.



