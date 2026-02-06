       #how to replace a specific word at sentence
r = "This is the best food, best in the food, I love food"

first = r.find("food")
print(first)
second = r.find("food", first + 1)
print(second)
result = r[:second] + "kerolos" + r[second + len("food"):]

print(result)

       
