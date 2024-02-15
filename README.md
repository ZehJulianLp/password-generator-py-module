# password-generator-py-module
This is a python module to generate a password based on the MAC address and CPU serial number of a computer.
The password is generated by concatenating the MAC address and CPU serial number and hashing the result with SHA-256.
The first 64 characters of the hash are used as the password.
The password is returned as a string.
The module also contains functions to get the MAC address and CPU serial number of the computer.
The module is tested to work on Windows and Linux.

# The module contains the following functions:
- get_mac_address: Returns the MAC address of the computer as a string.
- get_cpu_serial_number: Returns the CPU serial number of the computer as a string.
- generate_password: Generates a password based on the MAC address and CPU serial number of the computer.
  The function takes an integer length as a parameter and returns a string of the specified length.
  The length must be at least 1 and at most 64.
  If the length is not valid, the function raises a ValueError.

# How to use
1. Download the module file.
2. Drag it into your python project
3. Import the file into your project.
```python
import passwd_gen
```
