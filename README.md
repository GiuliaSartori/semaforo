# semaforo
 semaforo
 
void setup()    //Configurações iniciais
{
  pinMode(5, OUTPUT);    //define o pino 5 como saida
  pinMode(13, OUTPUT);    //define o pino 13 como saida
  pinMode(6, OUTPUT);    //define o pino 6 como saida
  pinMode(11, OUTPUT);    //define o pino 11 como saida
  pinMode(7, OUTPUT);    //define o pino 7 como saida
  pinMode(12, OUTPUT);    //define o pino 12 como saida
}

void loop()    //Roda de maneira ciclica os comandos abaixo
{
  digitalWrite(5, HIGH);    //Liga o pino 5
  digitalWrite(13, HIGH);    //Liga o pino 13
  delay(3000);                //Aguarde 3 seg.
  digitalWrite(5, LOW);        //Desliga o pino 5
  digitalWrite(6, HIGH);    //Liga o pino 6
  delay(2000);                //Aguarde 2 seg.
  digitalWrite(6, LOW);        //Desliga o pino 6
  digitalWrite(13, LOW);    //Desliga o pino 13
  digitalWrite(11, HIGH);    //Liga o pino 11
  digitalWrite(7, HIGH);    //Liga o pino 7
  delay(3000);                //Aguarde 3 seg.
  digitalWrite(11, LOW);    //Desliga o pino 11
  digitalWrite(12, HIGH);    //Liga o pino 12
  delay(2000);                //Aguarde 2 seg.
  digitalWrite(12, LOW);    //Desliga o pino 12
  digitalWrite(7, LOW);        //Desliga o pino 7
}

