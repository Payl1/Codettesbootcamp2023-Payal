Day 7 ( 26 sept):
=================

objective :  Recap from the trial period.

Coding of 2 DC motors.

HandsOn:

![](https://lh3.googleusercontent.com/4NKnRoKEH1XQX-8z19WU3152QXMS3vdkOZo6L5HqpMLa6uSqKutAVHFRXLNa927cIF5bHfMt9JR_Kglsg-wBfkoYHc_SfblaWxJXlQViD3PaZ5HYufEcD_LR1CmqquWQKv_2YlkLsEx10L1EeCR19-k)

We had already built the 2 DC motors. We went in detail about the coding and learnt some new coding, how you can control your DC motors with bluetooth by putting a command in the serial monitor.

Code:

int motor1enable = 3;

int motor1input1 = 2;

int motor1input2 = 4;

int motor2enable = 5;

int motor2input1 = 7;

int motor2input2 = 8;

void motorforward()

{

  analogWrite(motor1enable, 255);

  digitalWrite(motor1input1, HIGH);

  digitalWrite(motor1input2, LOW);

  analogWrite(motor2enable, 255);

  digitalWrite(motor2input1, HIGH);

  digitalWrite(motor2input2, LOW);

}

void motorbackward()

{

  analogWrite(motor1enable, 255);

  digitalWrite(motor1input1, LOW);

  digitalWrite(motor1input2, HIGH);

  analogWrite(motor2enable, 255);

  digitalWrite(motor2input1, LOW);

  digitalWrite(motor2input2, HIGH);

}

void motorleft()

{

  analogWrite(motor1enable, 255);

  digitalWrite(motor1input1, LOW);

  digitalWrite(motor1input2, LOW);

  analogWrite(motor2enable, 255);

  digitalWrite(motor2input1, LOW);

  digitalWrite(motor2input2, HIGH);

}

void motorright()

{

  analogWrite(motor1enable, 255);

  digitalWrite(motor1input1, HIGH);

  digitalWrite(motor1input2, LOW);

  analogWrite(motor2enable, 255);

  digitalWrite(motor2input1, LOW);

  digitalWrite(motor2input2, LOW);

}

void motorstop()

{

  analogWrite(motor1enable, 255);

  digitalWrite(motor1input1, LOW);

  digitalWrite(motor1input2, LOW);

  analogWrite(motor2enable, 255);

  digitalWrite(motor2input1, LOW);

  digitalWrite(motor2input2, LOW);

}

int state;

void setup()

{

  Serial.begin(9600);

  pinMode(motor1enable, OUTPUT);

  pinMode(motor1input1, OUTPUT);

  pinMode(motor1input2, OUTPUT);

  pinMode(motor2enable, OUTPUT);

  pinMode(motor2input1, OUTPUT);

  pinMode(motor2input2, OUTPUT);

}

void loop()

{

  if (Serial.available() > 0){

  state = Serial.read();

  }

  if (state == 'F'){

    Serial.println("Forward");

    motorforward();  

  }

  else if (state == 'B'){

    Serial.println("Backward");

    motorbackward();

  }

  else if (state == 'R'){

    Serial.println("Left");

    motorright();

  }

  else if (state == 'L'){

    Serial.println("Left");

    motorleft();

  }

  else {

    Serial.println("Stop");

    motorstop();

  }

}

Mistakes: 

I made some coding errors, but when I saw my errors in the serial monitor I corrected them.