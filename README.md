# Assignments-SDS

# Assignment 1

### 3.1.3
    l1 = ['r ', 'Is', '>', ' < ', 'g ', '?']
    var1=l1[1]
    var2=l1[0]
    var3=l1[2]
    var4=l1[4]
    var5=l1[5]

    print(var1+" "+var2+var3+" "+var4+var5)

### 3.1.4


    words = dict()

    keys = ['animal', 'coffee', 'python', 'unit', 'knowledge', 'tread', 'arise']
​
    
    for x in keys:
        
        if x [0] in 'aeiou':
               
            print (x + ' : ' + 'True')
        
            words[x] = True
        
        else:
            
            print(x + ' : ' + 'True')
            
            words[x] = False
        

    print(words)

### 3.3.2
    
    construct_link('FOD', ['Tid=*', 'BARNKON=P'])
    

    #url = 'https://api.statbank.dk/v1/data/FOD/JSONSTAT?lang=en&Tid=*&BARNKON=P'

    
    def Function2(x) :
    
        piger = requests.get(x)
    
        piger.json()

     
        with open('piger.json', 'w') as f:
            
            piger_json_str = json.dumps(piger.json())
        
            f.write(piger_json_str)
    
        return piger

    Function2("https://api.statbank.dk/v1/data/FOD/JSONSTAT?lang=en&Tid=*&BARNKON=P")   
    


### 4.1.1

### 4.1.2

### 4.1.3

### 4.1.4
