# Vaja14-UART-Putty-NUCLEO
posiljanje imen v program Putty 

---------------------------------
Odgovori:
2 c.) odspajkati moramo SD13 in SD14 in jih prispajkati na SB62 in SB63
e.) USART2_TX PA2 --- USART2_RX PA3
f.) 115200 bit/s

3.e.) HAL_GPIO_TogglePin(GPIOA,GPIO_PIN_5);
f.)   HAL_Delay(100);
---------------------------------
Komentar:
Program deluje odzivno ko pritisnemo tipko se nam v putty aplikaciji izpišejo imena.
