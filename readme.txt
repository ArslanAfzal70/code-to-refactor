GOOD Thing About Code:
- Code  is Written in Repository pattern, due to this the BookingController is Clean code is organizeable and all the logics of database is kept in one place it would be beneficial in future if change in eloquents. Function names are meaningful. Code is Clean and understandable. 


BAD Things About Code:

- More code has been written for associative arrays, 
firstly arrays are declared like $abc = array () then values are assigned by writing each indexes on each line, we can minimize code by doing directly $data = ['key'=> $value]

- Many if else statements can be minimized with ternary operators.

- String values are used for boolean values like 'true', 'yes' - These should be true or 1 for easy and meanining full comparisons.

- Excessive variables are declared like there is no need for $data = $request->all() in each function. more variables mean more mermory aquire.