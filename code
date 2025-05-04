// Air Quality Monitoring System using Arduino and MQ135 Gas Sensor

const int mP = A0;    
void setup()
 {
  Serial.begin(9600);    
 }
void loop() 
 {
  float slope=-0.2;
  float interept=1.5;
  int sensorMQ135 = analogRead(mP); 
  float voltage = sensorMQ135 * (5.0 / 1023.0); 
  float PPM = slope*voltage+interept;
  Serial.print("       Air Quality:       ");
  Serial.print(PPM);
  Serial.println(" ppm");
  if (0<PPM<50)
   {
    Serial.println("Air quality is good");
   } 
  else if(51<PPM<100)
   {
    Serial.println("Air quality is Moderate");
   }
  else if(101<PPM<200)
   {
    Serial.println("Air quality is unhealthy");
   }
  else if(201<PPM<300)
   {
    Serial.println("Air quality is very  unhealthy");
   }
  else if(300<PPM<500)
   {
    Serial.println("Air quality is Hazardous");
   }
  else if(500<PPM)
   {
    Serial.println("Air quality is Emergency");
   }
  delay(800); 
 } 

