# TextLCD

Updated [Simon Ford/TextLCD](https://os.mbed.com/users/simon/code/TextLCD/) library to support for the MbedOS 6.9.0 API. Tested using PlatformIO Core 6.1.3.

## Importing

Add the following line to platformio.ini
```sh
lib_deps = https://github.com/KalanaRatnayake/TextLCD
```

## Example 
```sh
int main() 
{
    TextLCD	lcd(PE_2, PE_3, PE_4, PE_5, PE_6, PC_13, TextLCD::LCD16x2);

    lcd.display("oneline", 2000000);
    
    lcd.display("firstline", "secondline", 2000000);

    while(1)
    {
        // code
    }
}
```

<br>
