  # Simpletrongroup2
  # just another school proyect 
memory=[]
ejecuter=0 #contador
def memoryxpand():
	if len(memory)==1000:
		return memory
	else:
		memory.append([])
print("Simpletrol 1.5.9 (bullshit bullshit etc(llenar)/n /n /n")

def entrys():
	n = 0
	Nentry = input("simple>")
	if Nentry == ("ejecutar"):
		return memory
	else:
		memory[n]=Nentry
		Nentry = input("simple>")
		n+=1
		return entrys()
def executervalidations(p):
		if len(memory[0]) != 7:
			return "sintax error"
		 #iniciar validaciones
	
