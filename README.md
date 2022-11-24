The article is being published in collaboration with JLCPCB. They supply high quality PCBs at a very reasonable price. They also can provide SMT circuit assembly.

We thanks to our sponsor JLCPCB  https://jlcpcb.com/RTA   for sponsoring us PCBs for this project circuit.

 Thanks To JLCPCB.
 
$2  for 1-4 Layer PCBs.

Get SMT Coupons - https://jlcpcb.com/RTA

In this circuit, we are going to teach you making a simple electronics project using NE-555 timer IC. An LED flasher circuit is a circuit which flashes the LED- meaning turns it ON-OFF, ON-OFF, ON-OFF. The 555 timer chip is a very versatile IC, because when connected correctly, it can it can create pulses of current at specific time intervals decided by the resistor-capacitor (RC) network.

The circuit can be used as a flashing metronome, dark room timer, memo-reminder or other similar applications. The IC is connected as a stable multi vibrator with a duty cycle of about 10%.

In figure 1 the LED will be ON for a short period of time and OFF for a longer period. The duty cycle can be reversed if the LED is connected as shown in figure 2 but the battery consumption will also increase due to the fact that the LED will stay ON for a longer period of time.



Component List - 

To make this LED flasher circuit using NE-555 timer IC, we might need some electronics component. You can order your assembled SMT circuit form JLCPCB.


All components list have been given below –


Component List – 

1.	Time IC – NE 555 

2.	Resistor –68 KΩ * 2

3.	Capacitor – 100uF/25v *2

4.	LED – 3v (20mA)

5.	Power Source – 9v


NE555 Pin Out - 

NE555 timer IC is an integrated circuit used in a variety of timer, delay, pulse generation and oscillator applications. Derivatives provide two or four timing circuits in one package. There are totally 8 legs of a timer IC. 

As well as the 555 timer, there is also available the NE556 timer oscillator.

The internal block diagram and schematic of the 555 timer are highlighted with the same color across all three drawings to clarify, how the chip is implemented.



1.	GND - The ground pin connects the 555 timer to the negative (0v) supply rail.

2.	TRIG - The negative input to comparator No 1. A negative pulse on this pin “sets” the internal Flip-flop when the voltage drops below 1/3Vcc causing the output to switch from a “LOW” to a “HIGH” state.

3.	OUT - The output pin can drive any TTL circuit and is capable of sourcing or sinking up to 200mA of current at an output voltage equal to approximately Vcc – 1.5V so small speakers, LEDs or motors can be connected directly to the output.

4.	RESET - This pin is used to “reset” the internal Flip-flop controlling the state of the output, pin 3. This is an active-low input and is generally connected to a logic “1” level when not used to prevent any unwanted resetting of the output.

5.	CONT - This pin controls the timing of the 555 by overriding the 2/3Vcc level of the voltage divider network. By applying a voltage to this pin the width of the output signal can be varied independently of the RC timing network. When not used it is connected to ground via a 10nF capacitor to eliminate any noise.

6.	THRES - The positive input to comparator No 2. This pin is used to reset the Flip-flop when the voltage applied to it exceeds 2/3Vcc causing the output to switch from “HIGH” to “LOW” state. This pin connects directly to the RC timing circuit.

7. DISCH - The discharge pin is connected directly to the Collector of an internal NPN transistor which is used to “discharge” the timing capacitor to ground when the output at pin 3 switches “LOW”.

8. VCC - This is the power supply pin and for general purpose TTL 555 
       timers is between 4.5V and 15V.
   

Feature - 

	Variety of Timer

	Delay Timer

	Pulse generation

	Oscillator Applications

	Lamp and LED flashers

	Logic clocks

	Tone generations

	Security alarms

	Position Modulation

	LED blinker


Circuit Connection – Step 1

555 timer IC is the cheap, popular and precise timing device used in various applications. 555 timer IC is used here in an astable operating mode which generates a continuous output in the form of square wave via pin 3 which turns the LED on and off.

To make this simple LED flasher circuit using NE-555 timer IC, we need to follow some method. 1st we need to connect 2 and 6 no leg of timer IC-NE555. Then we connect 4 and 8 no leg of NE-555 timer IC. It is a common connection for NE555 IC circuit.

Especially if you want to make a LED light effect project. Remember, to make led light flasher circuit using NE-555 IC you might need this connection.


Circuit Connection – Step 2

It is time to connect, 100µf/25v capacitor with the circuit. We connect capacitor cathode leg with 1no leg of timer IC, and then connect capacitor anode leg with 2no leg of timer IC.

To make a perfect flasher light, we are using 2 pieces 68 KΩ resistor with the circuit. Now we make a parallel connection between this two resistor. We connect it’s parallel terminal with 7no leg of timer IC and it’s other terminal with 6 and 8 no leg of timer IC.


Circuit Connection – Step 3

Now we need to connect LED light with the circuit. We are using 6 pieces led light each side. Then we make a parallel connection for each 6 pieces led. This time, we got two side led light. 

We connect left side LED light negative leg with 1no leg of timer IC and negative leg of power source.

Then we connect right side led light negative leg with positive leg of left side led light and 3no leg of timer IC. And we connect right side led light positive leg with 4no leg of timer IC and positive leg of power supply.


Circuit Connection – Step 4

Our circuit is not going to ready for use now. Just need to connect 9v power supply with the circuit. We connect this power supply negative cable with 1 no leg of timer IC and power supply positive cable with 8no leg of timer IC.
Now just plug-in power and enjoy the awesome effect of this circuit.



Steps to Order PCBs From JLCPCB

If you complete design of your PCBs, then it is time to order PCBs. To order best quality PCBs, just visit JLCPCB and click on the “QUOTE NOW” button.

Since 2006,  JLCPCB continuously driven to become more efficient and to reduce costs. They promise to offer customers the most economic PCBs forever. JLCPCB makes cheapest but top quality PCBs possibly because of scale effect, extremely high production efficiency and less manpower cost.
You can order minimum 5 pieces PCBs for only $2 costs.

To order PCBs, make your Gerber file. Then drag and drop the Gerber file on the following box.
Click on “Gerber Viewer” button you can check the PCBs design. Make sure everything is good, then choose color, quantity and order your PCBs at very reasonable prices.

If you are a new user, then you can order 10 pieces PCBs, costing only $2. To place your order click on “Save to Cart”  button. Confirm your shipping address and shipping method.


Steps to Order SMT PCBs From JLCPCB - 

To order your SMT PCBs, visit JLCPCB.

1.	 Drag and drop SMT PCBs file on site.

2.	 Choose your PCBs color and quantity.

3.	 To free SMT assembly for your PCB click on “SMT Assembly” button and then confirm.

4.	 Add your BOM file and CPL file.

5.	 Place your order click on “Save to Cart” button.

6.	 Confirm your shipping address and shipping method.

7.	 Pay your payment

8.	 Wait for confirmation mail.

9.	 For SMT Service, Click here.



Shipping and Billing - 

JLCPCB supported all shipping method can be seen below.

Estimated Delivery Time

DHL International Express 3-5 business days

UPS Worldwide Saver 3-6 business days

S.F Express (Standard) 5-8 business days

S.F Express (Economy) 8-15 business days

Singapore EMS 8-15 business days

Post Link Registered Mail 15-20 business days

ePacket 15-25 business days

Registered Air Mail 15-20 business days



JLCPCB supported Payment method.


•	PayPal


•	Credit/Debit Care


•	Prepaid wire transfer




Confirm PCBs Order


To confirm your order, pay your payment. Then accept PayPal, Credit/Debit Card, and Prepaid Wire Transfer. To manufacture your PCBs, it’ll take about 2 days. DHL will be fastest shipping method to arrive your ordered PCBs at your location.

All PCBs were well packed and quality was really good.

Thanks to JLCPCB for best quality PCBs.
