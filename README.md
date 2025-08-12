cümle=input("Bir Cümle Yaz:")

kelimeler=cümle.split()

kelime_sayısı=len(kelimeler)

harf_sayısı=0

for karakter in cümle:

    if karakter !=" ":

        harf_sayısı+=1

print("Kelime Sayısı:",kelime_sayısı)


print("Harf sayısı (boşluklar hariç:):",harf_sayısı)

