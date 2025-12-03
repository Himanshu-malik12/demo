# demo
num1 = int(input("Enter the base number for the table: "))
num2 = int(input("Enter the comparison number: "))

for i in range(1, 999):
    table_value = num1 * i
    print(f"{num1} x {i} = {table_value}")
    
    if table_value >= num2:
        print("found it")
        break
else:
    print("no match found")
    
