Atividade 23/08 exercício com simulador arduino.
void setup()
{
  pinMode(13, OUTPUT);
}

void loop()
{
//Escrever para a saida 13 como ligado(1)
digitalWrite(13, HIGH);
// Aguardar 1 segundo
delay(1500);
//Escrever para a saida 13 como desligado(0)
digitalWrite(13, LOW);
// Aguardar 1 segundo
delay(500);
}
