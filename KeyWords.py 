def  multiply_and_greet(*args,**kwargs): 

    keys=kwargs.keys()
    multiple=1 
    for num in args: 
        multiple*=num
    print(multiple)  
    if "age" in keys: 
        print(f"Hello {kwargs['name']} you live in {kwargs['city']} at the age {kwargs['age']}")    
    elif "city" in keys: 
        print(f"Hello {kwargs['name']} you live in {kwargs['city']} in Kenya") 
    elif "name" in keys: 
        print(f"Hello {kwargs['name']}")      
   
    else: 
        print("Hello anonymous") 