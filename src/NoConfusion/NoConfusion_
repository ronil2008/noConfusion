class DontConfuse:
    
    @classmethod
    def NormalRange(cls, x, y):
        return range(x, y + 1)
    
    @classmethod
    def Set_STR_Limit(cls, string: str, i0: int, i1: int, mode='Module.Default'):
        if mode == 'Module.Default':
            return string[i0:i1 + 1]
        elif mode == 'Python.Default':
            return string[i0:i1]
        elif mode == 'Module.False':
            return string[i0 + 1:i1]
    
    @classmethod
    def GetLastIndexOf(cls, string: str):
        return len(string) - 1
    
    @classmethod
    def removeFirstAndLastFrom(cls, string: str):
        return string[1:len(string) - 1]
