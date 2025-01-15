![image-20201025143332274](C:\Users\10161\AppData\Roaming\Typora\typora-user-images\image-20201025143332274.png)

http://stm32f4-discovery.net/2014/09/library-33-pwm-stm32f4xx/

- Not all timers are available on all STM32F4xx devices
- Not all timers works with same tick frequency
- All timers have **16bit** prescaler
- **TIM6** and **TIM7** don’t have PWM feature, they are only basic timers
- **TIM2** and **TIM5** are 32bit timers
- **TIM9** and **TIM12** have two PWM channels
- **TIM10**, **TIM11**, **TIM13** and **TIM14** have only one PWM channel
- All channels at one timer have the same PWM frequency!

# STM32F4 NVIC or Nested Vector Interrupt Controller 

# STM32F4 External interrupts tutorial

External interrupts tutorial