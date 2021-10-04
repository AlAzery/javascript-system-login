# javascript-system-login

<h3>copy code</h3>

````html
<h1>login</h1>
<form action="#login" method="post" accept-charset="utf-8">
  <label for="username">username</label>
  <input type="text" name="username" id="username" />
  <br />
  <label for="password">password</label>
  <input type="password" name="password" id="password" />
  <button type="submit" onclick="login()">login</button>
</form>
````

````javascript

<!--java script -->
<script>
    function login() {
  var username = document.getElementById("username").value;
  var password = document.getElementById("password").value;

  var username1 = "123";
  var password1 = "123";

  if (username == username1 && password == password1) {
    alert("success login");
  } else {
    alert("gagal login");
  }
  }
</script>

````