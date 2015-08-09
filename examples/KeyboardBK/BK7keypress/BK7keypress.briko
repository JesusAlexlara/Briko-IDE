
buttonsbk Buttons(PORT1);    // Declara el modulo de botones en el puerto 1
int boton;                   // Variable para guardar el boton que presionas

//Codigo principal que corre por siempre
code(){

boton = Buttons.read();                   //Lee que boton presionas

if(boton==1){
bk7keypress(KEY_BACKSPACE);               //Presiona la tecla borrar
}

if(boton==5){
bk7keyend();                              //Cierra los recursos del teclado
}

if(boton==0){
bk7keyrelease(KEY_BACKSPACE);
//bk7keyreleaseall();
}

}
