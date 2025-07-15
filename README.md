def rstring(s):
    if len(s)==0:
        return s
    return rstring(s[1:])+s[0]
text=input("enter a word")
print(rstring(text))
********output********
enter a word joshika
akihsoj
