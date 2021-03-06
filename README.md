# FTC-config-files

<html xmlns="http://www.w3.org/1999/xhtml">
  <head></head>
  <body>
    <table width="100%" cellspacing="0" cellpadding="3" border="1" summary="">
      <tbody>
        <tr bgcolor="F05A28">
          <th align="left" colspan="3"><font size="+2" color="#FFFFFF"><b>REV Robotics Electronics</b></font></th>
        </tr>
        <tr bgcolor="#F05A28">
          <th align="left" colspan="3"><font size="+2" color="#FFFFFF"><b>Embedded Devices</b></font></th>
        </tr>
        <tr bgcolor="#FFFFFF">
          <td width="20%"><b>Lynx Embedded IMU</b></td>
          <td><code>&lt;LynxEmbeddedIMU name="imu" port="0" bus="0" /&gt;</code></td>
          <td>A <code>LynxEmbeddedIMU</code> is an Inertial Measurement Unit, which aids the robot in navigation</td>
        </tr>
        <tr bgcolor="#F05A28">
          <th align="left" colspan="3"><font size="+2" color="#FFFFFF"><b>Analog Input Devices</b></font></th>
        </tr>
        <tr bgcolor="#F05A28">
          <th align="left" colspan="3"><font size="+2" color="#FFFFFF"><b>Digital Devices</b></font></th>
        </tr>
        <tr bgcolor="#F05A28">
          <th align="left" colspan="3"><font size="+2" color="#FFFFFF"><b>I2C Bus 0-3</b></font></th>
        </tr>
        <tr bgcolor="#F05A28">
          <th align="left" colspan="3"><font size="+2" color="#FFFFFF"><b>Motors</b></font></th>
        </tr>
        <tr bgcolor="#FFFFFF">
          <td width="20%"><b>NeveRest 20 Gearmotor</b></td>
          <td width="%20"><code>&lt;NeveRest20Gearmotor name="name" port="" /&gt;</code></td>
          <td>A <code>NeveRest20Gearmotor</code> is a DC motor with a 20:1 gear ratio</td>
        </tr>
        <tr bgcolor="#FFFFFF">
          <td width="20%"><b>NeveRest 3.7 v1 Gearmotor</b></td>
          <td width="%20"><code>&lt;NeveRest3.7v1Gearmotor name="name" port="" /&gt;</code></td>
          <td>A <code>NeveRest3.7v1Gearmotor</code> is a DC motor with a 3.7:1 gear ratio</td>
        </tr>
        <tr bgcolor="#FFFFFF">
          <td width="20%"><b>NeveRest 40 Gearmotor</b></td>
          <td width="%20"><code>&lt;NeveRest40Gearmotor name="name" port="" /&gt;</code></td>
          <td>A <code>NeveRest40Gearmotor</code> is a DC motor with a 40:1 gear ratio</td>
        </tr>
        <tr bgcolor="#FFFFFF">
          <td width="20%"><b>NeveRest 60 Gearmotor</b></td>
          <td width="%20"><code>&lt;NeveRest60Gearmotor name="name" port="" /&gt;</code></td>
          <td>A <code>NeveRest60Gearmotor</code> is a DC motor with a 60:1 gear ratio</td>
        </tr>
        <tr bgcolor="#F05A28">
          <th align="left" colspan="3"><font size="+2" color="#FFFFFF"><b>PWM Devices</b></font></th>
        </tr>
        <tr bgcolor="#F05A28">
          <th align="left" colspan="3"><font size="+2" color="#FFFFFF"><b>Servos</b></font></th>
        </tr>
        <tr bgcolor="#FFFFFF">
          <td width="20%"><b>Continuous Rotation Servo</b></td>
          <td width="%20"><code>&lt;ContinuousRotationServo name="name" port="" /&gt;</code></td>
          <td>A <code>ContinuousRotationServo</code>provides rotational movement, usually slower, but not in a fixed range</td>
        </tr>
        <tr bgcolor="#FFFFFF">
          <td width="20%"><b>Servo</b></td>
          <td width="%20"><code>&lt;Servo name="name" port="" /&gt;</code></td>
          <td>A <code>Servo</code> provides rotational movement, usually slower and in a fixed range</td>
        </tr>
      </tbody>
    </table>
  </body>
</html>

<html xmlns="http://www.w3.org/1999/xhtml">
  <head></head>
  <body>
    <table width="100%" cellspacing="0" cellpadding="3" border="1" summary="">
      <tbody>
        <tr bgcolor="#4999FF">
          <th align="left" colspan="3"><font size="+2" color="#FFFFFF"><b>Old Modern Robotics Electronics</b></font></th>
        </tr>
        <tr bgcolor="#4999FF">
          <th align="left" colspan="3"><font size="+2" color="#FFFFFF"><b>Modules</b></font></th>
        </tr>
        <tr bgcolor="#FFFFFF">
          <td width="20%"><b>Device Interface Module</b></td>
          <td width="%20"><code>&lt;DeviceInterfaceModule name="name" serialNumber="########"&gt;&lt;/DeviceInterfaceModule&gt;</code></td>
          <td>A <code>DeviceInterfaceModule</code> connects to sensors and other external electronics</td>
        </tr>
        <tr bgcolor="#FFFFFF">
          <td width="20%"><b>Legacy Module</b></td>
          <td></td>
          <td>A <code>LegacyModule</code> connects to the old HiTechnic modules and LEGO Mindstorms sensors</td>
        </tr>
        <tr bgcolor="#FFFFFF">
          <td width="20%"><b>Motor Controller</b></td>
          <td width="%20"><code>&lt;MotorController name="name" serialNumber="########"&gt;&lt;/MotorController&gt;</code></td>
          <td>A <code>MotorController</code> controls up to two DC motors</td>
        </tr>
        <tr bgcolor="#FFFFFF">
          <td width="20%"><b>Servo Controller</b></td>
          <td width="%20"><code>&lt;ServoController name="name" serialNumber="########"&gt;&lt;/ServoController&gt;</code></td>
          <td>A <code>ServoController</code> controls up to six servos</td>
        </tr>
        <tr bgcolor="#4999FF">
          <th align="left" colspan="3"><font size="+2" color="#FFFFFF"><b>Device Interface Module</b></font></th>
        </tr>
        <tr bgcolor="#FFFFFF">
          <td width="20%"><b>Color Sensor</b></td>
          <td width="%20"><code>&lt;ColorSensor name="name" port="" /&gt;</code></td>
          <td>A <code>ColorSensor</code> distinguishes between colors</td>
        </tr>
        <tr bgcolor="#FFFFFF">
          <td width="20%"><b>Gyro</b></td>
          <td width="%20"><code>&lt;Gyro name="name" port="" /&gt;</code></td>
          <td>A <code>Gyro</code> provides rotation feedback</td>
        </tr>
        <tr bgcolor="#FFFFFF">
          <td width="20%"><b>I2C Device</b></td>
          <td width="%20"><code>&lt;I2cDevice name="name" port="" /&gt;</code></td>
          <td>An <code>I2cDevice</code> communicates with the DIM via I2C</td>
        </tr>
        <tr bgcolor="#FFFFFF">
          <td width="20%"><b>IR Seeker V3</b></td>
          <td width="%20"><code>&lt;IRSeekerV3 name="name" port="" /&gt;</code></td>
          <td>An <code>IRSeekerV3</code> provides data about received IR signals</td>
        </tr>
        <tr bgcolor="#FFFFFF">
          <td width="20%"><b>Optical Distance Sensor</b></td>
          <td width="%20"><code>&lt;OpticalDistanceSensor name="name" port="" /&gt;</code></td>
          <td>An <code>OpticalDistanceSensor</code> measures distance or how dark or light a surface is</td>
        </tr>
        <tr bgcolor="#FFFFFF">
          <td width="20%"><b>Touch Sensor</b></td>
          <td width="%20"><code>&lt;TouchSensor name="name" port="" /&gt;</code></td>
          <td>A <code>TouchSensor</code> senses whether a momentary switch is pressed or not pressed</td>
        </tr>
        <tr bgcolor="#4999FF">
          <th align="left" colspan="3"><font size="+2" color="#FFFFFF"><b>Motor Controller</b></font></th>
        </tr>
        <tr bgcolor="#FFFFFF">
          <td width="20%"><b>Motor</b></td>
          <td width="%20"><code>&lt;Motor name="name" port="" /&gt;</code></td>
          <td>A <code>Motor</code> provides rotational movement</td>
        </tr><tr bgcolor="#4999FF">
          <th align="left" colspan="3"><font size="+2" color="#FFFFFF"><b>Servo Controller</b></font></th>
        </tr>
        <tr bgcolor="#FFFFFF">
          <td width="20%"><b>Servo</b></td>
          <td width="%20"><code>&lt;Servo name="name" port="" /&gt;</code></td>
          <td>A <code>Servo</code> provides rotational movement, usually slower and in a fixed range</td>
        </tr>
      </tbody>
    </table>
  </body>
</html>
