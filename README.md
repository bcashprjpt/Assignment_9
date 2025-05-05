# Assignment_9
#
#
# @@ assignmen9_forms:
#  @ Setting.py:-
	* Here i have placed 3 app in install app 'forms_app','crispy_forms','crispy_bootstrap4'
# @@ forms_app
# #Templates:
#  @ index1.html:-
	* Here i have used form and a submit button and placed extra button to move to the bootstrap page
	* and place a click function on the go to bootstrap button
#  @ index2.html:-
	* Here i have loaded the crispy_forms_tags in a form any apply a filetr by using the |crispy_bootstrap4
	* and placed a bootstrap button 
#  @ dispaly_user_info.html:-
	* Here i have display the user detail information when user click on the submit button from the index1.html page
#
# #models.py:	
	 * Here i have created a class of userDetail which used to assign the first name, last name, email, address.
# #form.py:
	* Here i have created a class of UserDetailForm by importing the UserDetail model storig all the fields data
# #views.py:	
# 	@ index1():
		* This method is used to render to the index1.html page
# 	@ index2();
		* This method is used to render to the index2.html page
# 	@ user_info();
		* This method is used to collect all the data from the forms and store in the session 
# 	@ dispaly_info():
		* This method is used to get the session request and render the data to the dispaly_user_info.html page 
		
