
## Programas  c++ de Bedoya Napa Stefany Mishelle
====================
## Información del Autor 
> Estudiante: Bedoya Napa Stefany Mishelle
> Correo Electrónico: stefany.bedoya.napa@utelvt.edu.ec
> Celular: 0967415020
## Programas
1.-BedoyaStefany-Compara.cpp
2.-BedoyaStefany-CuentaMoneda.cpp
3.-BedoyaStefany-PuntoVenta.cpp
4.-BedoyaStefany-SumaN.cpp
5.-BedoyaStefany-laedad.cpp
# Descripción de los programas 
### BedoyaStefany-Compara.cpp
Este programa en C++ permite comparar dos números y determinar si son iguales , si uno es mayor o menor.
### BedoyaStefany-CuentaMoneda.cpp
Este programa en C++ permite determinar la Suma de varias  monedas y de sus respectivas denominaciones.
### BedoyaStefany-PuntoVenta.cpp
Este programa en C++ permite determinar el valor a pagar por la compra de distintos productos tomando en cuenta el IVA y su respectivo Descuento.
### BedoyaStefany-SumaN.cpp
Este Programa en C++ permite determinar el resultado al sumar varios números.
### BedoyaStefany-laedad.cpp
Este programa en C++ permite calcular la edad de una persona.
# Funcionalidad
### BedoyaStefany-Compara.cpp
```
float SN_x,SN_y;
```
### Salida
```
si(SN_x==SN_y) //===> Son iguales.
si(SN_x<SN_y) //===> Y es el mayor , caso contrario X es mayor.
```
### BedoyaStefany-CuentaMoneda.cpp
```
int SN_n,SN_c=0,SN_c1=0,SN_c2=0,SN_c3=0;
float SN_x,SN_a=0,SN_a1=0,SN_a2=0,SN_a3=0;
```
### Salida
```
SN_c,SN_a,SN_c1,SN_a1,SN_c2,SN_a2,SN_c3,SN_a3  //===> Suma total de las monedas , suma de las monedas según su denominación por separado.
```
### BedoyaStefany-PuntoVenta.cpp
```
int SN_C=0,SN_P;
float SN_A=0,SN_x,SN_Tb,SN_PIVA,SN_Pdsc,SN_IVA=0.12,SN_dsc=0.25,SN_VT;
```
### Salida
```
SN_Tb,SN_IVA,SN_dsc,SN_VT //===> Valor total a pagar ,total bruto , IVA y descuento.
```
### BedoyaStefany-SumaN.cpp
```
int SN_C=0,SN_b;
float SN_S=0,SN_x;
```
### Salida
```
SN_S //===> La suma total de los números.
```
### BedoyaStefany-laedad.cpp
```
int SN_dd,SN_mm,SN_yy,SN_dd1,SN_mm1,SN_yy1,SN_da,SN_ma,SN_ya;
```
### Salida
```
SN_ya,SN_ma,SN_da //===> Su edad.
```
# Instalación
1.- Descargar F-Droid.
```
https://f-droid.org/
```
2.- " Una vez dentro de la aplicación F-droid".
```
Descargar la terminal (Termux) junto a todas su actualizaciones.
```
3.- Ingresar a la terminal(Termux) e instalar los paquetes de datos necesarios.
```
//===> pkg install git
//===> pkg install vim
//===> pkg install clang 
//===> pkg install g++ 
//===> apt update
//===> apt upgrade
```
```

### Descaragar el repositorio a la Terminal (Termux) 
1.-Clonar el repositorio en la maquina local.
```
git clone https://github.com/Mishelle8/ACTIVIDAD-E2.git
```
2.- Ingresar al Repositorio.
```
cd ~

cd ACTIVIDAD-E2
```

# Compilar y Ejecutar.
```
g++ BedoyaStefany-Compara.cpp -o BedoyaStefany-Compara
//===> Lo mismo se debe de realizar con los demás programas.
```
```
./BedoyaStefany-Compara
//===> Lo mismo se debe de relaizar con los demás programas.
```


