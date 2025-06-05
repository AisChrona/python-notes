# Opening Files:
f = open("filename.txt", "r")  # Modes: r, w, a, r+

# Reading:
content = f.read()
lines = f.readlines()

# Writing/Appending:
f = open("file.txt", "w")
f.write("Hello World")

# Using with block:
with open("file.txt", "r") as f:
    content = f.read()
    
# Common Modes:
r – read
w – write (overwrite)
a – append
r+ – read & write

