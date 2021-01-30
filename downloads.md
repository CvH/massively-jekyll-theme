---
layout: page
title: Downloads
description: 
---

![LE Download](assets/images/downloads/le_dl_tool.png){:style="margin-left: 60px;margin-right: auto; float: right;"} To create bootable USB or SD Card installation media for any LibreELEC supported platform please download the "LibreELEC USB-SD Creator" app and run it with administrator rights.

<ul class="icons alt">
<li><a href="http://releases.libreelec.tv/LibreELEC.USB-SD.Creator.Win32.exe" class="icon alt fa-windows" target="_blank"><span class="label">Windows</span> Windows</a></li>
<li><a href="http://releases.libreelec.tv/LibreELEC.USB-SD.Creator.macOS.dmg" class="icon alt fa-apple" target="_blank"><span class="label">MacOS</span> MacOS</a></li>
</ul>
<ul class="icons alt">
<li><a href="http://releases.libreelec.tv/LibreELEC.USB-SD.Creator.Linux-32bit.bin" class="icon alt fa-linux" target="_blank"><span class="label">Linux 32Bit</span> Linux 32Bit</a></li>
<li><a href="http://releases.libreelec.tv/LibreELEC.USB-SD.Creator.Linux-64bit.bin" class="icon alt fa-linux" target="_blank"><span class="label">Linux 64Bit</span> Linux 64Bit</a></li>
</ul>
<br><br><br><br>
<style>
.container {
  width: 100%;
  max-width: 100%;
  margin: 0 auto;
  display: grid;
  grid-template-columns: 1fr;
  grid-template-rows: auto;
  grid-gap: 30px;
  
}

@media only screen and (min-width: 500px) {
  .container {
    grid-template-columns: 1fr ;
  }  
  .item h1 {
    font-size: 30px;
  }
}

@media only screen and (min-width: 850px) {
  .container {
    grid-template-columns: 1fr 1fr;
  }
}

/* card */

.card {
  min-height: 100%;
  background: white;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  display: flex;
  flex-direction: column;
  text-decoration: none;
  color: #444;
  position: relative;
  top: 0;
  transition: all .1s ease-in;
}

.card:hover {
  top: -2px;
  box-shadow: 0 4px 5px rgba(0,0,0,0.2);
}

.card article {
  padding: 20px;
  display: flex;
  
  flex: 1;
  justify-content: space-between;
  flex-direction: column;
  
}
.card .thumb {
  padding-bottom: 60%;
  background-size: cover;
  background-position: center center;
}

.card p { 
  font-size: 13pt;
  flex: 1; /* make p grow to fill available space*/
  line-height: 1.4;
  margin: 0;
}

/* typography */
h1 {
  font-size: 20px;
  margin: 0;
  color: #333;
}

.card span {
  font-size: 12px;
  font-weight: bold;
  color: #999;
  text-transform: uppercase;
  letter-spacing: .05em;
  margin: 2em 0 0 0;
}
</style>

<div class="support-grid"></div>
  <div class="container">
    <div class="item">
          <a href="" class="card">
            <div class="thumb" style="background-image: url(assets/images/downloads/logo-rpi.png);"></div>
            <article>
              <h1>Raspberry Pi</h1>
          <p>for all kind of Raspberry Pi devices</p>
            </article>
          </a>
    </div>
    <div class="item">
      <a href="" class="card">
        <div class="thumb" style="background-image: url(assets/images/downloads/logo-generic.png);"></div>
        <article>
          <h1>Generic</h1>
          <p>for typcial PC hardware, Intel Nucs, Nettops and Laptops with x86 Hardware</p>
        </article>
      </a>
    </div>
    <div class="item">
          <a href="" class="card">
            <div class="thumb" style="background-image: url(assets/images/downloads/logo-allwinner.png);"></div>
            <article>
              <h1>Alwinner</h1>
          <p>for all kind of Allwinner devices</p>
            </article>
          </a>
    </div>
    <div class="item">
      <a href="" class="card">
        <div class="thumb" style="background-image: url(assets/images/downloads/logo-rockchip.png);"></div>
        <article>
          <h1>Rockchip</h1>
          <p>for all kind of Rockchip devices</p>
        </article>
      </a>
    </div>
    <div class="item">
      <a href="" class="card">
        <div class="thumb" style="background-image: url(assets/images/downloads/logo-amlogic.png);"></div>
        <article>
          <h1>Allwinner</h1>
          <p>for all kind of Amlogic devices</p>
        </article>
      </a>
    </div>
    <div class="item">
      <a href="" class="card">
        <div class="thumb" style="background-image: url(assets/images/downloads/logo-nxp.png);"></div>
        <article>
          <h1>NXP</h1>
          <p>for all kind of NXP devices</p>
        </article>
      </a>
    </div>
  </div> 