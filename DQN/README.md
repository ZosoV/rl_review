## MushroomRL version

* Install the anaconda environment

.. code:: shell

    conda env create -f environment.yml

* Install gym dependencies

.. code:: shell

    sudo apt -y install libsdl-image1.2-dev libsdl-mixer1.2-dev libsdl-ttf2.0-dev \
                     libsdl1.2-dev libsmpeg-dev libportmidi-dev ffmpeg libswscale-dev \
                     libavformat-dev libavcodec-dev swig

* Download and install ROMs permissions

.. code:: shell

    curl -o Roms.rar http://www.atarimania.com/roms/Roms.rar
    unrar x Roms.rar
    python -m atari_py.import_roms .
