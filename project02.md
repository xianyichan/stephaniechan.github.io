
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Layout</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
        }

        .container {
            text-align: center;
        }

        .description p {
            margin-top: 20px;
        }

        .content {
            display: flex;
            position: relative;
            align-items: flex-start;
        }

        .left-side, .right-side {
            flex: 1;
        }

        .vertical-line {
            position: absolute;
            left: 50%;
            top: 0;
            bottom: 0;
            width: 1px;
            background-color: #000;
        }

        .left-side img, .right-side img {
            max-width: 100%;
            height: auto;
        }

        .right-side {
            text-align: right;
        }

        .second-image {
            margin-top: 50px; /* Adjust based on preference */
            display: block; /* This ensures the image respects the right-side text alignment */
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="description">
            <p>This is an overall description of the website content. aaaa </p>
        </div>
        <div class="content">
            <div class="left-side">
                <img src="./assets/images/AWS Cloud Computing.png" alt="First Image">
                <p>Description text for the first image.</p>
            </div>
            <div class="vertical-line"></div>
            <div class="right-side">
                <img src="./assets/images/Windows Server.png" alt="Second Image" class="second-image">
                <p>Description text for the second image.</p>
            </div>
        </div>
    </div>
</body>
</html>



* * *
* * *
>The goal is to leverage technology to create a more transparent, secure, and user-friendly system that not only meets compliance requirements but also contributes to a more agile and responsive asset management workflow. 
![Branching](https://media.discordapp.net/attachments/756886213276860477/1213859945288572958/image.png?ex=65f7022b&is=65e48d2b&hm=059a1ba59316ed5e3751cc9db1dd03d2592a5fcffd899143b89857e3379cffd5&=&format=webp&quality=lossless&width=543&height=642)

![Branching](https://media.discordapp.net/attachments/756886213276860477/1213860350487699506/image.png?ex=65f7028b&is=65e48d8b&hm=4c1001a691311b5933ae03788f904624d68ed4493c48883a49352a313a1e8f68&=&format=webp&quality=lossless&width=643&height=642)

[Home Page](./index.md)
* * *
[Project 01](./project02.md)
* * *
[Project 03](./project04.md)

* * *