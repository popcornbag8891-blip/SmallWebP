# Security

## Reporting a vulnerability

Please **don't open a public issue** for a security problem. Report it privately through GitHub instead:

1. Go to the [Security tab](https://github.com/popcornbag8891-blip/SmallWebP/security) of this repository.
2. Choose **Report a vulnerability**.

Include what you found, the steps to reproduce it, and the browser and device you used. If a specific file triggers it, describe the file rather than attaching it unless asked.

## What is in scope

- Anything that lets a page or file send image data off the device.
- A file that gets past file validation and causes harm when opened.
- Cross-site scripting or Content Security Policy bypasses on smallwebp.io.

## What file validation does and doesn't do

smallwebp.io checks every file before opening it: the real file type, the file size and dimensions, and known script patterns or appended archives and programs. This is validation, not a virus scanner. It can't guarantee that any file is safe, and it doesn't replace antivirus software.
