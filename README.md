# Tugas-1-Praktikum
# Nama : Muhammad farid andika putra
# NIM :  2309116101
print("======================================================================")
input("Nama: ")
input("NIM: ")
print("======================================================================")
print("Silahkan pilih mata uang yang ingin anda konversikan")
print("1. USD")
print("2. Yen")
print("3. Ringgit Malaysia")
print("======================================================================")
pilihan = int(input("Masukkan pilihan anda (1/2/3): "))

if pilihan == 1:
    def idrtousd(rupiah_usd):
        return(rupiah_usd/15357)
    rp_usd = int(input("masukkan nominal uangmu dalam rupiah: "))
    uangusd = idrtousd(rp_usd)
    print("Uang DOLLAR anda sebesar: ""$", uangusd)
elif pilihan == 2:
    def idrtoyen(rupiah_yen):
        return(rupiah_yen/107)
    rp_yen = int(input("masukkan nominal uang anda dalam rupiah: "))
    uangyen = idrtoyen(rp_yen)
    print("Uang YEN anda sebesar: " "¥", uangyen)
elif pilihan == 3:
    def idrtoringgit(rupiah_ringgit):
        return(rupiah_ringgit/3.273)
    rp_ringgit = int(input("masukkan nominal uang anda dalam rupiah: "))
    uangringgit = idrtoringgit(rp_ringgit)
    print("Uang RINGGIT anda sebesar: " "RM", uangringgit)

![foto almet andika](https://github.com/Andptra20/Tugas-1-Praktikum/assets/146108385/ae516edc-e571-4a1a-931f-cdfd03bda464)

![Untitled Diagram drawio](https://github.com/Andptra20/Tugas-1-Praktikum/assets/146108385/25a1f556-a15c-4da5-a6e4-5d2c86c52cfb)
![Uploading Screenshot 2023-09-26 220728.png…]()
![Uploading Screenshot (1).png…]()

