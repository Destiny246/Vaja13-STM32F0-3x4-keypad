# Vaja13-STM32F0-3x4-keypad
<ul>
  <h3>Odgovori na vprašanja:</h3>
    <h4>2.:</h4>
      <li>Tipka | Vrstica/Row | Stolpec/Colum | Razlaga</li>
      <li>  1        Pin2            Pin3       </li>
      <li>  2        Pin2            Pin1       </li>
      <li>  3        Pin2            Pin5       </li>
      <li>  4        Pin7            Pin3       </li>
      <li>  5        Pin7            Pin1       </li>
      <li>  6        Pin7            Pin5       </li>
      <li>  7        Pin6            Pin3       </li>
      <li>  8        Pin6            Pin1       </li>
      <li>  9        Pin6            Pin5       </li>
      <li>  *        Pin4            Pin3       </li>
      <li>  0        Pin4            Pin1       </li>
      <li>  #        Pin4            Pin5       </li>
    <h4>3.d:</h4>
      <li>HAL_GPIO_TogglePin(GPIOC, GPIO_PIN_9);</li>
    <h4>3.e:</h4>
      <li>100ms</li>
    <h4>3.f:</h4>
      <li>HAL_GPIO_TogglePin(GPIOC, GPIO_PIN_8);</li>
    <h4>3.g:</h4>
      <li>HAL_Delay(500);</li>
    <h4>4.b:</h4>
      <li>Ob pritisku na modro tipko vklopimo zeleno LED, ki obstane vklopljena do naslednjega pritiska na modro tipko.</li> 
    <h4>4.c:</h4>
      <li>Pritisk natipko in prižig zelene LED ne vplivata na enakomerno urtipanje modre LED.</li> 
</ul>

<ul>
  <h3>Komentar:</h3>
  <p>
    Modra LED utripa na vsake 500ms, zelena LED pa se vklopi samo ob pritisku na mnodro tipko in se izklopi le ob ponovnem pritisku.
  </p>
</ul>
