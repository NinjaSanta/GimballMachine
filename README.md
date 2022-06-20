# GimballMachine
A Arduino and VHDL Basys3 board based self-stabilizing platform with 3 servo motors and a MPU6050 gyro sensor

Arduino is used to get data from the MPU6050 gyro sensor using I2C, converts it into a series of analogus signals and sends it to BASYS3 board. Using VHDL, the data coming from the arduino board is converted into angle and using PWM, the amount of rotation necessary is calculated and outputted to the three MG996R servo motors, each one controlling rotation on an axis.
