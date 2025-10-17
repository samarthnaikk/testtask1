import os

    def generate_html_file():
        html_content = """<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The World of Tennis</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            line-height: 1.6;
            color: #333;
        }
        h1 {
            color: #0056b3;
        }
        p {
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <h1>Tennis: A Dynamic and Exciting Sport</h1>
    <p>Tennis is a popular racket sport that can be played individually against a single opponent (singles) or between two teams of two players each (doubles). Players use a racket to strike a felt-covered hollow rubber ball over a net into the opponent's court. The objective is to hit the ball in such a way that the opponent cannot make a valid return, earning a point. Known for its demanding physical and mental challenges, tennis is enjoyed by millions worldwide, both recreationally and professionally.</p>
</body>
</html>"""

        with open("index.html", "w") as f:
            f.write(html_content)
        print("✅ index.html created successfully!")

    if __name__ == "__main__":
        generate_html_file()