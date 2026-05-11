Pat2-subtask-1
morse code
# PAT 2 Subtask 1: Morse Code Research

## 1. Brief Overview of Morse Code
Morse code is a method of encoding text characters into sequences of short and long signals called dots (.) and dashes (-). It is used to transmit messages over telegraph, radio, and light signals. Each letter, number, and punctuation mark has a unique pattern of dots and dashes.

**Example:
`A` = `.-`  
`SOS` = `... --- ...`

## 2. Historical Context
Morse code was developed in the 1830s and 1840s by Samuel Morse and Alfred Vail for use with the electrical telegraph. Before Morse code, long-distance communication was slow and limited to physical mail.  

The system became widely adopted because it allowed operators to send messages quickly over long distances using electrical pulses. It was crucial for maritime communication, military operations, and early aviation. In 1999, the U.S. stopped using Morse code for maritime distress calls, but it is still used by amateur radio operators and in some emergency signaling.

## 3. How the Morse Code System Works
Morse code works by assigning each character a specific sequence of dots and dashes:
- **Dot (.)**: A short signal, usually 1 time unit.
- **Dash (-)**: A long signal, usually 3 time units.
- **Space between letters**: 3 time units.
- **Space between words**: 7 time units.

Translators convert English text to Morse by replacing each character with its corresponding pattern. In C++, this is commonly done using an array where index 0 = A, index 1 = B, etc.

### A-Z Morse Code Table
| Letter  Code  Letter  Code |
| --- | ---  --- --- 
| A | .-    N -. 
| B | -...  O  --- 
| C | -.-.  P  .--. 
| D | -..   Q  --.- 
| E | .     R  .-. 
| F | ..-.  S ... 
| G | --.   T  - 
| H | ....  U ..- 
| I | ..    V  ...- 
| J | .---  W  .-- 
| K | -.-   X -..- 
| L | .-..  Y  -.-- 
| M | --    Z --.. 


## 4. References
1. Britannica. *Morse Code*. https://www.britannica.com/technology/Morse-code
2. International Telecommunication Union. *ITU-R M.1677-1: International Morse code*. 2009.
3. Wikipedia. *Morse code*. https://en.wikipedia.org/wiki/Morse_code


