# JavaLab_Session4
Java program demonstrating polymorphism and abstract classes in a banking scenario.

This program showcases the use of abstract classes, method overriding, and dynamic dispatch to model different types of bank accounts.

An abstract class Account is created with common attributes like accountHolder and balance, and an abstract method calculateInterest().

The SavingsAccount class extends Account, adding an interest calculation, while the CurrentAccount class extends Account and demonstrates service charges with no interest.

In the main method, Account references are used to hold objects of SavingsAccount and CurrentAccount, demonstrating polymorphism through dynamic method dispatch.

This illustrates how subclasses can provide specific implementations of abstract methods while reusing parent class functionality.

## Program Output:

Account Holder: Sam
Balance: 50000.0
Savings Account Interest: 2000.0


Account Holder: Raj
Balance: 30000.0
Current Account has no interest. Service charge: 100.0
