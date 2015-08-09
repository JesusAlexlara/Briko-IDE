
stringbk Var;

//Codigo principal que corre por siempre
code(){

    bk7read(&Var,4);       //lee 4 bytes del serial
    if(Var.stringbuffer[0] == 'h' && Var.stringbuffer[1] == 'o' && Var.stringbuffer[2] == 'l' && Var.stringbuffer[3] == 'a' ){
    bk7led(ON);       //Prende el led del BK7
    delay(1000);      //Espera 1000 milisegundos
    bk7led(OFF);      //Apaga el led del BK7
    }
delay(10);            //Espera 10 milisegundos

}
