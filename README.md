# Coding.-am
<html lang="am"><head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Purple rain By | Professional</title>
    <style>
         
      @import url("https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@700&display=swap");
      * {
        margin: 0;
        font-family: "JetBrains Mono", monospace;
        font-weight: 1000;
      }
      audio {
        filter: sepia(20%) saturate(70%) grayscale(1) contrast(99%) invert(12%);
        width: 170px;
        height: 25px;
      }
      body * {
        font-weight: 1000;
      }
      body {
        overflow-y: hidden;
      }
    </style>
    </head><body style="background-color: rgb(16, 19, 20);">

        <canvas id="canvas" width="1500" height="1500"></canvas>

    

  <style>#tr-popup,#tr-popup * {all: unset;}#tr-popup {font: 15px "Segoe UI", Arial, Helvetica, sans-serif;color: #222;padding: 24px;display: block;z-index: 2147483647;position: absolute;max-width: 400px;min-width: 300px;direction: ltr;text-align: left;background: #fff;border-radius: 2px;box-sizing: border-box;box-shadow: 0 0 0 1px rgba(0, 0, 0, 0.1), 0 12px 24px 0 rgba(51, 51, 51, 0.3);transition: opacity, visibility;transition-duration: 0.2s;}#tr-popup[data-hidden="true"] {opacity: 0;visibility: hidden;}#tr-popup[data-position="top"] {margin-top: -12px;}#tr-popup[data-position="bottom"] {margin-top: 12px;}#tr-popup .tr-popup__arrow {top: 100%;left: 50%;width: 26px;height: 12px;display: block;position: absolute;margin-left: -13px;margin-top: -1px;background: url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNiIgaGVpZ2h0PSIxMiI+PHBhdGggZD0iTTAgMGwxMyAxMkwyNiAweiIgb3BhY2l0eT0iLjEiLz48cGF0aCBkPSJNMSAwbDEyIDExTDI1IDB6IiBmaWxsPSIjZmZmIi8+PC9zdmc+") no-repeat;}#tr-popup[data-position="bottom"] .tr-popup__arrow {top: auto;bottom: 100%;margin-bottom: -1px;transform: rotate(180deg);}#tr-popup .tr-popup__value,#tr-popup .tr-popup__block {word-wrap: break-word;white-space: pre-wrap;}[data-type="trSpan"][data-translated="true"][data-source-lang="ja"],[data-type="trSpan"][data-translated="true"][data-source-lang="zh"],#tr-popup .tr-popup__title_original,#tr-popup .tr-popup__block_a,#tr-popup .tr-popup__block_b,#tr-popup .tr-popup__button {font-family: "Segoe UI", Arial, Helvetica, sans-serif !important;}#tr-popup .tr-popup__title_original {font-weight: bold;}#tr-popup .tr-popup__block {display: block;}#tr-popup .tr-popup__link {cursor: pointer;-webkit-user-select: none;user-select: none;}#tr-popup .tr-popup__link_suggest {color: #1378d7;font-size: 13px;line-height: 18px;margin-right: 22px;}#tr-popup .tr-popup__link_suggest:hover,#tr-popup .tr-popup__link_suggest:active {color: #000;}#tr-popup .tr-popup__logo {height: 18px;opacity: 0.3;display: inline-block;transition: opacity 0.2s;vertical-align: top;}#tr-popup .tr-popup__logo_company {width: 34px;filter: brightness(0);background: url("https://yastatic.net/s3/trbro/v20.5.1.0/i/service_logo.svg");background-size: 34px;background-position: 0 -18px;}#tr-popup[lang="ru"] .tr-popup__logo_company {background-position: 0 0;}#tr-popup .tr-popup__logo_service {width: 42px;background: url("https://yastatic.net/s3/trbro/v20.5.1.0/i/service_name.svg");margin-left: 2px;background-size: 63px;background-position: 0 -18px;}#tr-popup[lang="ru"] .tr-popup__logo_service {width: 57px;background-position: 0 0;}#tr-popup[lang="uk"] .tr-popup__logo_service {width: 56px;background-position: 0 -36px;}#tr-popup[lang="tr"] .tr-popup__logo_service {width: 25px;background-position: 0 -54px;}#tr-popup .tr-popup__link_service:hover .tr-popup__logo {opacity: 0.6;}#tr-popup .tr-popup__input {width: 100%;height: 80px;resize: none;border: 2px solid #e5e5e5;padding: 8px;display: block;font-size: 15px;box-sizing: border-box;border-radius: 2px;}#tr-popup .tr-popup__input:focus {border-color: #bbb;}#tr-popup .tr-popup__block_a,#tr-popup .tr-popup__block_b {margin-top: 16px;}#tr-popup .tr-popup__block_a {display: flex;justify-content: space-between;}#tr-popup .tr-popup__block_b {position: relative;}#tr-popup .tr-popup__block_submit {text-align: right;margin-top: 24px;}#tr-popup .tr-popup__overlay {top: 0;left: 0;right: 0;bottom: 0;position: absolute;}#tr-popup .tr-popup__overlay_submitted {color: #999;z-index: 1;display: flex;background: #fff;align-items: center;justify-content: center;}#tr-popup:not([data-expanded="true"]) .tr-popup__block_b,#tr-popup:not([data-submitted="true"]) .tr-popup__overlay_submitted {display: none;}#tr-popup .tr-popup__menu {font-size: 13px;opacity: 0;visibility: hidden;white-space: nowrap;position: absolute;bottom: 100%;margin-bottom: 8px;padding: 4px 14px;z-index: 1;background-color: #f5f5f5;border: 1px solid #bbb;border-radius: 2px;box-shadow: 0px 0 0 1px rgba(0, 0, 0, 0.1), 0 8px 14px 0 rgba(51, 51, 51, 0.3);}#tr-popup[data-menu-position="left"] .tr-popup__menu {right: 0;}#tr-popup[data-menu="true"] .tr-popup__menu {opacity: 1;visibility: visible;}#tr-popup .tr-popup__menu:hover {background-color: #efefef;}#tr-popup .tr-popup__button {cursor: pointer;display: inline-block;-webkit-user-select: none;user-select: none;}#tr-popup .tr-popup__button_menu,#tr-popup .tr-popup__button_close {top: 4px;width: 20px;height: 20px;opacity: 0.3;position: absolute;}#tr-popup .tr-popup__button_close {right: 4px;background: url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyMCIgaGVpZ2h0PSIyMCI+PHBhdGggZD0iTTkuMjkzIDEwTDYuMTQ2IDYuODU0YS41LjUgMCAxIDEgLjcwOC0uNzA4TDEwIDkuMjkzbDMuMTQ2LTMuMTQ3YS41LjUgMCAwIDEgLjcwOC43MDhMMTAuNzA3IDEwbDMuMTQ3IDMuMTQ2YS41LjUgMCAwIDEtLjcwOC43MDhMMTAgMTAuNzA3bC0zLjE0NiAzLjE0N2EuNS41IDAgMCAxLS43MDgtLjcwOEw5LjI5MyAxMHoiLz48L3N2Zz4=");}#tr-popup .tr-popup__button_menu {right: 24px;background: url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGhlaWdodD0iMjAiIHdpZHRoPSIyMCI+PHBhdGggZD0ibTUgNnYxaDEwdi0xaC0xMHptMCAzdjFoMTB2LTFoLTEwem0wIDN2MWgxMHYtMWgtMTB6Ii8+PC9zdmc+");}#tr-popup .tr-popup__button_menu:hover,#tr-popup .tr-popup__button_close:hover {opacity: 0.5;}#tr-popup .tr-popup__button_close:active {opacity: 0.6;}#tr-popup[data-menu="true"] .tr-popup__button_menu {opacity: 1;}#tr-popup .tr-popup__button_submit {color: #000;height: 28px;padding: 0 16px;font-size: 13px;min-width: 112px;background: #fc0;box-sizing: border-box;text-align: center;line-height: 28px;border-radius: 2px;}#tr-popup .tr-popup__button_submit:hover {background: #ffb800;}#tr-popup .tr-popup__button_submit:active {background: #ffa400;}#tr-popup[data-invalid="true"] .tr-popup__button_submit {color: rgba(0, 0, 0, 0.5);cursor: default;background: rgba(0, 0, 0, 0.1);}[data-type="trSpan"][data-selected="true"] {color: #222 !important;background: #cce4f7 !important;}[data-type="trSpan"] {font-size: inherit !important;}</style>
  
    <canvas id="canvas" width="692" height="652"></canvas>
    <div class="inputs" style="position: absolute; left: 0; top: 0; padding: 10px; color: purple">
      <table>
        <tbody><tr>
          <td style="color: rgb(25, 67, 194) !important;"><ya-tr-span data-index="0-0" data-translated="true" data-source-lang="en" data-target-lang="hy" data-value="Drop Count" data-translation="Միավորների քան-выпадений" data-ch="0" data-type="trSpan">Միավորների քան-выпадений</ya-tr-span></td>
          <td style="color: rgb(25, 67, 194) !important;">
            <input type="number" onchange="changeCount(this.value)" min="1" value="500">
          </td>
        </tr>
        <tr>
          <td style="color: rgb(25, 67, 194) !important;"><ya-tr-span data-index="1-0" data-translated="true" data-source-lang="en" data-target-lang="hy" data-value="Drop Width" data-translation="Լայնությունը անկման" data-ch="0" data-type="trSpan">Լայնությունը անկման</ya-tr-span></td>
          <td style="color: rgb(25, 67, 194) !important;">
            <input type="number" onchange="changeDropWidth(this.value)" min="1" value="2">
          </td>
        </tr>
        <tr>
          <td style="color: rgb(25, 67, 194) !important;"><ya-tr-span data-index="2-0" data-translated="true" data-source-lang="en" data-target-lang="hy" data-value="Drop Height" data-translation="Բարձրությունը անկման" data-ch="0" data-type="trSpan">Բարձրությունը անկման</ya-tr-span></td>
          <td style="color: rgb(25, 67, 194) !important;">
            <input type="number" onchange="changeDropHeight(this.value)" min="1" value="15">
          </td>
        </tr>
        <tr>
          <td style="color: rgb(25, 67, 194) !important;"><ya-tr-span data-index="3-0" data-translated="true" data-source-lang="en" data-target-lang="hy" data-value="Gravity" data-translation="Ինքնահոս" data-ch="0" data-type="trSpan">Ինքնահոս</ya-tr-span></td>
          <td style="color: rgb(25, 67, 194) !important;">
            <input type="number" onchange="changeGravity(this.value)" min="1" value="10">
          </td>
        </tr>
        <tr>
          <td style="color: rgb(25, 67, 194) !important;"><ya-tr-span data-index="4-0" data-translated="true" data-source-lang="en" data-target-lang="hy" data-value="Color" data-translation="Գույնը" data-ch="0" data-type="trSpan">Գույնը</ya-tr-span></td>
          <td style="color: rgb(25, 67, 194) !important;">
            <input type="color" value="#c537E6" id="color">
          </td>
        </tr>
        <tr>
          <td style="color: rgb(25, 67, 194) !important;"><ya-tr-span data-index="5-0" data-translated="true" data-source-lang="en" data-target-lang="hy" data-value="Background Color" data-translation="Ֆոնի գույնը" data-ch="0" data-type="trSpan">Ֆոնի գույնը</ya-tr-span></td>
          <td style="color: rgb(25, 67, 194) !important;">
            <input type="color" value="#000000" id="backgroundColor">
          </td>
        </tr>
        <tr>
          <td style="color: rgb(25, 67, 194) !important;"><ya-tr-span data-index="6-0" data-translated="true" data-source-lang="en" data-target-lang="hy" data-value="Eminem - Stan" data-translation="Էմինեմը - Stan" data-ch="0" data-type="trSpan">Էմինեմը - Stan</ya-tr-span></td>
          <td style="color: rgb(25, 67, 194) !important;">
            <audio controls="" controlslist="nodownload noplaybackrate">
              <source src="Eminem.mp3" type="audio/mpeg">
              Your browser does not support the audio element.
            </audio>
          </td>
        </tr>
      </tbody></table>
    </div>
    <footer style="position: absolute; bottom: 0px; padding: 20px; margin: 0px auto; left: 0px; right: 0px; text-align: center; color: rgb(25, 67, 194) !important;"><ya-tr-span data-index="7-0" data-translated="true" data-source-lang="en" data-target-lang="hy" data-value=" Made with ❤️ by " data-translation=" Պատրաստված ❤️ " data-ch="0" data-type="trSpan"> Պատրաստված ❤️ </ya-tr-span><a id="nare" href="https://servetg.com" target="blank"><ya-tr-span data-index="7-0" data-translated="true" data-source-lang="en" data-target-lang="hy" data-value=" Servet Gulnaroglu " data-translation=" Սերվեթ Гульнароглу " data-ch="0" data-type="trSpan"> Professional#3155 </ya-tr-span></a>
      <span style="position: relative">
        <a href="https://www.youtube.com/@armen5505/videos" target="blank">
          <img style="position: relative; top: 5px" src="Youtube.jpg" width="30px">
        </a>
      </span>
    </footer>
    <script src="indexs.js"></script>
  

<div id="tr-popup" class="tr-popup" translate="no" data-hidden="true" data-invalid="true" data-disabled="false" lang="ru"><div class="tr-popup__block"><span class="tr-popup__title_original">Оригинальный текст:</span> <span class="tr-popup__value"></span></div><div class="tr-popup__block tr-popup__block_a"><span class="tr-popup__link tr-popup__link_suggest" data-action="expand">Предложить перевод</span><a href="https://translate.yandex.ru" class="tr-popup__link tr-popup__link_service" target="_blank" data-action="navigate"><span class="tr-popup__logo tr-popup__logo_company"></span><span class="tr-popup__logo tr-popup__logo_service"></span></a></div><div class="tr-popup__block tr-popup__block_b"><textarea class="tr-popup__input" spellcheck="false" autocapitalize="off" autocorrect="off" autocomplete="off" maxlength="1000"></textarea><div class="tr-popup__block tr-popup__block_submit"><span role="button" class="tr-popup__button tr-popup__button_submit" data-action="send">Отправить</span></div><div class="tr-popup__overlay tr-popup__overlay_submitted">Спасибо, перевод отправлен</div></div><span role="button" class="tr-popup__button tr-popup__button_close" data-action="clickClose"></span><span role="button" class="tr-popup__button tr-popup__button_menu" data-action="clickMenu"><span class="tr-popup__menu" data-action="disablePopup">Отключить подсказку с оригинальным текстом</span></span><span class="tr-popup__arrow"></span></div></body></html>
