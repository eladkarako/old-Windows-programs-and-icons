<img width="300" src="scrnsave.png" /><br/>

<img width="300" src="ss3dfo.png" /><br/>

<img width="300" src="ssbezier.png" /><br/>

<img width="300" src="ssflwbox.png" /><br/>

<img width="300" src="ssmarque.png" /><br/>

<img width="300" src="ssmaze.png" /><br/>

<img width="300" src="ssmyst.png" /><br/>

<img width="300" src="sspipes.png" /><br/>

<img width="300" src="ssstars.png" /><br/>

<img width="300" src="sstext3d.png" /><br/>

screensavers are able to store some configuration in the registry, they are 100% exe with extra functionality...

<hr/>
`%1` meaning the file itself.

`"%1"` opens up the configuration if they do have one.
`rundll32.exe desk.cpl,InstallScreenSaver %l` installs them (it copies them to the Windows folder I guess)
`"%1" /S` tests them, self execute 

<hr/>

all patched up to be able to recognise large memory as well as scale GDI correctly with high DPI screens, but that's just tiny patch, they should be able to run correctly due to how simple they are..

