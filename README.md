# ADRC_AutoQuadrotor

#四旋翼
1、STM32F407 +MPU6050+AK8975+MS5611+US100+SPI_FLASH； 
2、姿态解算包含互补 DCM GD EKF 可修改宏定义选择；
3、加速度计和气压计还有超声波通过互补融合；
4、控制有PID/（TD+ PID），观测器设计还有一定问题没有实现，但时跟踪微分器已验证没有问题，可以实飞；
