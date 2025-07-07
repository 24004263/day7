## login.html;
```
<!DOCTYPE html>
<html>
<head>
    <title>Login</title>
</head>
<body>
    <h2>Login</h2>
    <form method="post">
        {% csrf_token %}
        {{ form.as_p }}
        <button type="submit">Login</button>
    </form>
</body>
</html>
```
## admin :
```
<h2>Welcome, Admin!</h2>
<p>This is your dashboard.</p>
<a href="/logout/">Logout</a>
```
## register:
```
<h2>Register</h2>
<form method="post">
    {% csrf_token %}
    {{ form.as_p }}
    <button type="submit">Register</button>
</form>
<p>Already have an account? <a href="/login/">Login</a></p>

```
## student:
```
h2>Welcome, Student!</h2>
<p>This is your dashboard.</p>
<a href="/logout/">Logout</a>
```

## output
![image](https://github.com/user-attachments/assets/b7c6ab0e-06c3-4c89-9832-43bbef229067)
