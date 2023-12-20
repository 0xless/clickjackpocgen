# clickjackpocgen
Simple PoC generator for clickjacking vulnerabilities. Access it at: https://0xless.github.io/clickjackpocgen/  
It's an early working version, feel free to report any bugs or imprevement ideas.

## Motivation
`clickjackpocgen` was developed to quickly generate customizable clickjacking attacks demos.  
The tool is very straightforward and it's focused on usability instead of functionalities.  
`clickjackpocgen` was designed to help security professionals or hobbists to generate clickjacking PoCs, it's not suitable to generate "real" weaponized pages.

## Features
The tool offers some configurable options. It allows:
- To choose the URL to load in the iframe
- The positioning of the "clickjacked area" using mouse interactions, or `wasd` and `←↑→↓` buttons
- Personalizing the text on the "clickjacked area" during the configuration (to capture screenshots)
- Exporting a PoC page with invisible "clickjacked area"
- Personalizing alert text triggered on "clickjacked area" click

While it's easy to manually configure the PoC page exported, `clickjackpocgen` focuses on generating PoCs and doesn't support weaponizing pages.

## Known limitations
The tool allows to draw "clickjacked areas" on the screen in specific positions.
When resizing the screen, such position is fixed and might end up "outside" of the resized windows.
There is no easy way to work around this limitation using this approach as target websites will probably be responsive and change the layout of the page depending on the size of the window.

## Usage
Visit https://0xless.github.io/clickjackpocgen/ and follow the instructions at the bottom of the page.

## License
This project is licensed under the GPL-3.0 [License](https://github.com/0xless/clickjackpocgen/blob/main/LICENSE).
