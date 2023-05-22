# Vazifa1
# lugat = {"boolean":"mantiqiy qiymat", "float":"o'nlik son", "for":"biror amalni qayta-qayta bajarish tsikli", "if":"shartlarni tekshirish operatori", "integer":"butun son"}
#
# for k,q in lugat.items():
#     print(f"{k} - {q}")
#                                     2-vazifa
# davlatlar = {"Italya":"\t - Rim", "O'zbekiston":"- Toshkent", "AQSH":"\t\t - Washington DC", "Tojikiston":" - Dushanbe", "Rossia":"\t - Moskva"}
#
# for k,q in davlatlar.items():
#     print(f'{k}  {q}')
#                                        3-vazifa

davlatlar = {"Italya":"Rim", "O'zbekiston":"Toshkent", "AQSH":"Washington DC", "Tojikiston":"Dushanbe", "Rossia":"Moskva"}
for k, q in davlatlar.items():
    pass
davlat = input("Biron-bir davlat nomini kiriting\n>>>")
if davlat == k:
    print(f"{k} davlatining poytaxti {q}")
else:
    print(f"Bizda {davlat} haqida ma'lumot yo'q")
