# CarND-Controls-PID
Self-Driving Car Engineer Nanodegree Program

---

## PID parameters

The PID is tuned manually. We first start with tuning P until the car moves in an oscilating way and tune D for the car to arrive smoothly to minimise CTE. Then, an bias is added in order to tune the I term.

The final parameters are  Kp = 0.1 , Ki = 0.001, Kd = 1.5.

## Effect of P, I, D

With P term, as the car is only correctly itself according to the error, the veichle oscillate heavily similar to damping.

With PD, the car is able to slow down its correction and thus arrive smoothly to the desirsed point, however it unable to correct itself from contant error that could be arised due to friction or steady state error

With the addition of I term, the car is able to correct its steadys state error accumulated from the past.
