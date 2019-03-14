# webusb-workshop

This repository contains a few examples on how to connect with USB devices via the
WebUSB web interface:

* `01-connect-device` - Connect to a device & display its meta data
* `02-print-text` - Connect to POS compatible printer & print text
* `03-canvas-to-print` - Connect to POS compatible printer & print the contents of a `<canvas>` element

If you'd like to dig further into programmign POS printers, hav a look at [ESC/POS Mode Command Specifications](http://www.starmicronics.com/support/mannualfolder/escpos_cm_en.pdf) which describe all the commands from the POS spec that can be send to compatible printers in order to make some art™

## Running the examples

Any webserver will do, if you have Node.js installed, just run

```bash
npx http-server -p ${PORT}
```

and you're good to go.