# IS-420-Assignment-4
# Problem 1: Please create a PL/SQL function that given a topic ID, print out total number of child topics under that topic (i.e., parent ID = input topic ID). Please also call this function with input 1 and 5.   
# Problem 2: Please create a PL/SQL procedure which assigns a ticket to a support staff. The procedure takes a ticket ID and a staff ID as input and does the following steps. 
# 1) it checks whether there is a ticket with the given ticket ID. If not print a message invalid ticket ID and stops. 
# 2) it then checks whether a support staff has the input staff ID. If not print a message invalid staff ID and stop.
# 3) it assigns the ticket to the support staff (update the sid in ticket table), update status to 2, and insert a row into ticket_detail with appropriate tkid, sid, tdtime as current time (systimestamp), and content as 'ticket assigned to support staff'.
