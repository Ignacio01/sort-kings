# sort-kings
This program sorts the kings by their names, and in case they have the same names, they will be sorted by their roman number.

I created a class King, with the fields:
    · String name // Contains the name of the King
    · String romanNumber // Contains the roman number of the king
    · int numberKing // Contains the number of the King but converted to integer

The method convertRomanToNumber() in the class King:
  Will convert the roman number when a new object King will be created.
  It is called also when the roman number is being change by calling the Setter setRomanNumber(String romanNumber).
  
I also Overrided the class compareTo, so when two kings have the same name, it compares the value of the roman numbers.
