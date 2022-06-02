# s-whatsend
This package is used to provide a python interface for interacting with WhatsAPP Web to send multiple massage to multiple user provided by the user  in queue(Excel). It is based on the official Whatsapp Web Browser Application and uses Selenium browser automation to communicate with Whatsapp Web.


# This python script can be used for whatsapp marketing.

# Important Points:-
1> [comments this line if want to define message in excel file (Recipients data.xlsx) line (22)]

url = 'https://web.whatsapp.com/send?phone=' + "+91"+str(excel_data['Contact'][count]) + '&text=' + Message

[and uncomments line (23)]

#url = 'https://web.whatsapp.com/send?phone=' + "+91"+str(excel_data['Contact'][count]) + '&text=' + excel_data['Message'][0]


2> [add mobile numbers numbers list in Recipients data.xlsx]

# how to run this script

Install  pandas, selenium, webdriver & chrome driver latest in same folder,
Run command/ python3 s-whatsend.py
while running this code it will start whatsapp-web & waiting for next step which is scanning Qr-Code.
user has to scan Qr-Code of whatsapp-web and then 
hit enter in python.
