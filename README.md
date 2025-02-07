# AdvitiyaCTF
Our progress for the Advitiya's CTF
## 0 - Intro
Nothing to do here :/
## 1 - The Hidden Scripture
Opening the given 4 codes on google maps gives us coordinates for 4 points, all the coordinates were near-integral so finding their corresponding characters in the ASCII table gave us the name NEBULARK
## 2 - The Vehicle Activation
## 3 - Speed Boost
While inspecting the index.html file in the browser, we came across the string "redirecting to" and "legal/iota/epsilon/eta/data.html" so going on that page, we found the first part of the flag.
For the second part of the flag, we inspected the robots.txt and went through all files in the disallowed folders and found the password in one of them. We obviously had to run a simple web server for viewing the html since the files were encoded and we couldn't read them directly.
## 4 - The Final Gateway
