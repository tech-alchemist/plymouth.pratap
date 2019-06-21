#### **[Maharana Pratap](https://bit.ly/2FpjQ37)** 

#### A tribute via Plymouth (Boot Animation For Linux)

#### Installation

    $ cd /usr/share/plymouth/themes/
   
    $ sudo git clone https://github.com/tech-alchemist/plymouth.pratap.git pratap
    
    $ sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/pratap/pratap.plymouth 100
    
    $ sudo update-alternatives --config default.plymouth

& Type selection number of pratap & `Enter`

    $ sudo update-initramfs -u

Now reboot.

#### Removal
    $ sudo update-alternatives --remove default.plymouth /usr/share/plymouth/themes/pratap/pratap.plymouth
