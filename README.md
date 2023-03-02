# Brute-force-password-cracker

![Cracker](https://user-images.githubusercontent.com/76782671/222556885-ae293fd9-383d-4b40-83c2-d53c07b01c74.png)</center>

This is a simple password-cracker using the brute-forced method. 
<br>

I made it for the ___「Code First: Girls」Python challenge by DSTL___.

# About
This password cracker uses the brute-force method to check if the input that was entered by a user matches against 2 functions, then outputs the result.

A Function Called: ___Set_Character_Limitations___

It checks:
- If the length matches the allowed length, if not, recalls itself.
- If the characters inputted matches against a set of allowed characters, if not, recalls itself.
- If the above checks correct, the input passes to the next function.

A Function Called: ___Password_Cracker___
- The input is then passed to a for-loop where each character is iterated.
- The input entered is then checked if it is a numeric, alphabetic or a special character.
- A while loop is used to check if the character entered is the same as a random character created by the random module.
- The random module is used here to randomise the checking from the defined set.

If matched, it then appends to a final 'cracked_password' list, and finally returns it with a print statement.
<br>
![Screenshot2](https://user-images.githubusercontent.com/76782671/222561206-c680da51-5c2f-4f9c-bd2b-076fccd20e59.png)


# Team Version
Here's the link for the final version sumbitted by our group: 
<br>
https://github.com/goldfishdolphin/team-indigo
