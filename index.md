---
layout: slides
title: How to measure almost anything with a computer
---

<section data-markdown data-separator="^\n---\n$" data-separator-vertical="^\n--\n$">
<script type="text/template">

![Bonsai](assets/images/logo-horizontal.svg)

[neuronautas.github.io/how-to-measure](https://neuronautas.github.io/how-to-measure/)

## How to measure almost anything with a computer

---

<!-- .element: data-transition="none" -->
#### How do you get data into a computer?

<table>
  <tr>
    <td width="30%"><small>What is the temperature outside?</small></td>
    <td width="30%"></td>
    <td width="30%"><small>How do you get that <b>value</b> into a computer?</small></td>
  </tr>
</table>

<div>
  <img src="assets/images/measuring-0.svg"/>
</div>

--

<!-- .element: data-transition="none" -->
#### What is a computer?

<table>
  <tr>
    <td style="vertical-align: middle;"><a href="https://commons.wikimedia.org/wiki/File:HP-HP9000-425-Workstation_26.jpg"><img src="https://upload.wikimedia.org/wikipedia/commons/5/54/HP-HP9000-425-Workstation_26.jpg" /></a></td>
    <td style="vertical-align: middle;"><a href="https://commons.wikimedia.org/wiki/File:Lenovo_G500s_laptop-2905.jpg"><img src="https://upload.wikimedia.org/wikipedia/commons/e/e4/Lenovo_G500s_laptop-2905.jpg" /></a></td>
    <td style="vertical-align: middle;"><a href="https://commons.wikimedia.org/wiki/File:Android_Smartphones.jpg"><img src="https://upload.wikimedia.org/wikipedia/commons/1/16/Android_Smartphones.jpg" /></a></td>
  </tr>
  <tr>
    <td><small>HP9000 Unix Workstation</small></td>
    <td><small>Lenovo Laptop</small></td>
    <td><small>Android Smartphones</small></td>
  </tr>
</table>

--

<!-- .element: data-transition="none" -->
#### How do you get data into a computer?

<table>
  <tr>
    <td width="30%"><small>What is the temperature outside?</small></td>
    <td width="30%"></td>
    <td width="30%"><small>How do you get that <b>value</b> into a computer?</small></td>
  </tr>
</table>

<div>
  <img src="assets/images/measuring-0.svg"/>
  <img class="fragment" src="assets/images/measuring-1.svg" style="position: absolute; left: 99px;" />
</div>

--

<!-- .element: data-transition="none" -->
#### How do you get data into a computer?

![Daq](assets/images/daq.svg)

--

<!-- .element: data-transition="none" -->
#### Computers can only measure voltage

<table>
  <tr>
    <td style="vertical-align: middle;"><img src="assets/images/daq-sensor.svg" /></td>
    <td class="fragment" style="vertical-align: middle;"><img src="assets/images/daq-ohm.svg" /></td>
  </tr>
</table>

--

<!-- .element: data-transition="default none" -->
#### Bio-electricity and Ohm's Law

<table>
  <tr>
    <td style="vertical-align: middle;"><a href="https://en.wikipedia.org/wiki/Alessandro_Volta"><img src="https://upload.wikimedia.org/wikipedia/commons/5/52/Alessandro_Volta.jpeg" /></a></td>
    <td style="vertical-align: middle;"><a href="https://en.wikipedia.org/wiki/Georg_Ohm"><img src="https://upload.wikimedia.org/wikipedia/commons/2/2a/Georg_Simon_Ohm3.jpg" /></a></td>
    <td style="vertical-align: middle;"><a href="https://www.azquotes.com/picture-quotes/quote-the-future-science-of-government-should-be-called-la-cybernetique-1843-coining-the-french-andre-marie-ampere-89-92-33.jpg"><img src="https://upload.wikimedia.org/wikipedia/commons/c/c0/Ampere_Andre_1825.jpg" /></a></td>
  </tr>
  <tr>
    <td><small>Alessandro Volta</small></td>
    <td><small>Georg Ohm</small></td>
    <td><small>André-Marie Ampère</small></td>
  </tr>
</table>

--

<!-- .element: data-transition="none" -->
#### Computers can only measure voltage

<table>
  <tr>
    <td style="vertical-align: middle;"><img src="assets/images/daq-sensor.svg" /></td>
    <td style="vertical-align: middle;"><img src="assets/images/daq-ohm.svg" /></td>
  </tr>
</table>

--

<!-- .element: data-transition="none" -->
#### Computers can only measure voltage

<table>
  <tr>
    <td style="vertical-align: middle;"><img src="assets/images/daq-sensor.svg" /></td>
    <td style="vertical-align: middle;"><img src="assets/images/daq-thermistor.svg" /></td>
  </tr>
</table>

--

<!-- .element: data-transition="none" -->
#### Voltage divider: a readout of variable resistance

![Voltage](assets/images/daq-voltage.svg)

--

<!-- .element: data-transition="none" -->
#### Analog to Digital Converter (ADC)

<table>
  <tr>
    <td style="vertical-align: middle;"><img src="assets/images/daq-adc.svg" /></td>
    <td class="fragment" style="vertical-align: middle;"><img src="assets/images/daq-transistor.svg" /></td>
  </tr>
</table>

--

<!-- .element: data-transition="none" -->
#### The simplest ADC: 1-bit comparator

<table>
  <tr>
    <td style="vertical-align: middle;"><img src="assets/images/daq-adc1.svg" /></td>
    <td style="vertical-align: middle;"><a href="https://en.wikipedia.org/wiki/Comparator#/media/File:Opamp105.gif"><img src="https://upload.wikimedia.org/wikipedia/commons/f/f5/Opamp105.gif" /></a></td>
  </tr>
</table>

--

<!-- .element: data-transition="none" -->
#### Counting in Binary

<table>
  <tr>
    <td style="vertical-align: middle;"><img src="assets/images/daq-adc.svg" /></td>
    <td style="vertical-align: middle;"><img width="320" src="assets/images/binary-1.svg" /></td>
  </tr>
</table>

--

<!-- .element: data-transition="none" -->
#### Counting in Binary

<table>
  <tr>
    <td style="vertical-align: middle;"><img src="assets/images/daq-adc.svg" /></td>
    <td style="vertical-align: middle;"><img width="320" src="assets/images/binary-2.svg" /></td>
  </tr>
</table>

--

<!-- .element: data-transition="none" -->
#### Counting in Binary

<table>
  <tr>
    <td style="vertical-align: middle;"><img src="assets/images/daq-adc.svg" /></td>
    <td style="vertical-align: middle;"><img width="320" src="assets/images/binary-3.svg" /></td>
  </tr>
</table>

--

<!-- .element: data-transition="none" -->
#### Flash ADC

<table>
  <tr>
    <td style="vertical-align: middle;"><img src="assets/images/daq-adc.svg" /></td>
    <td style="vertical-align: middle;"><a href="https://en.wikipedia.org/wiki/Flash_ADC#/media/File:Flash_ADC.png"><img src="https://upload.wikimedia.org/wikipedia/commons/3/3a/Flash_ADC.png" /></a></td>
  </tr>
</table>

--

<!-- .element: data-transition="none" -->
#### Flash ADC

<table>
  <tr>
    <td style="vertical-align: middle;"><img src="assets/images/daq-adc-specs.svg" /></td>
    <td style="vertical-align: middle;"><a href="https://en.wikipedia.org/wiki/Flash_ADC#/media/File:Flash_ADC.png"><img src="https://upload.wikimedia.org/wikipedia/commons/3/3a/Flash_ADC.png" /></a></td>
  </tr>
</table>

--

<!-- .element: data-transition="none default" -->
#### Successive Approximation ADC
<table>
  <tr>
    <td style="vertical-align: middle;"><img src="assets/images/daq-adc.svg" /></td>
    <td style="vertical-align: middle;"><a href="https://en.wikipedia.org/wiki/Successive_approximation_ADC#/media/File:SA_ADC_block_diagram.png"><img width="300" height="240" src="https://upload.wikimedia.org/wikipedia/commons/6/61/SA_ADC_block_diagram.png" /></a></td>
  </tr>
</table>

--

<!-- .element: data-transition="none default" -->
#### Successive Approximation ADC
<table>
  <tr>
    <td style="vertical-align: middle;"><img src="assets/images/daq-adc-rate.svg" /></td>
    <td style="vertical-align: middle;"><a href="https://en.wikipedia.org/wiki/Successive_approximation_ADC#/media/File:SA_ADC_block_diagram.png"><img width="300" height="240" src="https://upload.wikimedia.org/wikipedia/commons/6/61/SA_ADC_block_diagram.png" /></a></td>
  </tr>
</table>

---

<!-- .element: data-transition="none" -->
#### How do you get data out of a computer?

![Control](assets/images/control.svg)

--

<!-- .element: data-transition="none" -->
#### TTL: Transistor-Transistor Logic

<table>
  <tr>
    <td style="vertical-align: middle;"><img src="assets/images/control-ttl.svg" /></td>
    <td class="fragment" style="vertical-align: middle;"><img src="assets/images/daq-ohm.svg" /></td>
  </tr>
</table>

--

<!-- .element: data-transition="none" -->
#### Brushless DC Motor: DC to AC converter

<table>
  <tr>
    <td style="vertical-align: middle;"><img src="assets/images/control-motor.svg" /></td>
    <td class="fragment" style="vertical-align: middle;"><a href="https://en.wikipedia.org/wiki/Brushless_DC_electric_motor#/media/File:Poles.jpg"><img width="300" height="240" src="https://upload.wikimedia.org/wikipedia/commons/6/6e/Poles.jpg" /></a></td>
  </tr>
</table>

--

<!-- .element: data-transition="none" -->
#### Pulse-Width Modulation (PWM)

<table>
  <tr>
    <td style="vertical-align: middle;"><img src="assets/images/control-pwm.svg" /></td>
    <td class="fragment" style="vertical-align: middle;">
      <div>
        <a href="https://en.wikipedia.org/wiki/Pulse-width_modulation#/media/File:PWM,_3-level.svg"><img width="320" height="221" src="https://upload.wikimedia.org/wikipedia/commons/8/8e/PWM%2C_3-level.svg" /></a>
        <div>
          <small>
          <span style="color:blue; font-size:100%; line-height:1;" title="Blue">■</span> Pulse-width modulated binary logic<br>
          <span style="color:red; font-size:100%; line-height:1;" title="Red">■</span> Induced sine-like current
          </small>
        </div>
      </div>
    </td>
  </tr>
</table>


</script>
</section>
