# Draw-a-triangle-with-stars
while 1:
    h = input("Enter the height of the triangle: ") 
    if h =="0":
        break
    for i in range(1 , int(h)+1):
        print("*"* i)
