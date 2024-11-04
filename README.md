# web-tech-log-in-page<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Person Profile</title>
</head>
<body>

    <form action="#" method="post" enctype="multipart/form-data">
        <table border="1" cellpadding="8" cellspacing="0" style="width: 50%; margin: auto;">
            <tr>
                <td colspan="3" align="center">
                    <h2>PERSON PROFILE</h2>
                </td>
            </tr>
            <tr>
                <td>Name</td>
                <td colspan="2"><input type="text" name="name" required></td>
            </tr>
            <tr>
                <td>Email</td>
                <td colspan="2"><input type="email" name="email" required></td>
            </tr>
            <tr>
                <td>Gender</td>
                <td colspan="2">
                    <input type="radio" name="gender" value="male"> Male
                    <input type="radio" name="gender" value="female"> Female
                    <input type="radio" name="gender" value="other"> Other
                </td>
            </tr>
            <tr>
                <td>Date of Birth</td>
                <td colspan="2">
                    <input type="text" name="day" size="2" maxlength="2" placeholder="DD"> /
                    <input type="text" name="month" size="2" maxlength="2" placeholder="MM"> /
                    <input type="text" name="year" size="4" maxlength="4" placeholder="YYYY">
                </td>
            </tr>
            <tr>
                <td>Blood Group</td>
                <td colspan="2">
                    <select name="blood_group">
                        <option value="A+">A+</option>
                        <option value="A-">A-</option>
                        <option value="B+">B+</option>
                        <option value="B-">B-</option>
                        <option value="AB+">AB+</option>
                        <option value="AB-">AB-</option>
                        <option value="O+">O+</option>
                        <option value="O-">O-</option>
                    </select>
                </td>
            </tr>
            <tr>
                <td>Degree</td>
                <td colspan="2">
                    <input type="checkbox" name="degree" value="SSC"> SSC
                    <input type="checkbox" name="degree" value="HSC"> HSC
                    <input type="checkbox" name="degree" value="BSc"> B.Sc.
                    <input type="checkbox" name="degree" value="MSc"> M.Sc.
                </td>
            </tr>
            <tr>
                <td>Photo</td>
                <td colspan="2">
                    <input type="file" name="photo">
                </td>
            </tr>
            <tr>
                <td colspan="3" align="center">
                    <input type="submit" value="Submit">
                    <input type="reset" value="Reset">
                </td>
            </tr>
        </table>
    </form>

</body>
</html>
