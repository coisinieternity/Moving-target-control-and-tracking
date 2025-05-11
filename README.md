# Moving-target-control-and-tracking
23年电赛E题
采用步进式PID做速度限制
用270度舵机，通过屏幕上的x，y点算出对应的云台角度，再计算出每个角度的pwm占空比，为准确要测云台水平角和云台与屏幕原点角度
主控用stm32f103c8t6，视觉采用openmv
