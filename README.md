# Hafizzah
CSE3512
# Function to get no of set bits in binary 
def  countSetBits(n): 
    count = 0
    while (n): 
        count += n & 1
        n >>= 1
    return count 
i = input ("enter integer:")
i = int (i)
print(countSetBits(i))
