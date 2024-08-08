# saved-passwerd.index.html




[Uploading index sp.html…]()<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>حفظ الكلمات السرية</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        #passwords-container {
            width: 80%;
            margin: 40px auto;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        #passwords-list {
            list-style: none;
            padding: 0;
            margin: 0;
        }
        #passwords-list li {
            padding: 10px;
            border-bottom: 1px solid #ccc;
        }
        #passwords-list li:last-child {
            border-bottom: none;
        }
        #add-password-form {
            margin-top: 20px;
        }
        #add-password-form input[type="text"] {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
        }
        #add-password-form button[type="submit"] {
            width: 100%;
            padding: 10px;
            background-color: #4CAF50;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        #add-password-form button[type="submit"]:hover {
            background-color: #3e8e41;
        }
    </style>
</head>
<body>
    <div id="passwords-container">
        <h2>حفظ الكلمات السرية</h2>
        <ul id="passwords-list"></ul>
        <form id="add-password-form">
            <input type="text" id="password-input" placeholder="أدخل كلمة سرية جديدة">
            <button type="submit">إضافة</button>
        </form>
    </div>

    <script src="javascript.js"></script>
</body>
</html>




