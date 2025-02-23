# Flag Icons CA

A collection of Canadian flag icons for use in web and mobile applications. It is meant to be an extension to [Flag Icons Library](https://github.com/lipis/flag-icons). See the **example.html** file for detailed usage.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Disclaimer](#disclaimer)
- [Credits](#credits)

## Installation
You can download the project locally and include it in your project. At this time there is no CDN available.

## Usage
This library can be used standalone:
```
<link rel="stylesheet" href="./css/flag-icons-ca.min.css" />
```

It can also be used in cunjunction with the existing [Flag Icons Library](https://github.com/lipis/flag-icons). Always include the custom library first so the official library supercedes any common classes :
```
<link
  rel="stylesheet"
  href="./css/flag-icons-ca.min.css"
/>
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/gh/lipis/flag-icons@7.2.3/css/flag-icons.min.css"
/>
```

For using the flags inline with text add the classes `.fi` and `.fi-ca-xx` (where `ca-xx` is the [ISO 3166-2 subdivision](https://www.iso.org/obp/ui/#iso:code:3166:CA) or "province" code) to an empty `span`. If you want to have a squared version flag then add the class fis as well. Example:
```
<div><span class="fi fi-ca-ab"></span> Alberta</div>
<div><span class="fi fi-ca-ab fis"></span> Alberta</div>
```

## License
This library is **Public Domain**. Feel free to use it at your leisure, but references are always welcome.

## Disclaimer
This library is provided "as-is," without any express or implied warranty. In no event shall the authors be held liable for any damages arising from the use of this library. Use it at your own risk.

## Credits
- [Flag Icons Library](https://github.com/lipis/flag-icons)
- Wikipedia [File:Flag of Alberta.svg](https://en.m.wikipedia.org/wiki/File:Flag_of_Alberta.svg)
- Wikipedia [File:Flag of British Columbia.svg](https://en.m.wikipedia.org/wiki/File:Flag_of_British_Columbia.svg)
- Wikipedia [File:Flag of Manitoba.svg](https://en.m.wikipedia.org/wiki/File:Flag_of_Manitoba.svg)
- Wikipedia [File:Flag of New Brunswick.svg](https://en.m.wikipedia.org/wiki/File:Flag_of_New_Brunswick.svg)
- Wikipedia [File:Flag of Newfoundland and Labrador.svg](https://en.m.wikipedia.org/wiki/File:Flag_of_Newfoundland_and_Labrador.svg)
- Wikipedia [File:Flag of Nova Scotia.svg](https://en.m.wikipedia.org/wiki/File:Flag_of_Nova_Scotia.svg)
- Wikipedia [File:Flag of the Northwest Territories.svg](https://en.m.wikipedia.org/wiki/File:Flag_of_the_Northwest_Territories.svg)
- ~~Wikipedia [File:Flag of Nunavut.svg](https://en.m.wikipedia.org/wiki/File:Flag_of_Nunavut.svg)~~ Unused due to copyright concerns.
- Openclipart [Flag of Nunavut, Canada](https://openclipart.org/detail/24402/flag-of-nunavut-canada)
- Wikipedia [File:Flag of Ontario.svg](https://en.m.wikipedia.org/wiki/File:Flag_of_Ontario.svg)
- Wikipedia [File:Flag of Prince Edward Island.svg](https://en.m.wikipedia.org/wiki/File:Flag_of_Prince_Edward_Island.svg)
- Wikipedia [File:Flag of Quebec.svg](https://en.wikipedia.org/wiki/File:Flag_of_Quebec.svg)
- Wikipedia [File:Flag of Saskatchewan.svg](https://en.m.wikipedia.org/wiki/File:Flag_of_Saskatchewan.svg)
- Wikipedia [File:Flag of Yukon.svg](https://en.m.wikipedia.org/wiki/File:Flag_of_Yukon.svg)