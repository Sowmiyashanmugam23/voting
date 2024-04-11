# voting
Naan Mudhaalvan- Voting Webapplication using django framework
<!DOCTYPE html>
<html lang="en">
 
<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css"
        integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
    <title>Polling {% block title %}{% endblock %}</title>
</head>
 
<body>
    <!--NavBar-->
    {% include 'partials/_navbar.html'%}
    <div class="container">
        <div class="row">
            <div class=".col-md-6 m-auto">
                {% block content %}{% endblock%}
            </div>
        </div>
    </div>
</body>

</html>
