  # Simpletrongroup2
  # just another school proyect 
memory=[]
ejecuter=0 #contador
def memoryxpand():
	if len(memory)==1000:
		return memory
	else:
		memory.append([0])
print("Simpletrol 1.5.9 (bullshit bullshit etc(llenar)")

def entrys():
	n = 0 #cambiar por la posicion de la input
	Nentry = input(">")#agregar posicion en memoria
	if Nentry == ("ejecutar"):
		return executervalidations(memory)
	else:
		memory[n]=Nentry
		Nentry = input("simple>")
		n+=1
		return entrys()
def executervalidations(p):
		if len(memory[0]) != 6:
			return "sintax error"
		 #iniciar validaciones
	
