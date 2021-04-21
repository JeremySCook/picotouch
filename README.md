# picotouch

Tiny capsense touch MIDI keyboard from a Raspberry Pi Pico

<img width=700 src="./docs/picotouch_top1.png"/>
<img width=700 src="./docs/picotouch_top2.png"/>


# Materials needed
- 1 - picotouch PCB (oshpark link soon)
- 1 - Raspberry Pi Pico
- 22 - 1M ohm 0805 SMD resistors


# Installation [tbd]

- Install CircuitPython
  Downlaod UF2 https://circuitpython.org/board/raspberry_pi_pico/

- Install Needed Libraries
  ```
  circup install adafruit_midi adafruit_debouncer
  ```

- Copy over `code.py`
  ```
  cp picotouch/firmare/picotouch_code.py /Volumes/CIRCUITPY/code.py
  ```
