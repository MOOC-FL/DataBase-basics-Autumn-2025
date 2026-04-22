
#### Column Conditions in SQL

| Condition | Description | Syntax Example (CREATE TABLE) |
| :--- | :--- | :--- |
| **`UNIQUE`** (Single Column) | Ensures all values in a column are different across rows. | `name TEXT UNIQUE` |
| **`UNIQUE`** (Multiple Columns) | Ensures no two rows have the same combination of values in the specified columns. | `UNIQUE(name, price)` |
| **`NOT NULL`** | Prevents a column from containing a `NULL` (empty/missing) value. | `price INTEGER NOT NULL` |
| **`DEFAULT`** | Assigns a default value to a column if no value is provided during row insertion. | `price INTEGER DEFAULT 0` |
| **`CHECK`** | Allows a custom boolean condition that must be `true` for the data to be accepted. | `CHECK (price >= 0)` | 
