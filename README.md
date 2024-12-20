menu={
    'pizza':40,
    'pasta':50,
    'burger':60,
    'salad':70,
    'coffee':80,
}


print("welcome to python restuarent")
print("pizza: rs40 /n pasta: rs50 /n burgur: rs 60 /n salad: rs70 /n coffee: rs 80")


order_total=0
item_1 =input("enter the name of item you want to order =")
if item_1 in menu:
    order_total += menu[item_1]
    print(f"your item{item_1}has been added to your order")

else:
    print(f"ordered item{item_1} is not avaialable yet!")

    another_order= input("do you want to add another item?(yes/no)")

