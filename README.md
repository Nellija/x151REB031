# x151REB031
University project

#1 Darbs /  Majas lappa

<html>
<head>
<title>
sveiks
</title>
</head>
<body>
<iframe width="560" height="315" src="https://www.youtube.com/embed/v0KSqLMpPI4" frameborder="0"$
<a href="http://www.w3schools.com"> W3 skola.html </a>
<img src=le.lv/url?sa=i&rct=j&q=&esrc=s&source=images&cd=&ved=0ahUKEwiLrvvk75TLAhXJDZoKHX3OCqMQj$
<a href="https://213.175.92.37/~x151REB031"> Mana drauga studiju lapa</a>

<h1>"A place for resistor"</h1>
<img src="//lh6.googleusercontent.com/-p0gRiB8N9Js/V0Ijv8vokXI/AAAAAAAAACc/hAW7D-x71qAamKJIHVs_a$
<iframe width="853" height="480" src="https://www.youtube.com/embed/S_csgnCEQHU" frameborder="0"$
</html>


#2 Darbs / Chuska

int PIN_SCE = 6;//SS
int PIN_RESET = 7;
int PIN_DC  = 5;// data
int PIN_SDIN = 4 ;//MOSI  SIMO
int PIN_SCLK =3 ;//CLK SCLK
int PIN_BL =9 ;//BL LED
int PIN_VCC =2 ;//Vcc +-
#define LCD_C LOW //command
#define LCD_D HIGH //data high command low.
#define LCD_X 84 ///character area //
#define LCD_Y 48  //consists of banks of 7 by eight pixels.//
#define LCD_DATA 1
const unsigned char nokia [] = {
    0x00, 0xE0, 0xE0, 0xE0, 0xE0, 0xE0, 0xE0, 0xE0, 0xE0, 0x80, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00,
    0xE0, 0xE0, 0xE0, 0xE0, 0x00, 0x00, 0xC0, 0xE0, 0xE0, 0xE0, 0xE0, 0xE0, 0xE0, 0xE0, 0xE0, 0xE0,
    0xE0, 0xE0, 0xE0, 0xE0, 0xE0, 0xC0, 0x80, 0x00, 0xE0, 0xE0, 0xE0, 0xE0, 0xE0, 0x00, 0x00, 0x00,
    0x00, 0x80, 0xC0, 0xE0, 0xE0, 0xE0, 0xE0, 0x60, 0x20, 0x00, 0x40, 0xE0, 0xE0, 0xE0, 0xE0, 0x00,
    0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0xC0, 0xE0, 0xE0, 0xE0, 0xE0, 0xE0, 0xC0, 0x00, 0x00, 0x00,
    0x00, 0x00, 0x00, 0x00, 0x00, 0xFF, 0xFF, 0xFF, 0xFF, 0x0F, 0x0F, 0x3F, 0xFF, 0xFF, 0xFE, 0xF8,
    0xF0, 0xC0, 0x00, 0x00, 0xFF, 0xFF, 0xFF, 0xFF, 0x00, 0xFE, 0xFF, 0xFF, 0xFF, 0xFF, 0x03, 0x03,
    0x03, 0x03, 0x03, 0x03, 0x03, 0x03, 0x03, 0xFF, 0xFF, 0xFF, 0xFF, 0x00, 0xFF, 0xFF, 0xFF, 0xFF,
    0xFF, 0xF0, 0xF8, 0xFC, 0xFE, 0xFF, 0xDF, 0x0F, 0x07, 0x03, 0x00, 0x00, 0x00, 0x00, 0xFC, 0xFF,
    0xFF, 0xFF, 0xFF, 0x00, 0x00, 0x00, 0x00, 0xE0, 0xF8, 0xFF, 0xFF, 0x7F, 0x1F, 0x07, 0x1F, 0xFF,
    0xFF, 0xFF, 0xF8, 0xE0, 0x00, 0x00, 0x00, 0x00, 0x00, 0xFF, 0xFF, 0xFF, 0xFF, 0x01, 0x00, 0x00,
    0x00, 0x01, 0x07, 0x1F, 0x7F, 0xFF, 0xFF, 0xFE, 0xFF, 0xFF, 0xFF, 0xFF, 0x00, 0x0F, 0x7F, 0xFF,
    0xFF, 0xFF, 0xF8, 0xF8, 0xF8, 0xF8, 0xF8, 0xF8, 0xF8, 0xF8, 0xF8, 0xFF, 0xFF, 0x7F, 0x1F, 0x00,
    0xFF, 0xFF, 0xFF, 0xFF, 0xFF, 0x00, 0x01, 0x03, 0x07, 0x1F, 0x3F, 0x7F, 0xFE, 0xFC, 0xF8, 0xF0,
    0xC0, 0x80, 0xF9, 0xFF, 0xFF, 0xFF, 0xFF, 0x00, 0xE0, 0xFC, 0xFF, 0xFF, 0x7F, 0x1F, 0x1F, 0x1F,
    0x1F, 0x1F, 0x1F, 0x1F, 0x1F, 0x1F, 0xFF, 0xFF, 0xFF, 0xFC, 0xE0, 0x00, 0x00, 0x00, 0xC0, 0xC0,
    0x40, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00,
    0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x80, 0x00,
    0x00, 0x60, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00,
    0x00, 0x00, 0xC0, 0xC0, 0xC0, 0x80, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00,
    0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0xE0, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00,
    0x00, 0xFF, 0xDF, 0x00, 0x00, 0xF0, 0xFE, 0x06, 0x06, 0xFE, 0x70, 0xFE, 0xFE, 0x06, 0x06, 0xFE,
    0x00, 0xFE, 0x1E, 0x02, 0x86, 0xFC, 0x00, 0xFC, 0x66, 0x62, 0x7E, 0x38, 0xF8, 0xFE, 0x06, 0x02,
    0x02, 0xFF, 0xFF, 0x02, 0x02, 0xFE, 0x00, 0x00, 0xFE, 0x06, 0x06, 0xFE, 0x00, 0xF8, 0xDE, 0x02,
    0x06, 0xFE, 0x00, 0x00, 0x00, 0x00, 0xFF, 0x60, 0x60, 0x3F, 0x00, 0xFC, 0x66, 0x62, 0x7E, 0x38,
    0xF8, 0xFE, 0x02, 0x06, 0xFC, 0x00, 0xFE, 0xFE, 0x02, 0x06, 0xFC, 0x00, 0xFF, 0x80, 0xF0, 0xFE,
    0x62, 0x66, 0x7C, 0x00, 0x00, 0x01, 0x07, 0x0C, 0x0C, 0x04, 0x07, 0x0C, 0x0C, 0x07, 0x00, 0x07,
    0x07, 0x00, 0x00, 0x07, 0x00, 0x07, 0x07, 0x00, 0x01, 0x07, 0x00, 0x07, 0x06, 0x0C, 0x0C, 0x00,
    0x01, 0x07, 0x0C, 0x0C, 0x00, 0x03, 0x0F, 0x0C, 0x04, 0x07, 0x00, 0x00, 0x07, 0x00, 0x00, 0x07,
    0x00, 0x03, 0x27, 0x2C, 0x2E, 0x3F, 0x00, 0x00, 0x00, 0x00, 0x07, 0x00, 0x00, 0x00, 0x00, 0x07,
    0x0E, 0x0C, 0x0C, 0x00, 0x01, 0x07, 0x0C, 0x0E, 0x07, 0x00, 0x3F, 0x1F, 0x0C, 0x06, 0x03, 0x00,
    0x07, 0x00, 0x00, 0x07, 0x0C, 0x0C, 0x04, 0x00,
};
void posmarker()  {
    LcdWrite( 0, 0x80|0);
    LcdWrite( 0, 0x40|0);
}
void pozicija(char x, char y)
{ 
    LcdWrite( 0, 0x80|x);
    LcdWrite( 0, 0x40|y);
}
void kursors(unsigned char z)
{
          digitalWrite(PIN_DC,HIGH);
        digitalWrite(PIN_SCE, LOW);
        //shiftOut(PIN_SDIN, PIN_SCLK, MSBFIRST,nokia[index3]);
        shiftOut(PIN_SDIN, PIN_SCLK, MSBFIRST,z);
        digitalWrite(PIN_SCE, HIGH);
}

void LcdClear(void) {
    for(int index = 0; index < 504; index++){
        LcdWrite(LCD_D, 0x00);
    }
}
void LcdWrite(byte dc, byte data) {
    digitalWrite(PIN_DC, dc);
    digitalWrite(PIN_SCE, LOW);
    shiftOut(PIN_SDIN, PIN_SCLK, MSBFIRST, data);
    digitalWrite(PIN_SCE, HIGH);
}
void initialise() {
    pinMode(PIN_VCC, OUTPUT);
    pinMode(PIN_SCE, OUTPUT);
    pinMode(PIN_RESET, OUTPUT);
    pinMode(PIN_DC, OUTPUT);
    pinMode(PIN_SDIN, OUTPUT);
    pinMode(PIN_SCLK, OUTPUT);
    pinMode(PIN_BL, OUTPUT);
    digitalWrite(PIN_VCC, HIGH);
    digitalWrite(PIN_RESET, LOW);
    digitalWrite(PIN_RESET, HIGH);
    LcdWrite(0, 0x21);
    //Tell LCD that extended commands follow
    LcdWrite(0, 0xB9);
    //Set LCD Vop (Contrast): Try 0xB1(good @ 3.3V) or 0xBF if your display is too dark
    LcdWrite(0, 0x04);
    //Set Temp coefficent
    LcdWrite(0, 0x14);
    //LCD bias mode 1:48: Try 0x13 or 0x14
    LcdWrite(0, 0x20);
    //We must send 0x20 before modifying the display control mode
    LcdWrite(0, 0x0C);
    //Set display control, normal mode. 0x0D for inverse
    //digitalWrite(PIN_BL, HIGH);
}
void setup()  {
    initialise();
    LcdClear();
    posmarker();
}
void loop(){
    pozicija(0,0);
    for (int index3 = 0; index3 < 84; index3++) {
        digitalWrite(PIN_DC,HIGH);
        digitalWrite(PIN_SCE, LOW);
        //shiftOut(PIN_SDIN, PIN_SCLK, MSBFIRST,nokia[index3]);
        shiftOut(PIN_SDIN, PIN_SCLK, MSBFIRST,0xFF);
        digitalWrite(PIN_SCE, HIGH);
    }
     pozicija(0,5);
    for (int index3 = 0; index3 < 84; index3++) {
        digitalWrite(PIN_DC,HIGH);
        digitalWrite(PIN_SCE, LOW);
        //shiftOut(PIN_SDIN, PIN_SCLK, MSBFIRST,nokia[index3]);
        shiftOut(PIN_SDIN, PIN_SCLK, MSBFIRST,0xFF);
        digitalWrite(PIN_SCE, HIGH);
    }
    
  
    for (int index3 = 0; index3 < 6; index3++) {
      pozicija(83,index3);
      kursors(0xFF);
    }
    for (int index3 = 0; index3 < 84; index3++) {
      pozicija(index3,2);
      kursors(0xFF);//uzzimesana
      delay(200);
      pozicija(index3,2);
      kursors(0x01);//dzesana
      pozicija(index3,2);
      kursors(0x84);//uzzimesana
      }

      for (int index3 = 84; index3 > 0; index3++) {
      pozicija(index3,2);
      kursors(0xFF);//uzzimesana
      delay(200);
      pozicija(index3,2);
      kursors(0x01);//dzesana
      }
   
    delay(2000);
}
