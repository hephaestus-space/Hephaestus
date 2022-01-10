<h1 class="code-line" data-line-start=0 data-line-end=1 ><a id="ANDROMEDA_V40_0"></a><strong>ANDROMEDA V4.0</strong></h1>
<h2 class="code-line" data-line-start=1 data-line-end=2 ><a id="_The_ultimate_2021_at_list_model_rocket_avionics___1"></a><em>The ultimate (2022 at least) model rocket avionics 🛰️</em></h2>
<p class="has-line-data" data-line-start="3" data-line-end="4"><strong><em>3 min. reading</em></strong> ⏱️⏳</p>
<p class="has-line-data" data-line-start="5" data-line-end="6"><a href="https://travis-ci.org/joemccann/dillinger"><img src="https://travis-ci.org/joemccann/dillinger.svg?branch=master" alt="Build Status"></a></p>


![andromeda image](https://user-images.githubusercontent.com/81572328/148812566-0baa8a0e-1877-4990-b019-a14194858da2.jpeg)


<p class="has-line-data" data-line-start="7" data-line-end="9">Andromeda V4.0 is the latest avionics card from Hephaestus.<br>
It was entirely designed from scratch on easyeda by <a href="https://www.instagram.com/christianferracane/">Christian Ferracane</a>, and contains many SMD parts, to reduce the use of space to the bone and have a board as small and light as possible, while maintaining its technical qualities. 🚀</p>
<p class="has-line-data" data-line-start="10" data-line-end="12">I hope it will be a timeless and always usable PCB.<br>
I have put a lot of effort and dedication into designing all the features to fit every possible need when it comes to launch.</p>
<p class="has-line-data" data-line-start="13" data-line-end="15">In the files above you will find the gerber files (those to be sent to a company that produces PCB) to print the board, the list of necessary parts (BOM) and the pick and place files (in case you want to have the SDM parts welded by a third party company). 📈<br>
Also I am attaching some context images to help understand how to assemble everything and the schematics that can help someone who wants to make their own board from scratch).</p>
<h2 class="code-line" data-line-start=16 data-line-end=17 ><a id="Features_16"></a>Features</h2>
<ul>
<li class="has-line-data" data-line-start="18" data-line-end="19">microcontroller with ARM Cortex-M7 processor at 600 MHz</li>
<li class="has-line-data" data-line-start="19" data-line-end="20">Float point math unit, 64 &amp; 32 bits</li>
<li class="has-line-data" data-line-start="20" data-line-end="21">1984K Flash, 1024K RAM (512K tightly coupled), 1K EEPROM (emulated)</li>
<li class="has-line-data" data-line-start="21" data-line-end="22">USB device 480 Mbit / sec &amp; USB host 480 Mbit / sec</li>
<li class="has-line-data" data-line-start="22" data-line-end="23">three-axis gyroscope</li>
<li class="has-line-data" data-line-start="23" data-line-end="24">three-axis accelerometer</li>
<li class="has-line-data" data-line-start="24" data-line-end="25">attitude control sensor</li>
<li class="has-line-data" data-line-start="25" data-line-end="26">barometer</li>
<li class="has-line-data" data-line-start="26" data-line-end="27">altimeter</li>
<li class="has-line-data" data-line-start="27" data-line-end="28">thermometer</li>
<li class="has-line-data" data-line-start="28" data-line-end="29">4 switchable 12V Pyro outputs to be used to power whatever you want</li>
<li class="has-line-data" data-line-start="29" data-line-end="30">power supply on a quick-fit terminal block</li>
<li class="has-line-data" data-line-start="30" data-line-end="31">on and off switch</li>
<li class="has-line-data" data-line-start="31" data-line-end="32">Speaker/Buzzer</li>
<li class="has-line-data" data-line-start="32" data-line-end="33">LED signaling light</li>
<li class="has-line-data" data-line-start="33" data-line-end="34">Voltage regulator</li>
<li class="has-line-data" data-line-start="34" data-line-end="35">support for two TWM servomotors</li>
<li class="has-line-data" data-line-start="35" data-line-end="36">Flash memory 128MB</li>
<li class="has-line-data" data-line-start="36" data-line-end="37">Sd card reader</li>
<li class="has-line-data" data-line-start="37" data-line-end="38">Voltage meter</li>
<li class="has-line-data" data-line-start="38" data-line-end="39">Double analog signal (Rx + Tx) on external pins</li>
<li class="has-line-data" data-line-start="39" data-line-end="40">Additional external SPI communication pins</li>
<li class="has-line-data" data-line-start="40" data-line-end="41">Additional external I²C communication pins</li>
</ul>
<p class="has-line-data" data-line-start="43" data-line-end="44">The project was entirely carried out by <a href="https://www.instagram.com/christianferracane/">Christian Ferracane</a> on EasyEda, here his <a href="ferracanechristian.it@gmail.com">email</a> (and  <a href="https://www.instagram.com/christianferracane/">Instagram</a>) for any specific request.</p>
<p class="has-line-data" data-line-start="46" data-line-end="47">As <a href="https://www.instagram.com/christianferracane/">Christian Ferracane</a> writes on the <a href="https://www.hephaestus.space">Hephaestus’website</a></p>
<blockquote>
<p class="has-line-data" data-line-start="48" data-line-end="49">This PCB board, now in its fourth iteration, is in effect the beating heart of the stabilization and data recording system.</p>
</blockquote>


![Photo View_2021-11-15](https://user-images.githubusercontent.com/81572328/148813023-46b82f6c-ad7f-4fcc-a28d-31333eee7fd0.png)

![Photo View_2021-11-15 (1)](https://user-images.githubusercontent.com/81572328/148813028-a8078862-7ab2-4864-b194-4344eb769f45.png)


<h2 class="code-line" data-line-start=51 data-line-end=52 ><a id="Tips_51"></a>Tips</h2>
<p class="has-line-data" data-line-start="53" data-line-end="54">My personal advice for PCB production are:</p>
<table class="table table-striped table-bordered">
<thead>
<tr>
<th>Name</th>
<th>Pros</th>
<th>Cons</th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="https://www.pcbway.com/setinvite.aspx?inviteid=500690">PCBway *</a></td>
<td>good (FAST!!)  support, fast production and shipment. Matte color silkscreen.</td>
<td>high price compared to competitors</td>
</tr>
<tr>
<td><a href="https://jlcpcb.com/">JLC PCB</a></td>
<td>fast productions, great customer service, fantastic pcb quality, EasyEda/LCSC support</td>
<td>Less customizable PCB (small details)</td>
</tr>
<tr>
<td><a href="https://www.nextpcb.com/?utm_campaign=NextPCB&amp;adgroupid=107998757886&amp;utm_source=google&amp;utm_medium=cpc&amp;keyword=nextpcb&amp;device=c&amp;network=g&amp;gclid=Cj0KCQiAoNWOBhCwARIsAAiHnEhYOf5u8YlR6fYUBS94bxhggXtSbDgVbZzmA3PcecFDAdKxRAvJiikaAv7sEALw_wcB">NextPcb*</a></td>
<td>Very kind support, fast production. Matte color silkscreen without extra. A LOT OF CUPONS</td>
<td>Maybe shipping was a little long but i don’t even think it’s their fault</td>
</tr>
</tbody>
</table>
<p class="has-line-data" data-line-start="63" data-line-end="64">“*”&quot; = Affiliate link, but my integrity is more important than money. Reviews are 100% honest.</p>
<h2 class="code-line" data-line-start=66 data-line-end=67 ><a id="Links_66"></a>Links</h2>
<table class="table table-striped table-bordered">
<thead>
<tr>
<th>Social</th>
<th>link</th>
</tr>
</thead>
<tbody>
<tr>
<td>Instagram</td>
<td><a href="https://www.instagram.com/hephaestus.space/">https://www.instagram.com/hephaestus.space/</a></td>
</tr>
<tr>
<td>Youtube</td>
<td><a href="https://www.youtube.com/channel/UC_j1_9UICSkZTVNIxCL9Fsg">https://www.youtube.com/channel/UC_j1_9UICSkZTVNIxCL9Fsg</a></td>
</tr>
<tr>
<td>Twitter</td>
<td><a href="https://twitter.com/hephaestuspace">https://twitter.com/hephaestuspace</a></td>
</tr>
<tr>
<td>Reddit</td>
<td><a href="https://www.reddit.com/user/hephaestus_space">https://www.reddit.com/user/hephaestus_space</a></td>
</tr>
<tr>
<td>GitHub</td>
<td><a href="https://github.com/hephaestus-space">https://github.com/hephaestus-space</a></td>
</tr>
<tr>
<td>Arduino Projects</td>
<td><a href="https://create.arduino.cc/projecthub/hephaestus-space">https://create.arduino.cc/projecthub/hephaestus-space</a></td>
</tr>
</tbody>
</table>


![Schematic_andromeda 4 0 _2021-11-15](https://user-images.githubusercontent.com/81572328/148813079-d6b9d864-c922-44c7-8824-98913452f9fc.png)



<h2 class="code-line" data-line-start=79 data-line-end=80 ><a id="License_79"></a>License</h2>
<p class="has-line-data" data-line-start="81" data-line-end="86">NC<br>
(non commercial: i’m broke af mate)<br>
ps: if you use it for commercial purposes despite the explicit request not to do it at least give me a little something  plz ;)<br>
<a href="https://ko-fi.com/hephaestus">buy me a coffee</a> ☕<br>
<strong>OPEN SOURCE POWAH!</strong></p>

