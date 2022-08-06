# TextLCD

Updated [Simon Ford/TextLCD](https://os.mbed.com/users/simon/code/TextLCD/) library to support for the MbedOS 6.9.0 API

## Example 
```sh
int main() 
{
    TextLCD	lcd(PE_2, PE_3, PE_4, PE_5, PE_6, PC_13, TextLCD::LCD16x2);

	lcd.locate(0,0);
	lcd.printf("Configuring..");
	wait_us(2000000);
	lcd.locate(0,0);

    while(1)
    {
        // code
    }
```