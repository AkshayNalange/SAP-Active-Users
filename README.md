# SAP-Active-Users
ABAP Program to get active users list 


This code calls the function TH_USER_LIST, which returns a list of all SAP users in the system (stored in the internal table lt_susers). The internal table has the structure SUSER, which contains information about each user, such as their user name (bname) and telephone number (tel1_num).

The code then loops through the internal table and writes the user name and telephone number for each user. You can modify this code to include additional information or to filter the list of users based on your needs.

Keep in mind that this code will only work if you have the necessary authorization to access the user list. You may need to request additional permissions from your SAP administrator if you do not have access to this information.
