# Python-File-Write
# Write to an Exiting File
To write to an exiting file, you must add a parameter to the open() function:

"a" - Append - Will to the end of the file

"w" - Write - Will overwrite any exiting content

Example

Open the file "demofile2.txt" and append content to the file:

    f = open("demofile2.txt", "a")
    f.write("Now the file has more content!")
    f.close()

    # Open and read the file after the appending

    f = open("demofile2.txt", "r")
    print(f.read())
