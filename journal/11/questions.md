# A bit more CSharp and SQL
1. What does ***inheritance*** accomplish for us in C#?

  > It allows subclasses to have access to general purpose methods that make it easier to negate redundant code

2. How does ***member inheritance*** work in C#? Does a `Class` inherit all members of the base `Class`?

  > When a class inherits another class it gains access to all of the super classes variables and methods

3. How does ***accessibility*** affect inheritance?

  > Some methods that a superclass has can be private and will not be inherited by the subclass

4. What is the difference between a `PRIMARY KEY` and a `FOREIGN KEY`

  > The primary key defines a property as not null and makes it easier to recognize as the primary way to search for rows in that table

5. What is an ***alias***?

  > an alias is an alternate shorter name for a variable that makes it easier to use through code snippets

6. Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

  ```SQL
  CREATE TABLE doctors (
    id INT NOT NULL AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
  )

  CREATE TABLE patients (
    id INT NOT NULL AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
  )

  CREATE TABLE patient_doctors (
    id INT NOT NULL AUTO_INCREMENT,
    doctorId INT NOT NULL,
    patientId INT NOT NULL,

    FOREIGN KEY (doctorId)
      REFERENCES doctors(id),
    FOREIGN KEY (patientId)
      REFERENCES patients(id),
  )

  ```

  > SELECT pat.*, patDoc.*, doc FROM patients pat JOIN patient_doctors patDoc ON patDoc.doctorId = doc.id JOIN doctors doc ON doc.id = patDoc.doctorId;
