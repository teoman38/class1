# class1
#Class
class Good():

    price = ""
    amount = ""

    def __init__(self, price, amount):
        self.price = price
        self.amount = amount

yumos = Good(75, 9)
limonata = Good(21.5, 12)
mehmet = Good(1, 1)
okan = Good(2, 1)

print("Yumoş fiyatı :" + str(yumos.price))
print("Yumoş miktarı :" + str(yumos.amount))

print("Limonat fiyatı :" + str(limonata.price))
print("Limonata miktarı :" + str(limonata.amount))

print("Mehmet in fiyatı :" + str(mehmet.price))
print("Mehmet in miktarı :" + str(mehmet.amount))

print("Okan ın fiyatı :" + str(okan.price))
print("Okan ın miktarı :" + str(okan.amount))
