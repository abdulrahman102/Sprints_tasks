### This python program used to check if a given year is leap or not. 
#### The code :  
    #!/usr/bin/python3
    #The above line is to specify the python interpeter

    #Function to check the leap year
    def check_leap(year):
        if year % 4 == 0 :
            if year % 100 == 0:
                if year % 400 == 0 :
                    return f"{year} is a leap year."
            else:
                return f"{year} is a leap year."
        return f"{year} is not a leap year."   

    #Function that takes user input
    def user_input():
        while True:
            try:
                user_year = int(input("What year do you like to check?: "))
                break
            except ValueError:
                print("Please Enter a valid integer.")    
        return user_year

    #The Script
    print(check_leap(user_input()))
#### The execution screeshot:   
![](https://github.com/abdulrahman102/Sprints_tasks/blob/master/sprint_6/python2_leap_year/Leap_year_run.png)
