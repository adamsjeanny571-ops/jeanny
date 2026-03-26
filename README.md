# jeanny
string binary = ""; // Initialize empty string to store binary representation

while (decimal > 0) {
    binary = to_string(decimal % 2) + binary; // Append remainder to binary string
    decimal /= 2; // Divide decimal number by 2
}  

return binary; 
 
