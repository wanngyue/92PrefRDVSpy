# 92PrefRDVSpy

This is a python script monitoring prefecture92 (Hauts-De-Seine) titre-de-séjour booking page, by default, it checks if any place is availabe every 30s and send an e-mail.

User needs to configure themselves the followling fields in the script:

	* smtp_server = "smtp.gmail.com"
	* port = 587
	* sender_email = "xxx@gmail.com"
	* password = ""
	* server.sendmail(sender_email, "xxx@gmail.com", msg)
  
Wish you good luck!
