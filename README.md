# DigitalElectronics2_Lab3
Lab3
# Lab3: Raúl Gómez
## Link
Link to my github: 
(https://github.com/raulgoi/DigitalElectronics2_Lab3/blob/7b8618d9650b9f375a8e065e59a9482ebc282559/README.md)

## Fill the table

Data type | Number of bits | Range | Description |
--------- | -------------- | ----- | ----------- |
uint8_t   |       8        | 0 - 255 | Unsigned 8-bit integer |
int8_t |     8   |  -128 - 127  |  Signed 8-bit integer |
uint16_t |  16  |  0 - 65353  | Unsigned 16-bit integer |
int16_t |   16   | -32768 - 32767 | Signed 16-bits integer |
float |  | -3,4e38 - 3,4e38  | Single-precision floating-point |
void | |  | specifies that the function does not return a value |

## Differences

*Explain the differences between function declaration-definition*

* The definition of an element of the program, determines the value associated with that element. In other part, the declaration of a program element specifies its name and type to the compiler.
* The definition reserve a certain amount of memory, while the declaration doesn`t imply memory allocation.
* A program element can be declarated many times. On the other side, the definition incorporates a unique specification with the name of the program element that could be distinguished by any code or data.
* The scope in the declaration describes the visibility of the variable, function, object, class, enum, etc. In contrast, in the definition scope is related to duration.


## Code C++

    // Configure Push button at port D and enable internal pull-up resistor
    // WRITE YOUR CODE HERE
    

    // Infinite loop
    while (1)
    {
        // Pause several milliseconds
        _delay_ms(BLINK_DELAY);

        // WRITE YOUR CODE HERE
    }






## Scheme


![Lab 3](https://user-images.githubusercontent.com/91128806/136802316-e2b1224e-d1b7-4f4c-8a3a-26c08037d41d.png)

