# <img src="https://emojis.slackmojis.com/emojis/images/1616212945/22482/coffee_cup.gif?1616212945" width=40px/>&nbsp;Espresso Express

😉 Heyyy !! Nice To See you!! we made cafeteria website using php with login/register authentication and with admin portal (using mysql database)

<b>Link :-</b> <a href="http://eecafeteria.epizy.com/">http://eecafeteria.epizy.com/</a>
<br><i>Forget passowrd mail probably in spam . Please check spam to reset password</i>

<b>Admin portal :-</b> <a href="http://eecafeteria.epizy.com/index_ad.php">http://eecafeteria.epizy.com/index_ad.php</a>
<br><i>Email and Password for admin portal is mentioned below</i>

---


# ✨ Some Salient Feature

- [x] <i>🔐 Login/Register Authentication</i> 
- [x] <i>🐇 Form Validation Using Ajax</i> 
- [x] <i>🔑 Password Stored Encrypted In Database Using PHP Encryption (Hash-12)</i> 
- [x] <i>📧 Message is send to mail using <a href="https://github.com/PHPMailer/PHPMailer">PHP Mailer Libraray</a></i>
- [X] <i>☁ Forget Password :- Reset Password Link Send To your Mail</i>
- [X] <i>🛒 cart and order functionality</i>
- [X] <i>🧾 history order page</i>
- [X] <i>🎫 admin portal</i> 
- [X] <i>🍽 admin can add add new menu item and edit or delete menu item </i>
- [X] <i>📈 graph analysis for admin to check peak time and number of order in day</i>

---

# 🔑 Forget Password Mail

<i>Please check your spam if you still donot recieve mail please add issue </i>

---

# 🔐 Admin Authentication

* Email - admin@gmail.com
* Password - 123456

---

# 📸 Screenshots

## Home Page

<img src="sample/0.png" width="42%" >&nbsp;&nbsp;&nbsp;&nbsp;<img src="sample/1.png" width="42%" >
<br><br>
<img src="sample/3.png" width="42%" >&nbsp;&nbsp;&nbsp;&nbsp;<img src="sample/4.png" width="42%" >
<br><br>
<img src="sample/5.png" width="42%" >&nbsp;&nbsp;&nbsp;&nbsp;<img src="sample/6.png" width="42%" >
<br>

## Contact us/About us Page

<img src="sample/7.png" width="42%" >&nbsp;&nbsp;&nbsp;&nbsp;<img src="sample/8.png" width="42%" >
<br>

## Menu/Cart Page

<img src="sample/9.png" width="42%" >&nbsp;&nbsp;&nbsp;&nbsp;<img src="sample/10.png" width="42%" >
<br>

## Order History Page

<img src="sample/11.png" width="42%" >&nbsp;&nbsp;&nbsp;&nbsp;<img src="sample/12.png" width="42%" >
<br>

## Log In/Sign Up Page

<img src="sample/13.png" width="42%" >&nbsp;&nbsp;&nbsp;&nbsp;<img src="sample/14.png" width="42%" >

## Admin Login Page

<img src="sample/15.png" width="42%" >

## Admin Home Page

<img src="sample/16.png" width="42%" >&nbsp;&nbsp;&nbsp;&nbsp;<img src="sample/17.png" width="42%" >
<br><br>
<img src="sample/18.png" width="42%" >&nbsp;&nbsp;&nbsp;&nbsp;<img src="sample/19.png" width="42%" >
<br>

## Order List Page

<img src="sample/20.png" width="42%" >

## Menu List/Add Menu Page

<img src="sample/21.png" width="42%" >&nbsp;&nbsp;&nbsp;&nbsp;<img src="sample/22.png" width="42%" >

---
# ☁ Remeber After Clonning

Make Database and then create table using sql files uploaded here or Click <a href='https://github.com/YashikGarg/Espresso-Express/tree/main/database'>Here</a>

After Clonning Make Changes Of Database Information  in <b> config.php(Ln 2) and sendmsg.php(Ln 4)</b> and replace with your own databse name,password,host and username

<b>
  
```
$conn=new mysqli($your_servername, $your_username, $your_password, $your_dbname);
```
 </b>

And Also Replace YOUR Eamil And Password In <b>sendmsg.php(Ln 52,Ln 53) And  check_reset.php(Ln 29,Ln 30) - 
```
53. $mail->Username = 'your_email';             //Replace With Your Mail
54. $mail->Password = 'your_email_password';    //Replace With Your Mail Password 
```
 </b> 

And replace reciptent in  <b>sendmsg.php(Ln 60)

```
60. $mail->addAddress('your_reciptent', 'Admin');   //Replace With Your  Recipient
```
___
> If You ♥ It Please Drop a ⭐ 😉
