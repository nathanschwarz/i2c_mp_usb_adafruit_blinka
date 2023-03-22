# i2c_mp_usb_adafruit_blinka
porting the I2C to USB library by EmbedME for the pyI2C_MP_USB to adafruit_blinka library

# usage
an simple example with the adafruit_vl53l0x sensor library
```
from blinka_mp_i2c import BlinkaMpI2C
i2c = BlinkaMpI2C()
sensor = adafruit_vl53l0x.VL53L0X(self.i2c, 0x29)
# do stuff with your sensor
```