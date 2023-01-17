# Test cases that have been prepared for the Login page of the testing fake online store:
[http://skleptest.pl/](http://skleptest.pl/) 


## Test case: Login page - Login page - Signing in with no data
The goal of the test is to check if it is possible to login without giving any data (email/username, password)

Previous conditions:
- Open the browser.

- Go to the login page of the online store: http://skleptest.pl/my-account/


| # | Description | Expected result |
| -------------------------------- |-------------------------------- |  -------------------------------- | 
| 1 | Do not type any data, click on the button 'Login' | The website gives the user an information that fields 'Username/e-mail address' and 'password' are required, the system does not sign in |

<br>
<br>

## Test case: Login page - Signing in with correct data (username & password)
The goal of the test is to check if it is possible to sign in when the user gives the existing username and correct password.

Previous conditions:
- It is needed to be registered and use existing email address and the password.

- Open the browser.

- Go to the login page of the online store: http://skleptest.pl/my-account/


| # | Description | Expected result |
| -------------------------------- |-------------------------------- |  -------------------------------- | 
| 1 | In the field 'email address' type the existing username that is registered | The user sees the username in the field |
| 2 | In the field 'password' type the correct password | The password is hidden but the user sees the security dots (their number is the number of the typed password's signs) |
| 3 | Click on the button 'Login' | The system signs the user in. The user is in the user panel |

<br>
<br>

## Test case: Login page - incorrect data (email & password)
The goal of the test is to check if it is possible to sign in when the user enters incorrect email and password.

Previous conditions:
- Open the browser.

- Go to the login page of the online store: http://skleptest.pl/my-account/


| # | Description | Expected result |
| -------------------------------- |-------------------------------- |  -------------------------------- | 
| 1 | In the field 'email address' type the an email address that is not registered | The user sees the email address in the field |
| 2 | In the field 'password' type the incorrect password  | The password is hidden but the user sees the security dots (their number is the number of the typed password's signs) |
| 3 | Click on the button 'Login' | The system does not let the user to log in. The system gives the information about incorrect email and password that has been entered |

<br>
<br>

## Test case: Login page - Incorrect email address
The goal of the test is to check if it is possible to sign in when the user enters incorrect email address

Previous conditions:
- It is needed to be registered and use existing password

- Open the browser

- Go to the login page of the online store: http://skleptest.pl/my-account/


| # | Description | Expected result |
| -------------------------------- |-------------------------------- |  -------------------------------- | 
| 1 | In the field 'email address' type the incorrect email address that is not registered in the data base | The user sees the email address in the field |
| 2 | In the field 'password' type the correct password | The password is hidden but the user sees the security dots (their number is the number of the typed password's signs) |
| 3 | Click on the button 'Login' | The system does not let the user to log in. The system gives the information about incorrect email or password that has been entered |

<br>
<br>

## Test case: Login page - Incorrect password
The goal of the test is to check if it is possible to sign in when the user enters incorrect password

Previous conditions:
- It is needed to be registered and use existing email address.

- Open the browser.

- Go to the login page of the online store: http://skleptest.pl/my-account/


| # | Description | Expected result |
| -------------------------------- |-------------------------------- |  -------------------------------- | 
| 1 | In the field 'email address' type the existing email address that is registered | The user sees the email address in the field |
| 2 | In the field 'password' type the incorrect password | The password is hidden but the user sees the security dots (their number is the number of the typed password's signs) |
| 3 | Click on the button 'Login' | The system does not let the user to log in. The system gives the information about incorrect email or password that has been entered |

<br>
<br>

## Test case: Login page - No password 
The goal of the test is to check if the application will let the user to log in if the user uses only the email address and no password.

Previous conditions:
- It is needed to have a registered account

- Open the browser

- Go to the login page of the online store: http://skleptest.pl/my-account/


| # | Description | Expected result |
| -------------------------------- |-------------------------------- |  -------------------------------- | 
| 1 | In the field 'email address' type the correct email address that is  registered in the data base - type it by using the uppercase letters | The user sees the email address in the field |
| 2 | Click on the button 'Login' | The system does not let the user to log in. The system gives the information about inccorect email and/or password that has been entered |

<br>
<br>

## Test case: Login page - Email address - Uppercase letters 
The goal of the test is to check if the application will let the user to log in, if the user uses uppercase letters in the email address.

Previous conditions:
- It is needed to have a registered account

- Open the browser

- Go to the login page of the online store: http://skleptest.pl/my-account/


| # | Description | Expected result |
| -------------------------------- |-------------------------------- |  -------------------------------- | 
| 1 | In the field 'email address' type the correct email address that is  registered in the data base - type it by using the uppercase letters | The user sees the email address in the field |
| 2 | In the field 'password' type the correct password | The password is hidden but the user sees the security dots (their number is the number of the typed password's signs) |
| 3 | Click on the button 'Login' | The system signs the user in. The user is in the user panel |

<br>
<br>

## Test case: Login page - Password - Uppercase letters 
The goal of the test is to check if the application will let the user to log in, if the user uses uppercase letters in the email address.

Previous conditions:
- It is needed to have a registered account

- The password that has been given needs to contain minimum 1 lowercase letter

- Open the browser

- Go to the login page of the online store: http://skleptest.pl/my-account/


| # | Description | Expected result |
| -------------------------------- |-------------------------------- |  -------------------------------- | 
| 1 | In the field 'email address' type the correct email address that is  registered in the data base | The user sees the email address in the field |
| 2 | In the field 'password' type the correct password using only uppercase letters | The password is hidden but the user sees the security dots (their number is the number of the typed password's signs) |
| 3 | Click on the button 'Login' | The system informs the user that the email address and/or password is incorrect |

<br>
<br>

## Test case: Login page - Remember me checkbox
The goal of the test is to check if marked checkbox 'Remember me' by signing in will keep the user to be logged in, in the future sessions.

Previous conditions:
- It is needed to be registered and use existing email address and the password.

- Open the browser.

- Go to the login page of the online store: http://skleptest.pl/my-account/


| # | Description | Expected result |
| -------------------------------- |-------------------------------- |  -------------------------------- | 
| 1 | In the field 'email address' type the existing email address that is registered | The user sees the email address in the field |
| 2 | In the field 'password' type the correct password | The password is hidden but the user sees the security dots (their number is the number of the typed password's signs) |
| 3 | Mark the checkbox 'Remember me' | There is a visible tick in the checkbox |
| 4 | Click on the button 'Login' | The system signs the user in. The user is in the user panel. |


<br>
<br>

## Test case: Remember me checkbox - incorrect data 
The goal of the test is to check if the application will remember incorrect user data by marking the checkbox 'Remember me' and trying to log in.

Previous conditions:
- Open the browser

- Go to the login page of the online store: http://skleptest.pl/my-account/


| # | Description | Expected result |
| -------------------------------- |-------------------------------- |  -------------------------------- | 
| 1 | In the field 'email address' type the incorrect email address that is not registered in the data base | The user sees the email address in the field |
| 2 | In the field 'password' type the incorrect password | The password is hidden but the user sees the security dots (their number is the number of the typed password's signs) |
| 3 | Mark the checkbox 'Remember me' | There is a visible tick inside of the checkbox |
| 4 | Click on the button 'Login' | The system does not let the user to log in. The systen gives the information about incorrect email or password that has been entered. Incorrect data has not been remembered on the login page |

<br>
<br>

## Test case: Login page - Entering incorrect data 3 times
The goal of the test is to check if after entering incorrect password 3 times the account will be blocked.

Previous conditions:
- It is needed to have a registered account

- Open the browser

- Go to the login page of the online store: http://skleptest.pl/my-account/


| # | Description | Expected result |
| -------------------------------- |-------------------------------- |  -------------------------------- | 
| 1 | In the field 'email address' type the existing email address that is registered | The user sees the email address in the field |
| 2 | In the field 'password' type the incorrect password | The password is hidden but the user sees the security dots (their number is the number of the typed password's signs) |
| 3 | Click on the button 'Login' | The system does not let the user to log in. The system gives the information about incorrect email or password that has been entered |
| 4 | Repeat steps: 1, 2, 3 - another 2 times | After the 3rd time of entering incorrect password the system informs the user that the account has been blocked and it is needed to reset it|
| 5 | Enter the correct email address | The user sees the email address in the field |
| 6 | Enter the correct password  | The user sees the security dots in the field of password |
| 7 | Click on the button 'Login' | The system informs the user that the account had been blocked and it is needed to reset the password |

<br>
<br>

## Test case: Login page - Login page - Resetting the password
The goal of the test is to check if it is possible to reset the password.

Previous conditions:
- It is needed to have a registered account.

- It is needed to have a mailbox on registered email.

- Open the browser.

- Sign in the mailbox.

- Open another card in the browser.

- Go to the login page of the online store: http://skleptest.pl/my-account/


| # | Description | Expected result |
| -------------------------------- |-------------------------------- |  -------------------------------- | 
| 1 | Click on the link 'Lost your password?' which is placed under the 'Login' button | The application takes the user to the website with the field to enter the email address or username |
| 2 | Enter the correct email address | The user sees the email address in the field |
| 3 | Click on the button 'Reset password' | The application informs the user that the email with a link has been sent. The user receives the email to the mailbox |
| 4 | In the mailbox open the email from the application | The user sees the message with the link in order to reset the password |
| 5 | Click on the link | The user is taken to the website where a new password can be assigned |
| 6 | Give a new password in the field and click 'Reset the password' | The system informs the user that the password has been reset |

<br>
<br>

## Test case: Login page - Using reset password
The goal of the test is to check if it is possible to log in using the reset password.

Previous conditions:
- It is needed to have a registered account.

- It is needed to have a mailbox on registered email.

- Open the browser.

- Sign in the mailbox.

- Open another card in the browser.

- Go to the login page of the online store: http://skleptest.pl/my-account/


| # | Description | Expected result |
| -------------------------------- |-------------------------------- |  -------------------------------- | 
| 1 | Click on the link 'Lost your password?' which is placed under the 'Login' button | The application takes the user to the website with the field to enter the email address or username |
| 2 | Enter the correct email address | The user sees the email address in the field |
| 3 | Click on the button 'Reset password' | The application informs the user that the email with a link has been sent. The user receives the email to the mailbox |
| 4 | In the mailbox open the email from the application | The user sees the message with the link in order to reset the password |
| 5 | Click on the link | The user is taken to the website where a new password can be assigned |
| 6 | Give a new password in the field, repeat it in the proper field and click 'Reset the password' | The system informs the user that the password has been reset |
| 7 | Go to the login page http://skleptest.pl/my-account/ | The user sees the login page |
| 8 | Enter the correct email address and new password | The user sees the email address and the security dots in the password field |
| 9 | Click on the button 'Login' | The system takes the user to the user panel |

<br>
<br>







[def]: https://drive.google.com/file/d/14E0rDlC5DENiwVBseXntWdcoTYBW-DN4/view?usp=share_link