This project implements a digital audio console on FPGA using the Digilent Pmod I2S2 and Pmod JSTK2 modules.
The system samples and processes audio signals via the I2S protocol, while the joystick controls volume, balance, mute, and filtering effects through SPI and UART communication.
Several hardware modules — including a moving average filter, LFO (Low Frequency Oscillator), and LED controllers — were integrated to manage real-time audio manipulation and visualization on the Basys3 board.
