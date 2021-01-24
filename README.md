# Earthquake-Detector-Location-Notifier
The  final  project  aims  to  design  a  tool  that  plays  a significant role during earthquakes. The tool will use one of the I2C sensors, an accelerometer, to  measure  the  acceleration  of  the  development  kit.  This measured  raw  data  will  be  computed  to  determine if  the movement  is  caused  by  an  earthquake.  If  the  movement  is caused by an earthquake, the tool will be triggered. Once the tool is triggered, the DAC speaker will produce noise  like  a  siren.  If  the  person  who  has  this  tool  is  trapped under the rubble,  the  siren  will  help  to locate a person more easily.Also, the trapped person will notneed to waste limited oxygen for screaming.On the other hand, once the tool is triggered, the computed data will be stored in QSPI flash like a black box of a plane. When  the  blue  button  is  pushed,  the  stored  data  will  be presented in the simulator with the help of UART. The stored data can be used for analytic purposes.

The  project  will  be implemented  on  the STM IoT  node  with a B-L475E-IOT01A1 discovery kit.
