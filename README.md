# Ender 3-Pro, its firmware, and operating configuration

This is the latest operating configuration for my [Creality Ender 3 Pro 220x220x250MM](https://www.amazon.com/gp/product/B07K3SZBHJ/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1) purchased Dec 11, 2020.

```text
Mainboard version:  4.2.2
Klipper version:    0.11.0-40
```

### Upgraded Part List
Listed by order of most recently purchased. Items ~~striked~~ are no longer being used.

1. [Sprite Direct Drive Extruder Pro Kit with 80N Stepper Motor](https://www.amazon.com/gp/product/B09WR8CJZD/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)
1. [Ender 3 V2 Enclosure](https://www.amazon.com/gp/product/B08FFHSP9M/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)
2. [~~Capricorn Teflon Tube PTFE Bowden Tubing~~](https://www.amazon.com/gp/product/B09N789L23/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)
3. [4Pcs Metal Leveling Nuts and Springs](https://www.amazon.com/gp/product/B082PC59BP/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)
4. [CR-Touch](https://www.amazon.com/gp/product/B0979F7RWN/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)
5. [~~All Metal Extruder Feeder, Capricorn Bowden Tubing, Pneumatic Couplers, Bed-Level Springs~~](https://www.amazon.com/gp/product/B081DN6RM2/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)
6. [Dual Z-axis](https://www.amazon.com/gp/product/B09N8QQDSP/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)
7. [Tempered Glass Plate 235x235](https://www.amazon.com/gp/product/B07DS2LZF1/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)

### Settings at a glance

**Sprite direct drive extruder and CR-Touch offsets:**
```cnf
[bltouch]
x_offset: -34.5
y_offset: -41.5
z_offset: 0.980
```

**Bed Mesh:**
```cnf
[bed_mesh]
speed: 150
mesh_min: 27, 41.5
mesh_max: 198, 200
probe_count: 5, 3
```

**Bed-level screws:**
```cnf
[screws_tilt_adjust]
screw_thread: CW-M4
screw1_name: Back left
screw1: 60, 245
screw2_name: Front left
screw2: 60, 84
screw3_name: Front right
screw3: 230, 84
screw4_name: Back right
screw4: 230, 245
```
