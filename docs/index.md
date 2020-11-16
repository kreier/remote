# Terminal and Remote for Bluetooth Low Energy 

- [Simple terminal](./simple/)
- [Progressive Webapp](./loginov/)
- [Analog controller](./analog/)
- [Digital controller](./digital/)

And this is how it looks like:

        <div id="joystick">
        	<div id="joystick-direction">
        		<div class="joystick-row">
        			<div class="joystick-cell">
        			</div>
        			<div class="joystick-cell" id="button_UP">
        			  <img src="digital/button/button_UP.svg" class="button-image">
        		    </div>
        			<div class="joystick-cell">
        			</div>
        		</div>
        		<div class="joystick-row">
        			<div class="joystick-cell" id="button_LEFT">
        			  <img src="digital/button/button_LEFT.svg" class="button-image">
        			</div>
        			<div class="joystick-cell">
        			</div>
        			<div class="joystick-cell" id="button_RIGHT">
        			  <img src="digital/button/button_RIGHT.svg" class="button-image">
        			</div>
        		</div>
        		<div class="joystick-row">
        			<div class="joystick-cell">
        			</div>
        			<div class="joystick-cell" id="button_DOWN">
        			  <img src="digital/button/button_DOWN.svg" class="button-image">
        			</div>
        			<div class="joystick-cell">
        			</div>
        		</div>
        	</div>
        	<div id="joystick-rxtx">
        		<div class="joystick-row">RX: ____________________
        		</div>
        		<div class="joystick-row">TX: ____________________
        		</div>
        		<div class="joystick-row">MENU      START
        		</div>
        	</div>
        	<div id="joystick-button">
        		<div class="joystick-row">
        			<div class="joystick-cell">
        			</div>
        			<div class="joystick-cell">
        			  <img src="digital/button/Xbox_button_Y.svg" class="button-image">
        			</div>
        			<div class="joystick-cell">
        			</div>
        		</div>
        		<div class="joystick-row">
        			<div class="joystick-cell">
        			  <img src="digital/button/Xbox_button_X.svg" class="button-image">
        			</div>
        			<div class="joystick-cell">
        			</div>
        			<div class="joystick-cell">
        			  <img src="digital/button/Xbox_button_B.svg" class="button-image">
        			</div>
        		</div>
        		<div class="joystick-row">
        			<div class="joystick-cell">
        			</div>
        			<div class="joystick-cell">
        			  <img src="digital/button/Xbox_button_A.svg" class="button-image">
        			</div>
        			<div class="joystick-cell">
        			</div>
        		</div>
        	</div>
        </div>

## Source code used

### Progressive WebApp

This interface is a copy of Danila Loginov and his [Github repository](https://github.com/loginov-rocks/Web-Bluetooth-Terminal).

### Analog controller

It uses the [html controller project from Yoann Moinet](https://github.com/yoannmoinet/nipplejs) that really looks and works great.

