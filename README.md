Unit Converter (temp, volume, mass)
- Converts various units between one another. The user enters the type of unit being entered,
    the type of unit they want to convert to and then the value.
    The program will then make the conversion.


Temparture converter-done

    1. Create a "To Celsius" class and a "To Farenheit" class and "To Kelvin" class
    2. Method that will request to pick F to C or C to F and send the data to the Class to work on
   - Formulas used:
       -  "F = (input × 9/5) + 32 = output"
       -  "K = input + 273.15"
       -  "C = (input-32) (5/9)"
       -  "K = (input-32) (5/9) + 273.15"
       -  "F = (K-273.15) (9/5) + 32"
       -  "C = K - 273.15"


Volume converter

    - 1. Class for basic conversion using the S * C = E formuala Class for having an intenal
        method that will take care finding and using the necessary conversion metric based on the inputed user values
    - 2. Method that will take a value from a specific Dictionary called vol_table that
        contains full name of the unit, unit symbol, unit metric based on the cubic meter 3.
        -The main formula functions as such OUT = (value*input unit metric)/conversion to metric

Mass converter

    - 1. Class for having an intenal method that will take care finding and using
        the necessary conversion metric based on the inputed user values
    - 2. Method that will take a value from a specific Dictionary called mass_table that
        contains full name of the unit, unit symbol, unit metric based on the cubic meter 3.
        -The main formula functions as such OUT = (value*input unit metric)/conversion to metric
