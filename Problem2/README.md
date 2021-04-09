# Problem 2 - Every Time We Touch, I Get This File...

**Description:**

And every time we K.I.S.S. I swear I could fly. When you don't know what you want to do with a file, Keep It Simple Stupid, use `touch`! But remember, `touch`ing a file more than once does nothing. Given a list of `touch` commands and filenames, output the number of _unique_ files created.

**Input**:

File `input.txt` containing one command per line in the format `touch FILENAME`

**Expected Output:**

Print the **number** of unique filenames

-----

**Example Input:**

```
touch test.txt
touch something.lua
touch somewheresomehow.lua
touch something.lua
touch test.txt
touch somethingelse.js
```

**Example Output:**

`4`

--------------

**Competition Input:**

`input.txt` located in the `Problem2` folder

**Competition Output:**

`10`