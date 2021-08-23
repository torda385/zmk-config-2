```
west build \
--pristine \
-d build/left \
-b nice_nano \
-- \
-DSHIELD=ferris_sweep_v2_left \
-DZMK_CONFIG=${HOME}/dev/zmk-config/config
```
```
cp $(pwd)/build/left/zephyr/zmk.uf2 /Volumes/NICENANO
```


```
west build \
--pristine \
-d build/right \
-b nice_nano \
-- \
-DSHIELD=ferris_sweep_v2_right \
-DZMK_CONFIG=${HOME}/dev/zmk-config/config
```
```
cp $(pwd)/build/left/zephyr/zmk.uf2 /Volumes/NICENANO
```
