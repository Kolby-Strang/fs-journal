# CSharp and SQL Fundamentals
01. What is the purpose of a `namespace`?

  > Grouping Imports together for ease of use throughout your program

02. What is the difference between a `class` and an `interface`?

  > | ANSWER HERE |

03. What is the method that returns an instance of a class, yet it has no return type?

  > | ANSWER HERE |

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

  > Public

06. In the Car example what is `string` an indication of?

  > The return type of the method

07. In the Car example what is `abstract` preventing?

  > | ANSWER HERE |

08. In a SQL table, what is the difference between information in a row and information in a column?

  > A column is one property that applies to all the rows on that table while a row is a single strip of data that uses all of the properties that the table it is within denotes

09. Demonstrate the necessary SQL for creating a table called `characters` with the values `name, age, description` as strings, and an `int` id.

  > CREATE TABLE IF NOT EXISTS characters(id INT PRIMARY KEY NOT NULL AUTO_INCREMENT, name CHAR(255) NOT NULL, age CHAR(255) NOT NULL, description VARCHAR(500) NOT NULL)

10. In SQL how can you query more than a single table? Provide an example.

  > | ANSWER HERE |
