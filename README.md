# initial-stage

ip = 'Welcome to the Python Project'
l = len(ip) - 1
x = 0

def reversal(ip):
  while(x <= l):
    global l
    global x
    print(ip[l])
    l = l - 1
   
reversal()
    
