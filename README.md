def rstring(s):
    if len(s)==0:
        return s
    return rstring(s[1:])+s[0]
text=input("enter a word")
print(rstring(text))
********output********
enter a word joshika
akihsoj



def sumnum(*args):
    print(args[4])
    return sum(args)
print(sumnum(1,2,3,4,5,6,7,8,9,10))
********output********
5
55
