# Support Palestine
This repo contains website banner for support Palestine. It is cloned with some modifications from [Support-Palestine-Banner](https://github.com/Safouene1/support-palestine-banner) repo.


## Banner for websites to show support for Palestine
Use this snippet to show your support for Palestinians on top of your website.
![image](https://github.com/akhyariz/support-palestine-website-banner/assets/182084/3a6cafce-95fc-40f7-bc02-4c9a91015662)

## Demo
[Akhyari Zudhi's Blog](https://blog.ers.web.id)

## About the Website Banner
This code adds a small black banner on top of your website with Palestinian flag and support message. It links to [International Networking for Humanitarian INH](https://kitabisa.com/orang-baik/7617a239efacb2c3894cf39d8045fc20) X [Kitabisa](https://kitabisa.com) donation site but you can change the link to point to a support channel of your choice.

## Installation Banner
Just copy this code to your template right after the opening `<body>` tag.

```html

<style>
/* CSS Reset */
html {
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: inherit;
}

* {
  margin: 0;
  padding: 0;
}
body {
  margin-top: 34px;
}
.flag-background {
  background: darkgreen;
  width: 40px;
  height: 24px;
  margin: auto;
}
.flag-top {
  background: black;
  width: 40px;
  height: 8px;
  z-index: 1;
}
.flag-middle {
  background: white;
  height: 8px;
  width: 40px;
  z-index: 1;
}
.flag-triangle {
  background: auto;
  border-top: 12px solid transparent;
  border-bottom: 12px solid transparent;
  border-left: 20px solid red;
  z-index: 2;
  position: relative;
  top: -16px;
  left: 0;
}

.support-palestine,
.support-palestine:visited {
  position: absolute;
  left: 0;
  top: 0;
  right: 0;
  background: rgb(20, 20, 20);
  display: flex;
  justify-content: center;
  padding-top: 5px;
  padding-bottom: 5px;
  z-index: 10000;
  text-decoration: none;
  font-family: arial;
}
.support-palestine:hover,
.support-palestine:active {
  background: black;
  display: flex;
  background: rgb(80, 80, 80);
  text-decoration: none;
}
.support-palestine__flag {
  margin-right: 10px;
}

.support-palestine__label {
  color: white;
  font-size: 12px;
  line-height: 24px;
}
</style>

    <div class="top-banner">
      <a class="support-palestine" href="https://kitabisa.com/campaign/daruratgaza2023" rel="nofollow noopener" target="_blank" title="Donate to support palestine">
        <div aria-label="Flag of palestine" class="support-palestine__flag" role="img">
          <div class="flag-background">
            <div class="flag-top"></div>
            <div class="flag-middle"></div>
            <div class="flag-triangle"></div>
          </div>
        </div>
        <div class="support-palestine__label">Donate to support Palestine</div>
      </a>
    </div>

```
