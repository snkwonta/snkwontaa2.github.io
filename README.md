<!DOCTYPE html>
<html>
    <head>
        <title>Calculator</title>
        
        <script src="calculator.js"></script>
        <link href="A2calc.css" rel="stylesheet" type="text/css">
    </head>
    <body>
        <div class="main">
        <form name="form">
            <input type="text" name="textview" disabled/>
        <table>
            <tr>
                <td><input class="button" type="button" value="&#8634" onclick="show()"></td>
                <td><input class="button" type="button" value="(" onclick="show('(')"></td>
                <td><input class="button" type="button" value=")" onclick="show(')')"></td>
                <td><input class="button" type="button" value="/" onclick="show('/')"></td>

            </tr>
            <tr>
                <td><input class="button" type="button" value="7" onclick="show(7)"></td>
                <td><input class="button" type="button" value="8" onclick="show(8)"></td>
                <td><input class="button" type="button" value="9" onclick="show(9)"></td>
                <td><input class="button" type="button" value="*" onclick="show('*')"></td>

            </tr>
            <tr>
                <td><input class="button" type="button" value="4" onclick="show(4)"></td>
                <td><input class="button" type="button" value="5" onclick="show(5)"></td>
                <td><input class="button" type="button" value="6" onclick="show(6)"></td>
                <td><input class="button" type="button" value="-" onclick="show('-')"></td>
            </tr>

            <tr>
                <td><input class="button" type="button" value="1" onclick="show(1)"></td>
                <td><input class="button" type="button" value="2" onclick="show(2)"></td>
                <td><input class="button" type="button" value="3" onclick="show(3)"></td>
                <td><input class="button" type="button" value="+" onclick="show('+')"></td>
            
            </tr>
            <tr>
                <td><input class="button" type="button" value="CE" onclick="show()"></td>
                <td><input class="button" type="button" value="0" onclick="show(0)"></td>
                <td><input class="button" type="button" value="." onclick="show('.')"></td>
                <td><input class="button" type="button" value="=" onclick="textview.value=eval(textview.value)"></td>
            </tr>

        </table>
    </form>
    </div>
    </body>
</html>

