  # Simpletrongroup2
  # just another school proyect 
memory=[]
ejecuter=0 
def memoryxpand():
	if len(memory)==970:
		return memory
	else:
		memory.append(0)
		return memoryxpand()
print("Simpletrol 1.5.9 (bullshit bullshit etc(llenar)")

def entrys(n): 
	Nentry = input(">")
	if Nentry =="-99999":
		return startcharging(memory,0)
	else:
		memory[n]=Nentry
		Nentry = input(">")
		return entrys(n + 1)
def startcharging(p,np):
	if memory[np] != 0:
		if memory[np]== "-99999":
			print (np,">",(memory[np]))
			return ejecutar(2)
		else:
			print (np,">",(memory[np]))
			return startcharging(memory,np + 1)
	else:
		print ("carga completada,ejecutando")	
def ejecutar(a):
        if a == 2:
                return"funciona"
memoryxpand()	
entrys(0)
	

		
