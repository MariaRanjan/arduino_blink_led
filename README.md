# Arduino LED Blink 🔴🟢

This is a basic Arduino program that blinks an LED connected to **pin 13**.
It is my first step towards learning **embedded systems and Arduino programming**.

## 🔧 Components Used
- Arduino Uno
- Built-in LED (Pin 13) or External LED
- Jumper wires
- Resistor (220Ω – if using external LED)

## 📄 Code Description
- The LED turns **ON for 1 second**
- The LED turns **OFF for 1 second**
- This cycle repeats continuously

## 🧠 Arduino Code
```cpp
int led = 13;

void setup() {
  pinMode(led, OUTPUT);
}

void loop() {
  digitalWrite(led, HIGH);
  delay(1000);
  digitalWrite(led, LOW);
  delay(1000);
}
