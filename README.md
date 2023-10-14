# virus-bintang
#!bin/usr/bash
#copyraight by Bintang

#variabel
e=echo
s=sleep
v=https
z=bit.ly
k=3ild93L

# pembersih texs
c=clear
$c # pembersih

# tampilan
$s 1
figlet   Link-Virus
$e "-e"
$s 1
$e "=================================================="
$e "  {•} AUTHOR : BINTANG"
$e "  {•} TEAM   : NDADAPAN"
$e "=================================================="

# Daftar menu
$s 1
echo "            <•> WELCOME USER TERMUX <•>"
echo "×××××××××××××××××××××××××××××××××××××××××××××××××"
echo "{1} link-Virus"
echo "{x} Keluar"
read -p " {•} pilih: " option ;
echo "×××××××××××××××××××××××××××××××××××××××××××××××××"

#data base
if [[ $option == "1" ]]
then
    echo
    echo "sabar menunggu....."
    sleep 5
    $e "        ↓↓↓↓"
    $e $v://$z/$k
    echo "++++++++++++++++++++++++++++++++++++++++++++"
else 
    echo "babay sayang....."
fi
