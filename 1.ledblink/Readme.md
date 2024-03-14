
1. Select initialise peripherals by itself to no
2. Make FreeRTOS enabled in middleware section
3. Ensure pre-emption is enabled in kernel settings
4. Add a new task in task and queues
5. enable newlib reentrant in advanced settings.
6. change timebase source from systick to any of the timer

After that is done you just create one more new task(as everything works through tasks in FREERTOS) and just put toggle leds and different delays in both tasks.
