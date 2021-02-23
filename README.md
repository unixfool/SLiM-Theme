# SLiM-Theme 
## [Simple Login Manager]

 `slim version 1.3.6` `FreeBSD 12.2-STABLE`
 
<p align="center">
  <img src="https://img.shields.io/badge/Maintained%3F-Yes-green?style=for-the-badge">
  <img src="https://img.shields.io/github/license/unixfool/SLiM-Theme?style=for-the-badge">
  <img src="https://img.shields.io/github/stars/unixfool/SLiM-Theme?style=for-the-badge">
  <img src="https://img.shields.io/github/forks/unixfool/SLiM-Theme?color=teal&style=for-the-badge">
  <img src="https://img.shields.io/github/issues/unixfool/SLiM-Theme?color=violet&style=for-the-badge">
 </p>

<b>Release note:</b> 
 * Add Username Msg.
 * Add Password Msg.
 * Add Welcome Msg.

FreeBSD SLiM Themes GitHub Night Style. <br/>
Screen Resolution: `1920x1080`<br/>
<b>Styles:</b>
 * Green
 * Blue
 * Red
 * Purple
 * Orange

 
 ### What is SLiM?
 
 SLiM is an acronym for "Simple Login Manager". <br/>
 SLiM is very Lightweight and easily configurable requires minimal dependencies.<br/>
 It therefore contributes towards a lightweight system for users that also like to use lightweight desktops such as Xfce, Openbox, and Fluxbox.
 
 # How To:
 
 FreeBSD Installation `SLiM`<br/>
 You can install SLiM with PKG or PORTS.<br/>
 
 ```
root@anaconda:~ # pkg install slim
 ```
 
 `NOTE:` If you install SLiM with PKG dont need install it again with PORTS. 
 
 ```
 root@anaconda:~ # cd /usr/ports/x11/slim && make install clean
 ```
 
 
 <b>NOTE:</b> If you install SLiM, Now you need to enable on rc.conf<br/>
 <b>NOTE:</b> you can use a editor like ee, vi, pico, nano, vim. the local file is: /etc/rc.conf<br/>
 <b>NOTE:</b> Or you can do it with `sysrc`
 
  ```
 root@anaconda:~ # sysrc slim_enable="YES"
 ```
 
 
 ## How To Set Theme.
 
 `Step 1:` Clone this repository. 
 
 ```
 root@anaconda:~ # git clone https://github.com/unixfool/SLiM-Theme.git
 root@anaconda:~ # cd SLiM-Theme/
 root@anaconda:~ # cp -R Blue /usr/local/share/slim/themes/
 root@anaconda:~ # cp -R Green /usr/local/share/slim/themes/
 root@anaconda:~ # cp -R Orange /usr/local/share/slim/themes/
 root@anaconda:~ # cp -R Purple /usr/local/share/slim/themes/
 root@anaconda:~ # cp -R Red /usr/local/share/slim/themes/
 ```
 
 
 `Step 2:` Edit SLiM config file.<br/>
 <b>NOTE:</b> Look at the end of file for: `#current_theme      default`<br/>
 <b>NOTE:</b> You can use; Blue / Green / Orange / Purple / Red<br/>
 
  * `current_theme Blue`
  * `current_theme Green`
  * `current_theme Orange`
  * `current_theme Purple`
  * `current_theme Red`
  
 <b> NOTE:</b> You only can set 1 Theme for SLiM, this is just a example of what themes you can use on the config file.<br/>
 <b> NOTE:</b> Just need to change names on the current_theme value.
  
  

  ### Preview
  
<table>
<thead>
<tr>
<th>Green</th>
<th>Blue</th>
</tr>
</thead>
<tbody>
<tr>
<td>
<a target="_blank" rel="noopener noreferrer" href="https://raw.githubusercontent.com/unixfool/SLiM-Theme/main/Green/screenshot.png">
<img src="https://raw.githubusercontent.com/unixfool/SLiM-Theme/main/Green/screenshot.png" alt="img" style="max-width:50%;">
</a>
</td>
<td><a target="_blank" rel="noopener noreferrer" href="https://raw.githubusercontent.com/unixfool/SLiM-Theme/main/Blue/screenshot.png">
<img src="https://raw.githubusercontent.com/unixfool/SLiM-Theme/main/Blue/screenshot.png" alt="img" style="max-width:50%;"></a></td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th>Red</th>
<th>Purple</th>
</tr>
</thead>
	<tbody>
	<tr>
		<td>
		<a target="_blank" rel="noopener noreferrer" href="https://raw.githubusercontent.com/unixfool/SLiM-Theme/main/Red/screenshot.png">
		<img src="https://raw.githubusercontent.com/unixfool/SLiM-Theme/main/Red/screenshot.png" alt="img" style="max-width:50%;">
		</a>
		</td>

		<td><a target="_blank" rel="noopener noreferrer" href="https://raw.githubusercontent.com/unixfool/SLiM-Theme/main/Purple/screenshot.png">
		<img src="https://raw.githubusercontent.com/unixfool/SLiM-Theme/main/Purple/screenshot.png" alt="img" style="max-width:50%;"></a></td>
		</tr>
	</tbody>
</table>

<table>
<thead>
<tr>
<th>Purple</th>
</tr>
</thead>
	<tbody>
	<tr>
		<td>
		<p><a target="_blank" rel="noopener noreferrer" href="https://raw.githubusercontent.com/unixfool/SLiM-Theme/main/Orange/screenshot.png">
		<img src="https://raw.githubusercontent.com/unixfool/SLiM-Theme/main/Orange/screenshot.png" alt="img" style="max-width:50%;">
		</a></p>
		</td>

		</tr>
	</tbody>
</table>
 
<p>
 <a href="https://www.buymeacoffee.com/unixfool"><img src="https://img.buymeacoffee.com/button-api/?text=Buy me a beer&emoji=🍺&slug=unixfool&button_colour=FFDD00&font_colour=000000&font_family=Cookie&outline_colour=000000&coffee_colour=ffffff"></a>
 
 [![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/donate?hosted_button_id=UFGGRHGXKW64W)
 
 </p>
