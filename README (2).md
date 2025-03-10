<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Survey Form</title>
    <style>
        body {
            background: linear-gradient(to right, #00b09b, #96c93d);
            font-family: Arial, sans-serif;
            text-align: center;
            color: #fff;
            margin: 0;
            padding: 0;
        }

        form {
            background: #fff;
            max-width: 500px;
            margin: 50px auto;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
            color: #333;
        }

        .form-control {
            text-align: left;
            margin-bottom: 15px;
        }

        .form-control label {
            font-weight: bold;
        }

        .form-control input, .form-control select, .form-control textarea {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 16px;
        }

        .form-control input[type="radio"], .form-control input[type="checkbox"] {
            width: auto;
        }

        button {
            background: #28a745;
            color: white;
            border: none;
            padding: 10px;
            font-size: 18px;
            border-radius: 5px;
            cursor: pointer;
            width: 100%;
            margin-top: 20px;
        }

        button:hover {
            background: #218838;
        }
    </style>
</head>

<body>
    <h1>Survey Form</h1>
    <form id="form">
        <div class="form-control">
            <label for="name">Name</label>
            <input type="text" id="name" placeholder="Enter your name" required>
        </div>

        <div class="form-control">
            <label for="email">Email</label>
            <input type="email" id="email" placeholder="Enter your email" required>
        </div>

        <div class="form-control">
            <label for="age">Age</label>
            <input type="number" id="age" placeholder="Enter your age" required>
        </div>

        <div class="form-control">
            <label for="role">Which option best describes you?</label>
            <select id="role">
                <option value="student">Student</option>
                <option value="intern">Intern</option>
                <option value="professional">Professional</option>
                <option value="other">Other</option>
            </select>
        </div>

        <div class="form-control">
            <label>Would you recommend us to a friend?</label>
            <input type="radio" name="recommend" value="yes"> Yes
            <input type="radio" name="recommend" value="no"> No
            <input type="radio" name="recommend" value="maybe"> Maybe
        </div>

        <div class="form-control">
            <label>Languages and Frameworks known</label><br>
            <input type="checkbox"> C
            <input type="checkbox"> C++
            <input type="checkbox"> Java
            <input type="checkbox"> Python
            <input type="checkbox"> JavaScript
            <input type="checkbox"> React
            <input type="checkbox"> Angular
            <input type="checkbox"> Django
        </div>

        <div class="form-control">
            <label for="comment">Any comments or suggestions</label>
            <textarea id="comment" placeholder="Enter your comments here"></textarea>
        </div>

        <button type="submit">Submit</button>
    </form>
</body>

</html>
