# QRimgtest

test repo for embedding logo into QR image and color, format customization

## how to run

You must have rsvg-convert installed 

```sudo apt-get rsvg-convert```

Requires at least python3.8

```
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python3 test_template.py 
```

- change colors in test_template.py

- EDIT YOUR SVG TEMPLATE FILE to refer to lnurl_file and qr_code, idnumber, expires and sats
with {{ }}, For example: 

```<img 
     href={{lnurl_file}}
