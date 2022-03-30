<div id="top"></div>

<!-- PROJECT LOGO -->
<br />

<div align="center">

<table>
  <tr>
    <td>
     <img src="../Panglong_Keyboard-logo.png" alt="Panglong Keyboard" width="80" height="80">
    </td>
    <td>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/android/android-original.svg" width="80" height="80"/>
    </td>
  </tr>
</table>

  <h3 align="center">Panglong Keyboard (လွၵ်းမိုဝ်းပၢင်လူင်) - တွၼ်ႈတႃႇ Android</h3>

</div>

<!-- TABLE OF CONTENTS -->

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">လွင်ႈတၢင်း</a>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">ၵပ်းသိုပ်ႇ</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

<div align="center">
  <figure>
    <img src="demo_android.jpeg" alt="Demo: Android" height="500"/>
    <br />
    <figcaption>ၸႂ်ႉတိုဝ်းလွၵ်းမိုဝ်းပၢင်လူင် ၼိူဝ် Android</figcaption>
  </figure>
</div>
<br />

Keyboard app ၼိူဝ် Android ဢမ်ႇၸၢင်သႂ်ႇပဵၼ် single-standalone မိူၼ်ၼိူဝ် iOS, Keyboard app ဢၼ်ႁဵတ်းဝႆႉတႃႇ android တေသႂ်ႇမႃးပႃးလၢႆ" ၽႃႇသႃႇ
မိူၼ်ၼင်ႇ Google-Gboard, Microsoft-Swift Key ၶဝ်ၸိူဝ်းၼႆႉသႂ်ႇမႃးပႃးလိၵ်ႈတႆးယဝ်ႉ ၵူၺ်းႁၢင်ႈၽၢင်လွၵ်းမိုဝ်းဢမ်ႇမိုတ်ႈတႃ
Gboard တႄႉငၢႆး" လွၵ်းမိုဝ်းပၢင်လူင်ယူႇ

<div align="center">
 <table>
  <tr>
    <td>
      <image src="google_Gboard.jpeg" width="200">
    </td>
    &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 
    <td>
      <image src="microsoft_Swiftkey.jpeg" width="200">
    </td>
  </tr>
  <tr>
    <td>
      Google-Gboard လွၵ်းမိုဝ်းတႆး
    </td>
    &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 
    <td>
      Microsoft-Swift-Key လွၵ်းမိုဝ်းတႆး
    </td>
  </tr>
</table> 
</div>

ၶဝ်သွင်ၸဝ်ႈၼႆႉ (Google Gboard and Microsoft Swift-Key) ဢမ်ႇၸႂ်ႈ open-source မီၶူဝ်ႊသၼႃး (ads) လႄႈၵၢၼ်ၵဵပ်းၶေႃႈမုၼ်းၽူႈၸႂ်ႉ။
ပိူင်လူင်တႄႈၵေႃႈ တႃႇလဵပ်ႈႁဵၼ်းလႄႈတႃႇ tai-developer ဢၼ်သူၼ်ၸႂ်ၶႂ်ႈလဵပ်ႈႁဵၼ်း ဢမ်ႇၼၼ်သိုပ်ႇၶူင်သၢင်ႁႂ်ႈၶႅမ်ႉလႅပ်ႈၵႂႃႇတၢင်းၼႃႈၼၼ်ႉ လႆႈပိုၼ်ၽႄႈဝႆႉပၼ်ၶႃႈ။

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- AOSP -->

## AOSP - LatinIME

AOSP - inputmethod/LatinIME is open-source project from android, they provide tools and starter for Android keyboard.

The day I start this project they current support only two-letter code (Shan is used three-letter code, shn).

**So, I've submited patch for AOSP too.**

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- Openboard -->

## Openboard

Opeboard is Android Keyboard app base on AOSP, and open-source.

The part I've modified is add patch I've created for AOSP.

<figure align="center">
  <img src="AOSP - Patch_android.png" width="500">
  <figcaption>AOSP  - Patch for support Shan language</figcaption>
</figure>

and Edit ScriptUtils.java place in
``` app/src/main/java/org/dslul/openboard/inputmethod/latin/utils/ScriptUtils.java ```

<figure align="center">
  <image src="scriptutils.png" width="400">
  <figcaption>app/src/main/java/org/dslul/openboard/inputmethod/latin/utils/ScriptUtils.java</figcaption>
</figure>

*Shan's Unicode is in the same block with Myanmar Unicode.*

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ROADMAP -->

## Roadmap

- [x] Android - [https://github.com/NoerNova/openboard](https://github.com/NoerNova/openboard)
  - [x] With auto correct dictionary.
  - [ ] Improved dictionary with more and more data.

See the [open issues](https://github.com/NoerNova/Panglong_Keyboards/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star ⭐️ ! Thanks again!

1. Android - [https://github.com/NoerNova/openboard/pulls](https://github.com/NoerNova/openboard/pulls)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- LICENSE -->

## License

Apache 2.0.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->

## ၵပ်းသိုပ်ႇ

NorHsangPha - [noernova.com](noernova.com) - noernova666@gmail.com

Project Link: [https://github.com/NoerNova/Panglong_Keyboards](https://github.com/NoerNova/Panglong_Keyboards)

<p align="right">(<a href="#top">back to top</a>)</p>
