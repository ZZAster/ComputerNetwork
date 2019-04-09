# Assignment 4

---
## 1. 课后习题任选五道
**P2.**<br>
a. No, we can only transmit one packet at a time over a shared bus.<br>
b. No, as discussed in the text, only one memory read/write can be done at a time over the shared system bus. <br>
c. No, in this case the two packets would have to be sent over the same output bus at the same time, which is not possible.<br> 
<br>
**P3.**<br>
a. (n-1)D<br>
b. (n-1)D<br>
c. 0<br>
<br>
**P8.**<br>
a. 223.1.17.0/26<br>
b. 223.1.17.128/25<br>
c. 223.1.17.192/28<br>
<br>
**P11.**<br>
  Any IP address in range 128.119.40.128 to 128.119.40.191.<br>
Four equal size subnets: 128.119.40.64/28, 128.119.40.80/28, 128.119.40.96/28, 128.119.40.112/28.<br>
<br>
**P14.**<br>
  The maximum size of data field in each fragment is 680. Thus the number of required fragments is (2400-20)/680=4.<br>
Each fragment will have Identification number 422. Each fragment except the last one will be of size 700 bytes.<br>
The last datagram will be of size 360 bytes. The offsets of the 4 fragments will be 0, 85, 170, 255. Each of the<br>
first 3 fragments will have flag=1; the last fragment will have flag=0.<br>