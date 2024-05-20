<!DOCTYPE html>
<html>
<head>
	<title>loginDocument</title>
</head>
<body>
	<form action="verify.php" method="post">
        <fieldset>
            <legend>Login Page</legend>

            <table>
                <tr>
                    <td><label>User Name:</label></td>
                    <td><input type="text" name="txtusername"></td>
                </tr>
                <tr>
                    <td><label>Password:</label></td>
                    <td><input type="password" name="txtpassword"></td>
                </tr>
                <tr>
                    <td><input type="submit" name="btnsubmit"></td>
                    <td><input type="reset" name="btnclear" value="Clear"></td>
                </tr>
                
            </table>
        </fieldset>
    </form>
    
</body>
</html>
