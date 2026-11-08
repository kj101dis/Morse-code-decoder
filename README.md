# Morse-code-decoder




The Morse Code Decoder is a handheld device that turns taps into letters in real time. It is built around a Seeed Studio XIAO ESP32 with a 0.96 inch OLED display, and it has three buttons: SW1 for a dot, SW2 for a dash, and SW3 to clear the screen. You tap out a letter using dots and dashes, and after a short pause of about 1.2 seconds, the decoder commits that letter and shows it on the display, which can hold up to 42 characters across two lines. Under the hood, it uses a binary tree to decode each sequence, supports letters A through Z with up to four symbols, and connects the OLED over I2C at address 0x3C. The whole build costs about 44 dollars in parts, including the XIAO ESP32, the OLED display, the buttons, and the PCB.




I made this because I am very fond of learning Morse code. I used to know it, but I had forgotten a lot of it over time. Building this decoder was my way to practice and relearn it hands on, and having a real device to tap out dots and dashes makes learning it much more fun than just reading about it.



<img width="487" height="294" alt="Screenshot 2026-11-08 4 07 25 PM" src="https://github.com/user-attachments/assets/3c8f733c-7fec-46b3-9e97-aa45ce78a5ff" />

<img width="293" height="417" alt="Screenshot 2026-11-08 4 07 17 PM" src="https://github.com/user-attachments/assets/399a000d-2156-4dcf-904a-c94084401b13" />


<img width="601" height="388" alt="Screenshot 2026-11-08 4 04 46 PM" src="https://github.com/user-attachments/assets/98e3d0ec-351d-4c61-940c-f495f686220f" />










[table.html](https://github.com/user-attachments/files/34526145/table.html)
<style>
#tz-z373pu .tableizer-table {
  border-collapse: collapse;
  width: auto;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
  color: #3f3f46;
  font-size: 12px;
}
#tz-z373pu .tableizer-table th {
  padding: 12px 22px;
  text-align: left;
  font-weight: 600;
  font-size: 12px;
  background-color: transparent;
  color: #18181b;
  border-bottom: 2px solid #18181b;
}
#tz-z373pu .tableizer-table td {
  padding: 12px 22px;
  text-align: left;
  color: #3f3f46;
  border-bottom: 1px solid #e8e8e8;
}
#tz-z373pu .tableizer-table .tz-right { text-align: right; }
</style>
<div id="tz-z373pu" class="tableizer-root">
<table class="tableizer-table">
  <thead>
    <tr>
      <th>name</th>
      <th class="tz-right">cost excl.tax&amp;ship</th>
      <th>link</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>seed studio mcu</td>
      <td class="tz-right">10.0</td>
      <td>https://www.amazon.com/dp/B0B94JZ2YF</td>
    </tr>
    <tr>
      <td>pcb</td>
      <td class="tz-right">0.5</td>
      <td>https://cart.jlcpcb.com/shopcart/cart/</td>
    </tr>
    <tr>
      <td>oled</td>
      <td class="tz-right">10.0</td>
      <td>amazon.com/gp/product/B0FSRQG23K</td>
    </tr>
    <tr>
      <td>m4 heat insert</td>
      <td class="tz-right">10.0</td>
      <td>https://www.amazon.com/KADRICK-150PCS-Inserts-5-5mm-Insert/dp/B0FD89Y73F</td>
    </tr>
    <tr>
      <td>m4 button head</td>
      <td class="tz-right">10.0</td>
      <td>https://www.amazon.com/gp/product/B0DCVVYCS8/ref=ewc_pr_img_2?smid=AU4U01987UNZX&amp;th=1</td>
    </tr>
    <tr>
      <td>button</td>
      <td class="tz-right">3.5</td>
      <td>https://www.lcsc.com/product-detail/C318884.html?s_z=n_q_C318884&amp;globalKeyword=C318884</td>
    </tr>
  </tbody>
</table>
</div>
