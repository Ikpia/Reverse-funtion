# Reverse-funtion
# this function reverses small letters in a given string
letters = ['a','b','c','d','e','f','g','h','i','j','k','l','m','n','o','p','q','r','s','t','u','v','w','x','y','z']
rev = list(reversed(letters))
def reverse(string):
    translation = ' '
    for i in string:
        if i.islower():
            translation += rev[letters.index(i)] 
        else:
          translation += i
    print(translation)      
reverse('AAAaaaa aaa AAAaa')    
