# Swastik is basically, a Health & Nutrition Monitoring Service Application for the cause of Women and child nutrition,
But it can be used for used for various other purposes.<br />

This is Swastik API and routes, that handles all the connections to the database.<br />


<pre>
RESTful Routing:

A)     Functioning of the Route                                          Request Type                    URL

1.To Login the admin portal user into swastik Interface                  GET Request         https://domain_name/Login

2.To Register the user onto the database                                 GET Request         https://domain_name/Signup

3.To Logout the user from the current session                            GET Request         https://domain_name/Logout

4.To Render the register parent form                                     GET Request         https://domain_name/Register/parent

5.To Register the parent.                                                POST Request        https://domain_name/Register/parent

6.To Render the register child form                                      GET Request         https://domain_name/Register/child

7.To Register the child.                                                 POST Request        https://domain_name/Register/child

8.To get the details of the parent with the aadhar no.                   POST Request        https://domain_name/Client/parent

9.To get the details of the children of the parent present.              GET Request         https://domain_name/Client/parent/:aadharno/children

10. To update the details of any children with ID                        PUT Request         https://domain_name/Client/children/:child_id/update

11. To send any type of message to an array of numbers                   POST Request        https://domain_name/Message/sendtoall

12. Get phonenos of parents whose ward vaccination date is close         GET Request        https://domain_name/Message/phonenos

13. Get emails of parents whose ward vaccination date is close           GET Request        https://domain_name/Message/email

14. Sample protected route for auth verification                         GET Request        https://domain_name/Protected

15. Get the count of patients of all disease categorised as a map.       GET Request        https://domain_name/statistics/patients_count_wrt_disease

16. Get the count of children categorised on basis of pincode            GET Request        https://domain_name/statistics/children/pincode

17. Get the JSON array of children categorised on basis of pincode       GET Request        https://domain_name/statistics/children/pincode/:pincode

18. Allows messaging to all parents whose ward live in a unique pincode  GET Request        https://domain_name/message/phonenos/all_parents/:pincode

19. Allows to register complaint, accepts email and complain as feilds   POST Request       https://domain_name/complain/log_complaint

20. Returns the count of male and female parents as well as children     GET Request        https://domain_name/search/count_parents_children

So, These 20 routes can handle any operation from or on the database.

This is not an open source API, and it's © copyright are reserved solely with the creator.  
</pre>⌢栠捡㕫〮獟牥敶≲ഠ�