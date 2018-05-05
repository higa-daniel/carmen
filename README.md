# carmen
## Setup for PXC200AF device
References:
* Carmen For Linux (skip this step if you are not using FXVD4)
> http://www.arhungary.hu/doc/arh_fxvd4.pdf

> http://www.imagenation.com/dnpages/pxc_files.html#manuals

* OpenCV for Ubuntu:
> https://docs.opencv.org/3.4.1/d2/de6/tutorial_py_setup_in_ubuntu.html

* Tesseract for Ubuntu:
> https://www.howtoforge.com/tutorial/tesseract-ocr-installation-and-usage-on-ubuntu-16-04/

* Xawtv
> https://www.linuxtv.org/wiki/index.php/Xawtv
```sh
run chmod 664 /dev/video0
configure /etc/modprobe.d/bttv.conf
```
* mod_wsgi
> Install Carmen For Linux (skip this step if you are not using FXVD4)

> https://modwsgi.readthedocs.io/en/develop/

* Issues
-Placa vermelho não consegue ser lida.
-Blitz deve ler a placa inteira.
-Rodízio deve pegar apenas o último dígital.
