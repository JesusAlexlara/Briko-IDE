
buttonsbk Buttons(PORT1);    // Declara el modulo de botones en el puerto 1
int boton;                   // Variable para guardar el boton que presionas
bool pressed=0;
int x=127;
int y = 127;

//Codigo principal que corre por siempre
code(){

boton = Buttons.read();                    //Lee que boton presionas

if(boton==1 && pressed==0){
x = x+10;                                  //Aumenta valor de x
if(x>255){x=255;}
pressed=1;
}

if(boton==2 && pressed==0){
x = x-10;                                  //Disminuye valor de x
if(x<0){x=0;}
pressed=1;
}

if(boton==3 && pressed==0){
y = y+10;                                  //Aumenta valor de y
if(y>255){y=255;}
pressed=1;
}

if(boton==4 && pressed==0){
y = y-10;                                  //Disminuye valor de y
if(y<0){y=0;}
pressed=1;
}

if(boton==5){
bk7mouseend();                              //Cierra los recursos del mouse
}

if(boton==0){
pressed=0;
bk7mouserelease(MOUSE_LEFT);
}

bk7mousemove(x,y);                         //Mueve el mouse
delay(10);                                          //Espera 10 milisegundos

}
