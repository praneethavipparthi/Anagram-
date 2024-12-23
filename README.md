# Anagram-checker-Project
I did this project using python programming language. I used if,else,elif functions.
#To check whether the given strings are anagrams or not
def menu():
    print("=>Defination: A word, phrase, or name formed by rearranging the letters of another, such as earth, formed from heart.")
    print("=>Hey! Give me two words i will say they are anagrams or not")
menu()

str1=input("word1:")
str2=input("word2:")

if len(str1)!=len(str2):
    print("These words are not anagrams")
    print("=>Sorry you are wrong.You can try again")
else:
    if sorted(str1.upper())==sorted(str2.upper()):
        print("These words are anagrams")
        print("=>Yes!You are right")
    else:
        print("These words are not anagrams")
        print("=>Sorry you are wrong.You can try again")
