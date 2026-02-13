## **Uploading**
Drag .pio/build/STM32G0B1RE\_btt/firmware.bin to sd card


## **Bed** (PIDTEMPBED): 

`M303 E-1 C8 S90`

``` log
Recv: //action:notification PID tuning done
Recv: #define DEFAULT_BED_KP 117.44
Recv: #define DEFAULT_BED_KI 19.07
Recv: #define DEFAULT_BED_KD 482.30
Recv: ok
```

## **HotEnd** (PID_PARAMS_PER_HOTEND): 

`M303 E0 S205 C10`

``` log
Recv: //action:notification PID tuning done
Recv: #define DEFAULT_KP 18.36
Recv: #define DEFAULT_KI 1.87
Recv: #define DEFAULT_KD 45.16
```

## **Old Bed:**
``` log
Recv: PID Autotune finished! Put the last Kp, Ki and Kd constants from below into Configuration.h
Recv: //action:notification PID tuning done
Recv: #define DEFAULT\_bedKp 233.73
Recv: #define DEFAULT\_bedKi 45.65
Recv: #define DEFAULT\_bedKd 797.79
```




