# fixpermission-cpanel
                         Install

cd ~
rm -rf fixperm-1.0*
wget -O fixperm-1.0.tar.gz "https://github.com/ninzahost/fixpermission-cpanel/raw/main/fixperm-1.0.tar.gz"
tar -xvf fixperm-1.0.tar.gz
cd fixperm-1.0
sh setup -install
cd ..



                  Uninstall


cd ~
rm -rf fixperm-1.0*
wget -O fixperm-1.0.tar.gz "https://github.com/ninzahost/fixpermission-cpanel/raw/main/fixperm-1.0.tar.gz"
tar -xvf fixperm-1.0.tar.gz
cd fixperm-1.0
sh setup -uninstall
cd ..
