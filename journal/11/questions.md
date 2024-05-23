# A bit more CSharp and SQL
1. What does ***inheritance*** accomplish for us in C#?

  > It allows us to avoid repeating ourselves as much.

2. How does ***member inheritance*** work in C#? Does a `Class` inherit all members of the base `Class`?

  > It inherits any members that arent private

3. How does ***accessibility*** affect inheritance?

  > private members can't be inherited

4. What is the difference between a `PRIMARY KEY` and a `FOREIGN KEY`

  > Primary key is what is used as the reference for rows in a table; a foreign key is what we check in a separate table to get data from it in ours.

5. What is an ***alias***?

  > An alias is a variable name essentially.

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

  > SELECT
    *
    FROM
    PATIENTS
    WHERE patient_doctors.doctorId = @doctorId
