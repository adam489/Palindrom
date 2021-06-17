slowo = input("wpisz slowo lub wyraz: ")
odw_slowo = slowo[::-1]

if slowo == odw_slowo:
  print("wpisales palindrom")
else:
  print("To nie jest palidrom")