def decrypt(cipher,s):
    result = ""
 
    # traverse text
    for i in range(len(cipher)):
        char = cipher[i]
 
        # decrypt uppercase characters
        if (char.isupper()):
            result += chr((ord(char) - s-65) % 26 + 65)
 
        # decrypt lowercase characters
        else:
            result += chr((ord(char) - s - 97) % 26 + 97)
 
    return result
 
#check the above function
cipher = "KhoorUdpdqxmdq"
s = 3
print ("cipher  : " + cipher)
print ("Shift : " + str(s))
print ("text: " + decrypt(cipher,s))
