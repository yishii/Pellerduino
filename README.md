**Pellerduino**
- Parallax Propeller IDE based on Arduino IDE

Both program onto E2PROM and just load in hubmemory and run are supported.

**Status of this project**

Creating underway.

**Supported APIs**
* digitalWrite
* digitalRead
* pinMode
* delay
* delayMicroseconds

**Sample Code**

`

    void setup()
    {
        pinMode(20,OUTPUT);
    }

    void loop()
    {
        digitalWrite(20,LOW);
        delay(500);
        digitalWrite(20,HIGH);
        delay(500);
    }
`



