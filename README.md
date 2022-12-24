# Get a list of name as an input from the user and make the first letters in caps and print each word as a list

list = []
input("Enter a list of name:")
while True:
    inp = input()
    if inp == 'z':
        break
    list.append(inp.title())
print(list)
