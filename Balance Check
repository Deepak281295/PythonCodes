#Balance Check
def balance_check(s):
    dic={'(':')','[':']','{':'}'}
    a = stack()
    for i in range(len(s)):
        if (s[i] == '(' or s[i] == '{' or s[i] == '[' ):
            a.push(s[i])
            
        elif (a.peek()!="Empty Queue" and s[i]==dic[a.peek()]):
            a.pop()
            print(vars(a))
            
        else:
            a.push(s[i])
    return a.peek()=="Empty Queue"
balance_check("[()]([]))")
