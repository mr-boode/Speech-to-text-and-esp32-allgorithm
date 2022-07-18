# Speech-to-text-and-esp32-allgorithm
In this task ( convert speech to text) , HTML, CSS, JS were used. In the begining, a start HTML file was created that contains a link to link it with the speech to text conversion page and contains the start button. When you press it, the index HTML page will open asking the user to allow the use of the microphone.Tou must click on Allow and Speak and here the speech will be converted to text using JavaScript . It only works on Google Chrome browser therefore, some browsers do not support it.

Steps to connect ESP32 to Arduino :

1- Download Arduino IDE software : https://www.arduino.cc/en/software. 
2-Plug the ESP32 to your PC or laptob by using micro cable.
3- Go to Tools > Board > Boards Manager > from the search bar write "esp32" > click on install.
4- Go to Tools > Board > select the name of your ESP32 board.
5- Go to Tools > Port and select a COM port available.

6- write the following code in arduion editor :

// the setup function runs once when you press reset or power the board
void setup() {
  // initialize digital pin LED_BUILTIN as an output.
  pinMode(LED_BUILTIN, OUTPUT);
}

// the loop function runs over and over again forever
void loop() {
  digitalWrite(LED_BUILTIN, HIGH);   // turn the LED on (HIGH is the voltage level)
  delay(1000);                       // wait for a second
  digitalWrite(LED_BUILTIN, LOW);    // turn the LED off by making the voltage LOW
  delay(1000);                       // wait for a second
}
