# Quick-Assistance-Device-
Our project uses an Atmel ATSAMW25 SoC (System on Chip) which is wifi enabled by it’s WINC1500 2.4GHz IEEE® 802.11 b/g/n Wi-Fi module. The SAMD21 Cortex-M0+ 32bit low power ARM MCU is connected to Iot service like Temboo(used to connect cloud services to the microcontroller) and  Amazon Web Services(the cloud service) where a notification is sent to the user’s relatives and to the hospital with a press of a button and sounds a buzzer. 

HARDWARE REQUIREMENT/DESCRIPTION

ATSAMW25 SoC with SAMD21 Cortex-M0+ 32 bit low power ARM MCU and  WINC1500 2.4GHz IEEE® 802.11 b/g/n Wi-Fi
Pushbutton 
Buzzer 
3.7v 1100mAh Lithium polymer battery

APPROACH/METHODOLOGY       
This device is an internet of things based device. The ATSAMW25 SoC is connected to a pushbutton through a 10k ohm pull up resistor and a buzzer. As the pushbutton is pressed the buzzer is rings and the device through the Temboo API (which allows the microcontroller through  Wifi to connect to any cloud service)  accesses Amazon Web Service(the cloud service) and communicates with Amazon SNS (Simple Notification Service) and pushes an email to all the subscribed members to the service. 
