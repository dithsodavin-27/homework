<!DOCTYPE html>
<html>
<head>
    <title>Student Registration Form</title>
</head>
<body>

    <h2 align="center">Student Registration Form</h2>

    <table border="1" align="center" cellpadding="10" cellspacing="0">
        <tr>
            <td>Student ID</td>
            <td><input type="text" name="studentid"></td>
        </tr>

        <tr>
            <td>First Name</td>
            <td><input type="text" name="firstname"></td>
        </tr>

        <tr>
            <td>Last Name</td>
            <td><input type="text" name="lastname"></td>
        </tr>

        <tr>
            <td>Gender</td>
            <td>
                <input type="radio" name="gender"> Male
                <input type="radio" name="gender"> Female
            </td>
        </tr>

        <tr>
            <td>Date of Birth</td>
            <td><input type="date" name="dob"></td>
        </tr>

        <tr>
            <td>Email</td>
            <td><input type="email" name="email"></td>
        </tr>

        <tr>
            <td>Phone</td>
            <td><input type="text" name="phone"></td>
        </tr>

        <tr>
            <td>Address</td>
            <td>
                <textarea rows="4" cols="30"></textarea>
            </td>
        </tr>

        <tr>
            <td>Course</td>
            <td>
                <select>
                    <option>Select Course</option>
                    <option>Computer Science</option>
                    <option>Information Technology</option>
                    <option>Business Management</option>
                    <option>Accounting</option>
                </select>
            </td>
        </tr>

        <tr>
            <td>Photo</td>
            <td><input type="file"></td>
        </tr>

        <tr>
            <td colspan="2" align="center">
                <input type="submit" value="Save">
                <input type="reset" value="Clear">
            </td>
        </tr>
    </table>

</body>
</html>
