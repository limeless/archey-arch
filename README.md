# Archey with Geo/IP.
An archey script for Arch linux with Geo/IP supported. 

> I'm really bad at writing readme so beer with me.
> will try to add more in the future.

```sh
               +                
               #                
              ###               
             #####              User: limeless
             ######             Hostname: FuseStation
            ; #####;            Distro: Arch Linux
           +##.#####            Kernel: 4.19.16-1-MANJARO
          +##########           Uptime: 4 days, 19:55
         #############;         Window Manager: i3
        ###############+        Desktop Environment: 
       #######   #######        Shell: /usr/bin/fish
     .######;     ;###;`".      Terminal: xterm-termite
    .#######;     ;#####.       Packages: 1038
    #########.   .########`     CPU: Intel(R) Core(TM) i5-2415M CPU @ 2.30GHz
   ######'           '######    RAM: 942 MB / 7888 MB
  ;####                 ####;   Disk: 14GB / 226GB
  ##'                     '##   City: US, Irvine 
 #'                         `#  IP: 111.222.333.444

```
## Download
The latest stable version is [0.3.0](https://github.com/limeless/archey-arch/archive/0.3.0.tar.gz)

## Installation
**NOT RECOMMEND**

Simply replace the oringinal archey file.

```sh
$ which archey
/usr/bin/archey
$ sudo cp src/archey /usr/bin/archey
```

**RECOMMEND**

Copy `src/archey` to `/usr/bin/` with different name.

```sh
$ which archey
/usr/bin/archey
$ sudo cp src/archey /usr/bin/archey-ip
```
to run it, just simply use `archey-ip` instead of `archey`

## License
![GPLV3](https://www.gnu.org/graphics/gplv3-with-text-84x42.png)
This tool is protected by the [GNU General Public License v3](http://www.gnu.org/licenses/gpl-3.0.html).

Copyright [limeless](https://leburger.gitlab.io) 2019
