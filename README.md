# Ex.06 Book Front Cover Page Design
## AIM:21.10.2023
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Clone the GitHub repository.

### Step 2:
Create a Django Admin interface.

### Step 3:
Write the HTML code with relevant CSS properties.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the HTML code.

### Step 6:
Publish the website in the given URL.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover Page Using HTML and CSS</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background: url('/static/image.png') center/cover no-repeat;
            display: flex;
            align-items: center;
            justify-content: center;
            height: 200vh;
        }

        .book-cover {
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            padding: 20px;
            text-align: center;
        }

        .book-title {
            font-size: 28px;
            font-weight: bold;
            color: #333;
            margin-bottom: 10px;
        }

        .author {
            font-size: 18px;
            color: #666;
            margin-bottom: 20px;
        }

        .cover-image {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
            margin-bottom: 20px;
        }

        .publish-date {
            font-size: 16px;
            color: #888;
        }
    </style>
</head>
<body>

<div class="book-cover">
    <img class="cover-image" src="/static/image-1.png" alt="Book Cover Image">
    <div class="book-title">HARRY POTTER</div>
    <div class="author">by J.K Rowling</div>
    <div class="publish-date">Published on July 23, 2023</div>
</div>

</body>
</html>
```

## OUTPUT:
![283099423-d7a656f0-e1de-4f0a-8d74-fb84a71cb767](https://github.com/kamalesh2509/cover/assets/120444689/955b8d2c-3950-460e-b3fc-84bd526f91a2)





## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
