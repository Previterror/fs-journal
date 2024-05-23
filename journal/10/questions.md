# CSharp and SQL Fundamentals
01. What is the purpose of a `namespace`?

  > organisation?

02. What is the difference between a `class` and an `interface`?

  > an interface includes a bunch of required methods

03. What is the method that returns an instance of a class, yet it has no return type?

  > void

05. In the Car example what is the access modifier of the `Start()` method?

  ```c#
  abstract class Car
  {
    public string Start()
    {

      return "Vroooom";

    }
  }
  ```

  > public

06. In the Car example what is `string` an indication of?

  > the return type

07. In the Car example what is `abstract` preventing?

  > Instantiatingthat object

08. In a SQL table, what is the difference between information in a row and information in a column?

  > A row is a discrete object of data a column is a type of data.

09. Demonstrate the necessary SQL for creating a table called `characters` with the values `name, age, description` as strings, and an `int` id.

  > 

10. In SQL how can you query more than a single table? Provide an example.

  > joins

  Join accounts On accounts.id = accountid
