

file=open("Desktop/sample.txt","rt")
data=file.read(100)
print(data)
occurrences=data.count("resolve")
words=data.split()


print("number of words in text file:",len(words))
print(" number of occurrences of word:",occurrences)



output:
We resolve to be brave.We resolve to be good. We resolve to uphold the law according to our oath.
number of words in text file: 19
 number of occurrences of word: 3
