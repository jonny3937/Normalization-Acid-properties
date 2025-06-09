# NORMALIZATION IN DATABASE
## Introduction
Normalizatin is a technique used to organise data into databases. It is a systematic approach to remove the data redundancy and also improves data integrity.


It involves dividing a large table into smaller , more manageable pieces based on functional dependencies among attributes, ensuring that data anomallies are minimized.
Normalization is commonly used for two purpose   
- Remove data redundancy.
- Ensuring data dependencies of proper.


Without data normalization anomallies occur and it becomes difficult to handle and Update data . To understand these i'll take anexamplle using a table,
|ID    | Name    |Address   | Subject     |
|------|---------|----------|-------------|
| 201  | Akshay  |  Hamas   |  Biology    |
| 202  | Charu   |  Baha    |  Math       |
| 203  | Disha   |  Baziah  |  English    |
| 204  | Eva     |  Figi    |  French     |
- Apdation Anormally-To update address of a students who accur twice or more than twice you are required to **update** Address column in all the rows, else data will become inconsistent.
- Insertion Anormally-
- Deletion Anormally- 