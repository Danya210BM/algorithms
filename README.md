ALGORITHM light
BEGIN
SWITCH (color) DO
    case "green" : write("go")
    case "yellow" : write("slow down")
    case "red": write("stop")
    default : ("unknow request.")
END_SWITCH
END
ALGORITHM sum
VAR a,b,c,d,e,sum:INTEGER
BEGIN
write("enter your 5 numbers:")
read(a,b,c,d,e)
sum ←a+b+c+d+e
IF (sum<100) THEN
    print("The sum of your numbers is inferior to 100.")
ELSE
    print("the sum of your numbers is bigger than 100.")
END_IF
END
LGORITHM  YES
BEGIN
WHILE 
        if answer ="yes":
        print("You answered yes!")
    if answer ="no":
        print("You answered no. Please try again.")
        else:
        print("Invalid input. Please answer yes or no.")
END_WHILE
END
