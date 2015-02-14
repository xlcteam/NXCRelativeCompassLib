NXCRelativeCompassLib
=====================

NXC Library for relative compass

## Usage

Firstly, you need to set up port of the compass
i.e. `NRC_set_compass_port(IN_1);`

Rotate robot to the relative north and run following
`NRC_set_north();`

Then you are able to call method which tells you current angle from relative norht
`int angle = NRC_get_angle();`


## Licence
Licenced under the BSD License.

(c) 2013-2015, XLC Team
