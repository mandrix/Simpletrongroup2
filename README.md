  # Simpletrongroup2
  # just another school proyect 
memory=[]
ejecuter=0 
def memoryxpand():
	if len(memory)==1000:
		return memory
	else:
		memory.append(0)
memoryxpand()
print("Simpletrol 1.5.9 (bullshit bullshit etc(llenar)")

def entrys():
	n = 0 
	Nentry = input(">")
	if Nentry =="-99999":
		return startcharging(memory)
	else:
		memory[n]=Nentry
		Nentry = input(">")
		n+=1
		return entrys()
def startcharging(p):
	np = 0
	if memory[np] != 0:
		if memory[np]== -99999:
			print (np ">" ,(memory[np]))
			np+=1
		else:
			print (np">","+"(memory[np]))
			np+=1
	print ("carga completada,ejecutando")
entrys()		

		
