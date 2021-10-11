### RACTF
## capture the flag event writeups

# Hash cracking


![This is image](https://user-images.githubusercontent.com/71208443/136779910-1951ad63-fe61-4cb4-be45-876f3e7df598.png)

hashtype-md5

hashcat -a 0 -m 0 hash.txt rockyou.txt

DO{phantomlover}

![This is image](https://user-images.githubusercontent.com/71208443/136780362-c2f52c74-28aa-4897-82f2-b094f4e343c4.png)

hashtype-sha128

hashcat -a 0 -m 100 hash.txt rockyou.txt

DO{fishchips}

![This is image](https://user-images.githubusercontent.com/71208443/136780698-0e06a221-535f-4209-8b1a-a5dd399a7fc5.png)


hashtype - sha512

hashcat -a 0 -m 1700 hash.txt rockyou.txt

DO{mommadobbins}

![image](https://user-images.githubusercontent.com/71208443/136780897-b3acef5d-a104-46f6-b347-20970095f386.png)


hashtype - ghost

hashcat -a 0 -m 6900 hash.txt rockyou.txt

DO{happyfamily}


![image](https://user-images.githubusercontent.com/71208443/136781045-9c6726ec-0b55-47b6-877b-e98a9285925b.png)


hashtype - bcrypt 

hashcat -a 0 -m 3200 hash.txt rockyou.txt


DO{cowabunga}

![image](https://user-images.githubusercontent.com/71208443/136781221-70ccd965-36fd-40cb-a288-5623c1b9a3fb.png)


hashtype-md5 crypt

hashcat -a 0 -m 500 hash.txt rockyou.txt


DO{scottiebanks}

![image](https://user-images.githubusercontent.com/71208443/136781350-e44fc1d8-82c6-482c-8db7-3964119fada1.png)

hashtype - sha512 crypt

hashcat -a 0 -m 1800 hash.txt rockyou.txt

DO{igetmoney}


# stegnography

![image](https://user-images.githubusercontent.com/71208443/136782681-76a27eb3-a98e-4260-b25c-8e17269869cc.png)

strings filename gives me base64 encoded string

base64 decode 

DO{C0nVeR510n_m4Dn355}


![image](https://user-images.githubusercontent.com/71208443/136782899-e4c6fcbe-dce2-4269-838c-1b031f63ae75.png)

strimgs filename gives the flag

echo "RE97VzNfYVIzX3RoM19DaDRtUDEwblN9" | base64 -d

DO{W3_aR3_th3_Ch4mP10nS} 

![image](https://user-images.githubusercontent.com/71208443/136783280-2fa5b5a5-54be-413c-9a1c-f20835bae000.png)

strings 

DO{H1d1nG_iN_Pl41n_SiGhT}


![image](https://user-images.githubusercontent.com/71208443/136783507-f5518fb0-1503-4ccf-9975-a3939a6a7b7f.png)

for this i  use stegsolve 

![image](https://user-images.githubusercontent.com/71208443/136784278-5777a41e-ea77-4bf2-9010-f98c6ab7d5a9.png)









