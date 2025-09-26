# Blinking External LED

# Parts
1. Breadboard
2. LED
3. 330Ω Resistor
4. 2 Jumper Wires

# Instructions
1. Put LED on breadboard.
2. Put a resistor on either the "+" or "-" of the LED.
3. Connect the open LED leg to Pin 8
4. Connect the end of Resistor to GND (Ground).

# Circuit


# Code
```arduino
void setup() {
  pinMode(8, OUTPUT);
}

void loop() {
  digitalWrite(8, HIGH);
  delay(1000);
  digitalWrite(8, LOW);
  delay(1000);
}
```
