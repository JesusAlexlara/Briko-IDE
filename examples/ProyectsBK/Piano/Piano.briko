
byte Piano_1[5];                         //Crea un arreglo para leerel primer modulo de botones
byte Piano_2[5];                         //Crea un arreglo para leer el segundo modulo de botones

buzzerbk buzzer(PORT1);                  //Declara el modulo de buzzer en el puerto 1
buttonsbk modulo_botones(PORT2);         //Declara el modulo de botones en el puerto 2
buttonsbk modulo_botones2(PORT3);        //Declara el modulo de botones en el puerto 3

int Button_pressed=0;                    //Para saber si presionas un boton

//Codigo principal que corre por siempre
code(){

  modulo_botones.read(Piano_1);          //Lee el modulo de botones
  modulo_botones2.read(Piano_2);         //Lee el modulo de botones
  Button_pressed=0;                      //Para saber si presionas un boton

//Toca una diferente nota dependiendo de que boton presiones

  if (Piano_1[0] == 1){
      buzzer.playTone(NOTE_B3);          //Plays B3 Note in buzzer
      Button_pressed=1;                  //Para saber si presionas un boton
  }

  if (Piano_1[1] == 1){
      buzzer.playTone(NOTE_C4);         //Plays C4 Note in buzzer
      Button_pressed=1;                 //Para saber si presionas un boton
  }

  if (Piano_1[2] == 1){
      buzzer.playTone(NOTE_D4);         //Plays D4 Note in buzzer
      Button_pressed=1;                 //Para saber si presionas un boton
  }

  if (Piano_1[3] == 1){
      buzzer.playTone(NOTE_E4);         //Plays E4 Note in buzzer
      Button_pressed=1;                 //Para saber si presionas un boton
  }

  if (Piano_1[4] == 1){
      buzzer.playTone(NOTE_F4);         //Plays F4 Note in buzzer
      Button_pressed=1;                 //Para saber si presionas un boton
  }

  if (Piano_2[0] == 1){
      buzzer.playTone(NOTE_G4);         //Plays G4 Note in buzzer
      Button_pressed=1;                 //Para saber si presionas un boton
  }

  if (Piano_2[1] == 1){
      buzzer.playTone(NOTE_A4);         //Plays A4 Note in buzzer
      Button_pressed=1;                 //Para saber si presionas un boton
  }

  if (Piano_2[2] == 1){
      buzzer.playTone(NOTE_B4);         //Plays B4 Note in buzzer
      Button_pressed=1;                 //Para saber si presionas un boton
  }

  if (Piano_2[3] == 1){
      buzzer.playTone(NOTE_C5);         //Plays C5 Note in buzzer
      Button_pressed=1;                 //Para saber si presionas un boton
  }

  if (Piano_2[4] == 1){
      buzzer.playTone(NOTE_D5);         //Plays D5 Note in buzzer
      Button_pressed=1;                 //Para saber si presionas un boton
  }

  if(Button_pressed==0){
      buzzer.turn(off);                 //Turns buzzer OFF
}

}
