# Python code to find number of occurences of a digit in a number in recursive mode.

def count7(N):
  if(N < 9):
    if(N == 7):
      return 1
    else:
      return 0
  else:
    if(N % 10 == 7):
      return 1 + count7(N//10)
    else:
      return 0 + count7(N//10)
