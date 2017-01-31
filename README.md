# Greatest-Common-Divisor
Calculate GCD from two numbers

n1=int(input('Enter 1st number: ')) #reading 1st number from user and converting it to integer

n2=int(input('Enter 2nd number: ')) #reading 2nd number from user and converting it to integer

if n1 > 0 and n2 > 0: #if 1st number and 2nd number are greater than 0 then proceed

    for i in range(1,max(n1,n2)): #for 1 to the greatest of the two numbers
    
        if n1 % i == 0 and n2 % i ==0: #if 1st number and 2nd number division do not have reminders then proceed
        
            GCD=i #assigning greatest common divisor to variable
            
    else:
    
        if GCD==0: #if greatest common divisor not found print it
        
            print('GCD not found')
            
    print('GCD of ' + str(n1) + ' and ' + str(n2) + ' is: ' + str(GCD)) #print greatest common divisor results
    
else: #if numbers are less or equal than zero then print 'Numbers not valid'

    print('Numbers not valid')
    
