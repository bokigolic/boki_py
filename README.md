# am_pm_time
time = str(input("Enter time: "))
hours,minutes = time.split(":")
if "PM" in time.upper():
    
    print(hours)
    if hours == '12':
        
        print(time[:5])
    else:
        print(f"{int(hours)+12}:{minutes[:2]}")
else:
    if hours == '12':
        print(f"00:{minutes[:2]}")
    else: 
        print(time[:5])
    
    
    
    
    
    
    

    



