# Vaja2-ADC-continuos-conversion-STM32F0


b) Glede na vašo razvojno ploščico in razširitveno vezje z tipkami ter
potenciometri, izberite ustrezni analogni vhod. Kateri pin je to? __PC 0___.

e) Glede na potenciometer na vaši ploščici izberite-obkljukajte ustrezni kanal/pin.
Na zaslonu se vam mora usterzno pobarvati izbrani pin v zeleno barvo. Kaj se
izpiše poleg pina? __ADC3 IN1___.

f) V Clock Configuration spremenimo APB1 peripheral clock (MHz) na 16 MHz. Kaj
opazite? __Spremenijo se še nekatere druge nastavitve (APB1 peripheral clock,
APB1 timer clock in USART2)__.

h) Clock Prescaler nastavimo z deliteljem 4. Kolikšna je sedaj preskalirana
frekvenca takta fpreskalirana? __Preslikana frekvenca takta je 16MHz__

j) Sampling time (čas vzorčenja tvz_ciklih) spremenite na 239.5 cikov. Pravi čas
vzorčenja se nato poveča še za 12 ciklov. Koliko znaša pravi čas vzorčenja tvz v
mikro sekundah?
(enačba: tvz=tvz_ciklih/fpreskalriana)? _Prvi čas vzorčenja: 16,219 μs_
