
# Notes

* ⚠️ **WIP**  
* ✅ **GREEN**  
* 🧠 **In Discovery**  
* ❌ **RED**  
* 📝 **TBD**  

### Goal: 
### Time 🍅
### Notes:

The Kata:
Given a number n, draw stairs using the letter "I", n tall and n wide, with the tallest in the top left.

For example n = 3 result in:

"I\n I\n  I"
I
 I
  I

UAT
- The user can give a number which represents the number of steps in the stair
- The system can print the given number of steps:
  - 1
  - 2
  - 10
  - Any number
- The user cannot enter a negative number
- The user cannot enter a number over 50 (assumption about requirment)
- The user cannot enter an invalid character (has to be an in between 0 and 50)


Teststrategy - unit tests to drive the code
- We can receive a 0 and print an empty string
- We can receive the number 1 and print one I = one step in the stair
- We can receive the number 2 and print two I = two steps in the stair
  - Example:
  - I
  -  I
- We can receive the number 10 and print 10 steps in the stair
- We can not recieve a negative number
- We can not receive a number under 51