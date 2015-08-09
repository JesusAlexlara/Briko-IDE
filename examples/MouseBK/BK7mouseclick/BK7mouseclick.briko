
buttonsbk Buttons(PORT1);    // Declara el modulo de botones en el puerto 1
int boton;                   // Variable para guardar el boton que presionas
bool pressed=0;

//Codigo principal que corre por siempre
code(){

boton = Buttons.read();                    //Lee que boton presionas

if(boton==1 && pressed==0){
bk7mouseclick(MOUSE_LEFT);                 //Click izquierdo del mouse
pressed=1;
}

if(boton==5){
bk7mouseend();                             //Cierra los recursos del mouse
}

if(boton==0){
pressed=0;
}

}
