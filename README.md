# DatingApp
This is a dating App
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dating App</title>
    <style>
        /* Inline CSS for simplicity, consider using external stylesheets */
        body {
            font-family: Arial, sans-serif;
        }
        .profile {
            border: 1px solid #ccc;
            padding: 20px;
            margin: 10px;
        }
        .profile img {
            max-width: 100%;
            height: auto;
        }
        .btn-like, .btn-dislike {
            cursor: pointer;
            padding: 10px 20px;
            background-color: #ff5733;
            color: #fff;
            border: none;
            border-radius: 5px;
            margin: 5px;
        }
    </style>
</head>
<body>
    <h1>Welcome to the Dating App</h1>
    <div class="profile">
        <img src="user1.jpg" alt="User 1">
        <h2>User 1</h2>
        <p>Age: 25</p>
        <p>Location: New York</p>
        <button class="btn-like">Like</button>
        <button class="btn-dislike">Dislike</button>
    </div>
    <div class="profile">
        <img src="user2.jpg" alt="User 2">
        <h2>User 2</h2>
        <p>Age: 30</p>
        <p>Location: Los Angeles</p>
        <button class="btn-like">Like</button>
        <button class="btn-dislike">Dislike</button>
    </div>

    <script>
        // JavaScript for handling likes and dislikes
        const likeButtons = document.querySelectorAll('.btn-like');
        const dislikeButtons = document.querySelectorAll('.btn-dislike');

        likeButtons.forEach((button) => {
            button.addEventListener('click', () => {
                alert('You liked this user!');
                // You can add logic to handle the liking action here
            });
        });

        dislikeButtons.forEach((button) => {
            button.addEventListener('click', () => {
                alert('You disliked this user!');
                // You can add logic to handle the disliking action here
            });
        });
    </script>
</body>
</html>
