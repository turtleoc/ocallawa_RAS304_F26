---
Section Two : Component Selection
---

>For my design, the selected components are the **DFR0154 LCD Display** and the **PEC11-4215F-S24 Rotary Encoder**.

>The DFR0154 LCD display was selected because of its simple pinout and ease of use. Its serial communication interface reduces the number of connections required between the display and the PIC18F57Q43 microcontroller.

>The PEC11-4215F-S24 rotary encoder was selected because of its unlimited rotation and larger physical size compared to the other rotary encoder options. Its continuous rotation makes it well suited for navigating menus and adjusting settings through the human-machine interface.

>Additionally, our design will incorporate two pushbuttons for operating the human-machine interface.


## Display Module

The display module will provide a visual interface for the user, allowing information and settings to be displayed.



## Display Module

1. **DFR0154 Display**

<!-- ![DFR0154 Display](./LCD_1.webp) -->
   [DFR0154_Display](LCD_1.webp){style width:"350" height:"300;"}


   | Pros | Cons |
   | :--: | :--: |
   | Low cost US$14.00 | Bulky |
   | Simple pinout | Low backlight contrast |
   | [Link to product](https://www.digikey.com/en/products/detail/dfrobot/DFR0154/7597130) | |

2. **ERM2004DNS-1 Display**

   [ERM2004DNS-1 Display](./LCD_2.webp){style width:"350" height:"300;"}

   | Pros | Cons |
   | :--: | :--: |
   | Low cost US$7.79 | Complex pinout without additional module |
   | High contrast | Difficult mounting |
   | [Link to product](https://www.buydisplay.com/arduino-black-lcd-20x4-i2c-code-character-module-display-high-contrast) | |

3. **Hosyond 2.42 SSD1309 Display**

   [Hosyond 2.42 SSD1309 Display](./Hoysond.jpg){style width:"350" height:"300;"}

   | Pros | Cons |
   | :--: | :--: |
   | Low cost US$15.99 | Complex setup |
   | High pixel count | Fragile |
   | Simple pinout | |
   | [Link to product](https://www.amazon.com/Hosyond-inches-Display-SSD1309-Arduino/dp/B0G2RFLG1L/ref=sr_1_6?crid=2HMQACBZAN3Q7&dib=eyJ2IjoiMSJ9.Ow-e3_XoNgJW80RouUdQqt4rlTLRowULCs2eUHuLKh96rkOY7GfjGB9KO0b7LyYqkyDlR1Ymn0NjqUqPQ70i80z5Sw-e0HjGJRmJqaxuNWIXu2UgdwsEo4fIA0577m17iI01nDo7AWc9VjutFklhJ8ao0h4QHvXN__vHZTHHWMenyxvrRRYt3nBW_Jx11xhLwyEYtGaQqTf0qUNSZ8qS3zPj4jELu1l4KGe8Vm8Ufag.oeDuK4QLR1GEmp0xCKYhCaBLAN5Yi-H5MR_y_ucGP58&dib_tag=se&keywords=hoysond+2.4+oled&qid=1792512474&sprefix=hoysond+2.4+ole%2Caps%2C177&sr=8-6) | |

**Choice:**

> **DFR0154 LCD Display:** Its simplistic pinout allows the design to become significantly less complex.

## Dial Interface

This will allow the user to interact with the LCD display.

1. **WH148 B10K Potentiometer**

   [WH148 B10K Potentiometer](./Pot_1.jpg){style width:"350" height:"300;"}

   | Pros | Cons |
   | :--: | :--: |
   | Low cost US$6.99 | Impact sensitive |
   | Simple pinout | Limited rotation |
   | Easy to setup | |
   | [Link to product](https://www.amazon.com/dp/B07WWLC33K?lv=shuf&channelId=500&plpRedirect=mhFallback) | |

2. **PEC11-4215F-S24 Rotary Encoder**

   [PEC11-4215F-S24 Rotary Encoder](./Rotary%201.jpg){style width:"350" height:"300;"}

   | Pros | Cons |
   | :--: | :--: |
   | Low cost US$4.50 | Impact sensitive |
   | Unlimited rotation | Complex pinout |
   | Larger physical size | Complex setup |
   | [Link to product](https://www.adafruit.com/product/377) | |

3. **PTV09A-4215F-B103 Potentiometer**

   [PTV09A-4215F-B103 Potentiometer](./Pot_Small.jpg){style width:"350" height:"300;"}

   | Pros | Cons |
   | :--: | :--: |
   | Very low cost US$0.89 | Impact sensitive |
   | Simple analog interface | Limited rotation |
   | Easy to connect | Small size (9mm) |
   | [Link to product](https://www.digikey.com/en/products/detail/bourns-inc/PTV09A-4215F-B103/3820584) | |

**Choice:**

> **PEC11-4215F-S24 Rotary Encoder:** Its more user-friendly design and higher user quality are unmatched.
