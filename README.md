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
	
def operaciones(num):
    if num >= 10000 or num <= 10999:
        num % 1000
        #return leer

    elif num >= 11000 or num <= 11999:
        num % 1000
        #return escribir
    elif num >= 20000 or num <= 20999:
        num % 1000
        #return carga
    elif num >= 21000 or num <= 21999:
        num % 1000
        #return almacena
    elif num >= 30000 or num <= 30999:
        num % 1000
        #return suma
    elif num >= 31000 or num <= 31999:
        num % 1000
        #return resta
    elif num >= 32000 or num <= 32999:
        num % 1000
        #return multiplica
    elif num >= 33000 or num <= 33999:
        num % 1000
        #return divide
    elif num >= 34000 or num <= 34999:
        num % 1000
        #return modulo
    elif num >= 35000 or num <= 35999:
        num % 1000
        #return exponente
    elif num >= 40000 or num <= 40999:
        num % 1000
        #return bifurca
    elif num >= 41000 or num <= 41999:
        num % 1000
        #return bifurca negativo
    elif num >= 42000 or num <= 42999:
        num % 1000
        #return bifurca cero
    elif num >= 43000 or num <= 43999:
        num % 1000
        #return bifurca positivo
    elif num >= 44000 or num <= 44999:
        num % 1000
        #return parar
    elif num >= 45000 or num <= 45999:
        num % 1000
        #return limpiar acumulador
    #elif num == -9999:
        #return ejecutar

    else:
        return "Número no valido"
		
