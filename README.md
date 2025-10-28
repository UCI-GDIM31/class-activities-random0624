# in-class-activities
## Devlogs
### W1
Hello World!!

### W2
Why are the r, g, and b variables floats instead of ints, bools, or strings?
Why is the _bounce variable an int instead of a float, bool, or string?
The error you got after Step 4 of Part 2 told you something useful about why that line of code was broken- what was it?

1. rgb variables are floats because the color spectrum contains decimals as well, so int would not work. Boolean only stores true/false, and strings store letters, not numbers.

2. The bounce variable is a counter. A counter does not have decimals, so only integer is needed.

3. To be honest, I totally forgot what I fixed. It was either the missing "f", or a missing semi-colon. The "f" is important because the variable is instantiated as a float, so you have to add it at the end of the number. I don't know why, because this doesn't exist in C/C++, but I guess that makes C# special. We need the semi-colon because it is a crucial part of the syntax. It tells the computer it is the end of the line, and it also helps you organize your code.


### W3
The method named GetResponse() should have the return type string, since we are trying to get a text response. This method should have 2 parameters. The first one is int, the friendship level with the character, and the second should be a bool, checking whether or not the player knows the character's secret. Together, the method should be:

private string GetResponse(int friendshipLvl, bool secret){}


### W4



### W5
Question: What do we use Vector3.negativeinfinity and Vector3.positiveinifinity for?

Answer: There really isn't much use for it. It could be used to represent unreachable or invalid positions, and it might be used for debugging as an output in the console.
## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 