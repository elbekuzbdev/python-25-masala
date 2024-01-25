#  S.strip() funksiya satrning boshi va oxrida bo'shliq bo'lsa olib tashlaydi
a=" Dastur  "
print(a.strip())
# S.lower() funksiya satrdagi barcha so'zlarni kichik harflar bilan yozadi
b='Markaziy Osiyo'
print(b.lower())
#S.upper() funksiya satrdagi barcha so'zlarni katta harflar bilan yozadi:
c="Markaziy Osiyo"
print(c.upper())
# S.replace() funksiyasisatrdagi birso'z yoki harfni boshqasi bilan almashtiradi:
d="Bor"
e="Markaziy Osiyo"
print(d.replace("r", "y"))
print(e.replace("Markaziy", "O'rta"))
# S.split() funksiyasi  satrni ko'rsatilgan belgi bo'yicha qismlarga bo'lib chiqadi. Masalan, vergul ko'rsatilsa satrdagi har bir vergulgacha bo'lgan so'z yoki harfni alohida qism dwb oladi. yoki probrl(bo'shliq) ko'rsatilsa har bir probrlgacha bo'lgan qismi ajraladi. 
f="Python bilan ishlash qiziqarli"
print(a.split(" "))
