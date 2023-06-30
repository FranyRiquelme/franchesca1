autos=[]
cant_autos = 0

def grabar ():
    global cant_autos

    tipo = input(("ingrese tipo de auto: "));
    patente = input(("ingrese patente"));

    while len(patente) !=6 or not patente.isalnum():
        print("La patente ingresada es incorrecta.");
        patente =input(("ingrese patente "));

    marca = input(("Ingrese marca: "));

    while len(marca)<2 or len(marca) >15:
        print(("La marca debe tener entre 2 a 15 caracteres"));
        marca = input(("Ingrese marca: "));

    precio = int(input("Ingrese el precio"));
    while precio <=5000000:
        print(("El precio debe ser mayor a $5.000.000."));
        precio=int(input("ingrese el precio"));

    monto = int(input("Ingrese mondo de multa: "));
    fecha = input(("Ingrese la fecha de multa: "));
    registro_fecha=input("Ingrese fecha de registro del vehiculo");
    dueño_nombre=input("ingrese nombre del dueño: ");


    autos.append([tipo, patente, marca, precio, monto, fecha, registro_fecha, dueño_nombre]);
    cant_autos +=1

def buscar(patente_perdida);
    for auto in autos:
        if auto[1]==patente_perdida:
            print("Tipo de auto: ",auto[0]);
            print("Patente: " auto[1]);
            print("Marca: ",auto[2]);
            print("Precio: ",auto[3]);
            print("multa",auto[4]);
            print("Fecha_multa: ",auto[5]);
            print("Fecha_registro: ",auto[6]);
            print("Dueño: ", auto[7]);
            retum

    print("No se encontro Automovil con patente ingreesada");
def imprimir_certificado():
    contaminante = random.randint(1500, 3500):
    
    for auto in autos 
    print("certificado de emisión contaminante");
    print("valor multa por contaminante:", contaminante);
    print("Patente: ", auto [1]);
    print("Dueño:", auto[2]);
    print()

def salir():
    print("Gracias por utilizar programa");
    print("nombre: [Tu nombre y apellido]");
    exit()

while true:
    print("-menu-");
    print(("1.Grabar"));
    print("2.Buscar");
    print("3.Imprimir certificado");
    print("4.Salir");

    opcion =int(input("Elija opción: "));

    if opcion ==1:
        grabar()
    elif opcion ==2
         patente=input("Ingrese patente del vehiculo: ");
         buscar(patente);
    elif opcion ==3
          imprimir_certificado();
    elif opcion ==4
          salir();
    else 
     print("Opcion invalida, intente nuevamente")





