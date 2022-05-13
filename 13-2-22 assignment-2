class Solution:
    def isValid(self, s: str) -> bool:
        s = s.replace(' ','')
        if len(s)%2 != 0:
            return False
        dict = {'(' : ')', '[' : ']', '{' : '}'}
        ar = []
        for i in s:
            if i in dict:
                ar.append(i)
            else:
                if not ar:
                    return False
                pop = ar.pop()
                if i != dict[pop]:
                    return False
        return ar == []
