<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Food Calorie & BMI Prediction</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            padding: 2rem;
            background-color: #f8f9fa;
        }
        .section-title {
            margin-top: 2rem;
            margin-bottom: 1rem;
            font-weight: bold;
            color: #343a40;
        }
        .card {
            margin-bottom: 1.5rem;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1 class="text-center mb-4">🍽️ Food Calorie Estimation and BMI Prediction</h1>

        <p>This project is developed using <strong>Python</strong> and the <strong>Django framework</strong>, focusing on healthcare and nutrition analysis. It helps users monitor their fitness by predicting <strong>BMI</strong>, <strong>caloric intake</strong>, and providing <strong>diet recommendations</strong> using data and images.</p>

        <h2 class="section-title">🔍 Project Overview</h2>

        <div class="card">
            <div class="card-body">
                <h5 class="card-title">📊 Module 1: BMI Estimation</h5>
                <ul>
                    <li>Predicts Body Mass Index (BMI)</li>
                    <li>Input options:
                        <ul>
                            <li>Height, Weight, and Age</li>
                            <li>Photo upload (vision-based estimation)</li>
                        </ul>
                    </li>
                    <li>Classifies BMI into categories (Underweight, Normal, Overweight, Obese)</li>
                </ul>
            </div>
        </div>

        <div class="card">
            <div class="card-body">
                <h5 class="card-title">🥗 Module 2: Calorie Prediction and Diet Planning</h5>
                <ul>
                    <li>Suggests daily calorie needs based on BMI and inputs</li>
                    <li>Provides:
                        <ul>
                            <li>Diet plan recommendations</li>
                            <li>Suggested sports & physical activities</li>
                        </ul>
                    </li>
                </ul>
            </div>
        </div>

        <div class="card">
            <div class="card-body">
                <h5 class="card-title">🍕 Module 3: Image-Based Food Calorie Prediction</h5>
                <ul>
                    <li>Uses image recognition to detect food items</li>
                    <li>Predicts caloric content of detected foods</li>
                    <li>Helps track visual food intake</li>
                </ul>
            </div>
        </div>

        <h2 class="section-title">⚙️ Tech Stack</h2>
        <ul>
            <li><strong>Backend:</strong> Python, Django</li>
            <li><strong>Frontend:</strong> HTML5, CSS3, Bootstrap</li>
            <li><strong>Image Processing:</strong> OpenCV, TensorFlow/Keras</li>
            <li><strong>Database:</strong> SQLite</li>
        </ul>

        <h2 class="section-title">🚀 Features</h2>
        <ul>
            <li>Health metric predictions</li>
            <li>User-friendly web interface</li>
            <li>Image-based analysis for BMI and food intake</li>
            <li>Custom diet and fitness advice</li>
        </ul>

        <h2 class="section-title">📌 Future Enhancements</h2>
        <ul>
            <li>Integration with fitness trackers or wearables</li>
            <li>Enhanced food classification models</li>
            <li>Mobile application support</li>
        </ul>

        <h2 class="section-title">🧠 Project By</h2>
        <p><strong>Jaykiran Kotthakota</strong></p>
        <ul>
            <li><a href="https://www.linkedin.com/in/jaykiran-kotthakota-787525154" target="_blank">🔗 LinkedIn</a></li>
            <li><a href="https://github.com/jaykiran-kotthakota" target="_blank">💻 GitHub</a></li>
            <li><a href="https://www.instagram.com/jaykiran_kotthakota" target="_blank">📸 Instagram</a></li>
        </ul>
    </div>

</body>
</html>
