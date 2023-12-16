# submit-button

<input>
type="submit"
The submit button is used to send a form to the server.
name
It can use a name attribute but it does not need to have one.
value
The value attribute is used to control the text that appears on a button. It is a good idea to specify the words you want to appear on a button because the default value of buttons on some browsers is ‘Submit query’ and this might not be appropriate for all kinds of form.

<form action="http://www.example.com/subscribe.php">
 <p>Subscribe to our email list:</p>
 <input type="text" name="email" />
 <input type="submit" name="subscribe" value="Subscribe" />
</form>
