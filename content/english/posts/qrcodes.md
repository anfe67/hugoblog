---
title: "VCARD QR Codes in Inkscape"
date: 2020-05-19T11:40:29+02:00
publishdate: 2020-05-19T11:40:29+02:00
type: post
image: "QRCode.png"
tags: ["inkscape", "plugin", "python"]
categories:
- Python
- Application Plugins
comments: false
thumbnail: "QRCode.png"
---
# A Inkscape plugin to generate VCARD QR Codes.
This work is based on a inkscape plugin by Sergey Vedernikov, in turn based on the work of others. It is a little modification to the plugin
that Sergey proposed in a Inkscape forum, the generated VCARD and interface propose a field for the website and not the birthday of the contact.
In my opinion this is much better in order to use the plugin to generate QR Codes for business cards.

Only two files are necessary, one contains the plugin logic (QR code generation) in Python and the second (.inx file) is the plugin interface
for inkscape.

The repo can be reached on [github](https://github.com/anfe67/InkscapeQRVCard).
