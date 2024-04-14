#Que1: Write a code to reverse a string
original_name = "Karandeep Kaur"
reverse_name=original_name[::-1]
reverse_name

#Que 2:Write a code to count the number of vowels in a string

_string = input("Enter string:")
_count_vowels=0
for i in range(0,len(_string)):
  if _string[i] in ('a','e','i','o','u','A','E','I','O','U'):
    _count_vowels=_count_vowels+1
print(_count_vowels)

# Que 3: Write code to check if given string is palindrome or not.
_string = input("Enter string:" )
_string = _string.lower()
_reverse_string = _string[::-1]
_forward_string = _string[0::]
if (_reverse_string == _forward_string):
  print ("The given string is palindrome:", _string)
else:
  print("The given string is not palindrom:" , _string)
