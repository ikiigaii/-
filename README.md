<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Тест: Районы и области Казахстана</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 20px;
            background-color: #f4f4f4;
            text-align: center;
        }

        h1 {
            color: #333;
        }

        form {
            max-width: 600px;
            margin: 0 auto;
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .question {
            margin-bottom: 20px;
        }

        label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }

        select {
            width: 100%;
            padding: 8px;
            margin-top: 5px;
            margin-bottom: 15px;
            box-sizing: border-box;
        }

        .result {
            font-weight: bold;
            margin-top: 10px;
        }

        input[type="button"] {
            background-color: #4caf50;
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
        }

        input[type="button"]:hover {
            background-color: #45a049;
        }

        #finalResult {
            margin-top: 20px;
            font-size: 18px;
        }
    </style>
</head>

<body>
    <h1>Тест: Районы и области Казахстана</h1>
    <form>
        <!-- Добавленные вопросы -->
        <div class="question">
            <label for="question1">1. Район "Алаколь":</label>
            <select id="question1" name="question1" required>
                <option value="">Выберите область</option>
                <option value="almaty">Алматинская область</option>
                <option value="east-kazakhstan">Восточно-Казахстанская область</option>
                <option value="karaganda">Карагандинская область</option>
                <option value="aktobe">Актюбинская область</option>
            </select>
            <div class="result" id="result1"></div>
        </div>

        <div class="question">
            <label for="question2">2. Район "Кызылорда":</label>
            <select id="question2" name="question2" required>
                <option value="">Выберите область</option>
                <option value="almaty">Алматинская область</option>
                <option value="west-kazakhstan">Западно-Казахстанская область</option>
                <option value="kostanay">Костанайская область</option>
                <option value="kyzylorda">Кызылординская область</option>
            </select>
            <div class="result" id="result2"></div>
        </div>

        <div class="question">
            <label for="question3">3. Район "Акмолинский":</label>
            <select id="question3" name="question3" required>
                <option value="">Выберите область</option>
                <option value="almaty">Алматинская область</option>
                <option value="north-kazakhstan">Северно-Казахстанская область</option>
                <option value="karaganda">Карагандинская область</option>
                <option value="aktobe">Актюбинская область</option>
            </select>
            <div class="result" id="result3"></div>
        </div>

        <div class="question">
            <label for="question4">4. Район "Атырау":</label>
            <select id="question4" name="question4" required>
                <option value="">Выберите область</option>
                <option value="west-kazakhstan">Западно-Казахстанская область</option>
                <option value="atyrau">Атырауская область</option>
                <option value="mangystau">Мангистауская область</option>
                <option value="aktyubinsk">Актюбинская область</option>
            </select>
            <div class="result" id="result4"></div>
        </div>

        <div class="question">
            <label for="question5">5. Район "Туркестан":</label>
            <select id="question5" name="question5" required>
                <option value="">Выберите область</option>
                <option value="almaty">Алматинская область</option>
                <option value="south-kazakhstan">Южно-Казахстанская область</option>
                <option value="zhambyl">Жамбылская область</option>
                <option value="kyzylorda">Кызылординская область</option>
            </select>
            <div class="result" id="result5"></div>
        </div>

        <div class="question">
            <label for="question6">6. Район "Мангистау":</label>
            <select id="question6" name="question6" required>
                <option value="">Выберите область</option>
                <option value="west-kazakhstan">Западно-Казахстанская область</option>
                <option value="mangystau">Мангистауская область</option>
                <option value="atyrau">Атырауская область</option>
                <option value="aktobe">Актюбинская область</option>
            </select>
            <div class="result" id="result6"></div>
        </div>

        <div class="question">
            <label for="question7">7. Район "Костанай":</label>
            <select id="question7" name="question7" required>
                <option value="">Выберите область</option>
                <option value="almaty">Алматинская область</option>
                <option value="west-kazakhstan">Западно-Казахстанская область</option>
                <option value="kostanay">Костанайская область</option>
                <option value="kyzylorda">Кызылординская область</option>
            </select>
            <div class="result" id="result7"></div>
        </div>

        <div class="question">
            <label for="question8">8. Район "Караганда":</label>
            <select id="question8" name="question8" required>
                <option value="">Выберите область</option>
                <option value="almaty">Алматинская область</option>
                <option value="east-kazakhstan">Восточно-Казахстанская область</option>
                <option value="karaganda">Карагандинская область</option>
                <option value="aktobe">Актюбинская область</option>
            </select>
            <div class="result" id="result8"></div>
        </div>

        <div class="question">
            <label for="question9">9. Район "Актобе":</label>
            <select id="question9" name="question9" required>
                <option value="">Выберите область</option>
                <option value="almaty">Алматинская область</option>
                <option value="west-kazakhstan">Западно-Казахстанская область</option>
                <option value="karaganda">Карагандинская область</option>
                <option value="aktobe">Актюбинская область</option>
            </select>
            <div class="result" id="result9"></div>
        </div>

        <div class="question">
            <label for="question10">10. Район "Жамбыл":</label>
            <select id="question10" name="question10" required>
                <option value="">Выберите область</option>
                <option value="almaty">Алматинская область</option>
                <option value="south-kazakhstan">Южно-Казахстанская область</option>
                <option value="zhambyl">Жамбылская область</option>
                <option value="kyzylorda">Кызылординская область</option>
            </select>
            <div class="result" id="result10"></div>
        </div>

        <!-- Добавленные вопросы -->
        <div class="question">
            <label for="question11">11. Район "Кызылжар":</label>
            <select id="question11" name="question11" required>
                <option value="">Выберите область</option>
                <option value="almaty">Алматинская область</option>
                <option value="east-kazakhstan">Восточно-Казахстанская область</option>
                <option value="karaganda">Карагандинская область</option>
                <option value="aktobe">Актюбинская область</option>
            </select>
            <div class="result" id="result11"></div>
        </div>

        <div class="question">
            <label for="question12">12. Район "Талдыкорган":</label>
            <select id="question12" name="question12" required>
                <option value="">Выберите область</option>
                <option value="almaty">Алматинская область</option>
                <option value="east-kazakhstan">Восточно-Казахстанская область</option>
                <option value="karaganda">Карагандинская область</option>
                <option value="aktobe">Актюбинская область</option>
            </select>
            <div class="result" id="result12"></div>
        </div>

        <div class="question">
            <label for="question13">13. Район "Шымкент":</label>
            <select id="question13" name="question13" required>
                <option value="">Выберите область</option>
                <option value="almaty">Алматинская область</option>
                <option value="south-kazakhstan">Южно-Казахстанская область</option>
                <option value="zhambyl">Жамбылская область</option>
                <option value="kyzylorda">Кызылординская область</option>
            </select>
            <div class="result" id="result13"></div>
        </div>

        <div class="question">
            <label for="question14">14. Район "Усть-Каменогорск":</label>
            <select id="question14" name="question14" required>
                <option value="">Выберите область</option>
                <option value="almaty">Алматинская область</option>
                <option value="east-kazakhstan">Восточно-Казахстанская область</option>
                <option value="karaganda">Карагандинская область</option>
                <option value="aktobe">Актюбинская область</option>
            </select>
            <div class="result" id="result14"></div>
        </div>

        <div class="question">
            <label for="question15">15. Район "Кокшетау":</label>
            <select id="question15" name="question15" required>
                <option value="">Выберите область</option>
                <option value="almaty">Алматинская область</option>
                <option value="north-kazakhstan">Северно-Казахстанская область</option>
                <option value="karaganda">Карагандинская область</option>
                <option value="aktobe">Актюбинская область</option>
            </select>
            <div class="result" id="result15"></div>
        </div>

        <div class="question">
            <label for="question16">16. Район "Павлодар":</label>
            <select id="question16" name="question16" required>
                <option value="">Выберите область</option>
                <option value="almaty">Алматинская область</option>
                <option value="east-kazakhstan">Восточно-Казахстанская область</option>
                <option value="karaganda">Карагандинская область</option>
                <option value="aktobe">Актюбинская область</option>
            </select>
            <div class="result" id="result16"></div>
        </div>

        <div class="question">
            <label for="question17">17. Район "Жезказган":</label>
            <select id="question17" name="question17" required>
                <option value="">Выберите область</option>
                <option value="almaty">Алматинская область</option>
                <option value="south-kazakhstan">Южно-Казахстанская область</option>
                <option value="zhambyl">Жамбылская область</option>
                <option value="kyzylorda">Кызылординская область</option>
            </select>
            <div class="result" id="result17"></div>
        </div>

        <div class="question">
            <label for="question18">18. Район "Тараз":</label>
            <select id="question18" name="question18" required>
                <option value="">Выберите область</option>
                <option value="almaty">Алматинская область</option>
                <option value="south-kazakhstan">Южно-Казахстанская область</option>
                <option value="zhambyl">Жамбылская область</option>
                <option value="kyzylorda">Кызылординская область</option>
            </select>
            <div class="result" id="result18"></div>
        </div>

        <div class="question">
            <label for="question19">19. Район "Актау":</label>
            <select id="question19" name="question19" required>
                <option value="">Выберите область</option>
                <option value="west-kazakhstan">Западно-Казахстанская область</option>
                <option value="mangystau">Мангистауская область</option>
                <option value="atyrau">Атырауская область</option>
                <option value="aktobe">Актюбинская область</option>
            </select>
            <div class="result" id="result19"></div>
        </div>

        <div class="question">
            <label for="question20">20. Район "Семей":</label>
            <select id="question20" name="question20" required>
                <option value="">Выберите область</option>
                <option value="almaty">Алматинская область</option>
                <option value="east-kazakhstan">Восточно-Казахстанская область</option>
                <option value="karaganda">Карагандинская область</option>
                <option value="aktobe">Актюбинская область</option>
            </select>
            <div class="result" id="result20"></div>
        </div>

        <input type="button" value="Проверить ответы" onclick="checkAnswers()">
        <div id="finalResult" class="result"></div>

        <script>
            function checkAnswers() {
                var correctAnswers = {
                    question1: "east-kazakhstan",
                    question2: "kyzylorda",
                    question3: "north-kazakhstan",
                    question4: "atyrau",
                    question5: "south-kazakhstan",
                    question6: "mangystau",
                    question7: "kostanay",
                    question8: "karaganda",
                    question9: "aktobe",
                    question10: "zhambyl",
                    question11: "east-kazakhstan",
                    question12: "almaty",
                    question13: "south-kazakhstan",
                    question14: "east-kazakhstan",
                    question15: "north-kazakhstan",
                    question16: "east-kazakhstan",
                    question17: "south-kazakhstan",
                    question18: "zhambyl",
                    question19: "mangystau",
                    question20: "east-kazakhstan"
                    // Добавьте правильные ответы для остальных вопросов
                };

                var totalQuestions = 20; // Общее количество вопросов
                var correctCount = 0; // Счетчик правильных ответов

                for (var i = 1; i <= totalQuestions; i++) {
                    var userAnswer = document.getElementById("question" + i).value;
                    var resultDiv = document.getElementById("result" + i);

                    if (userAnswer === correctAnswers["question" + i]) {
                        resultDiv.textContent = "Правильно!";
                        resultDiv.style.color = "#4caf50";
                        correctCount++;
                    } else {
                        resultDiv.textContent = "Неправильно. Правильный ответ: " + translateToRussian(correctAnswers["question" + i]);
                        resultDiv.style.color = "#f44336";
                    }
                }

                var finalResultDiv = document.getElementById("finalResult");
                finalResultDiv.textContent = "Вы ответили правильно на " + correctCount + " из " + totalQuestions + " вопросов.";
            }

            function translateToRussian(regionCode) {
                var translations = {
                    "almaty": "Алматинская область",
                    "east-kazakhstan": "Восточно-Казахстанская область",
                    "karaganda": "Карагандинская область",
                    "aktobe": "Актюбинская область",
                    "west-kazakhstan": "Западно-Казахстанская область",
                    "kostanay": "Костанайская область",
                    "kyzylorda": "Кызылординская область",
                    "atyrau": "Атырауская область",
                    "mangystau": "Мангистауская область",
                    "north-kazakhstan": "Северно-Казахстанская область",
                    "south-kazakhstan": "Южно-Казахстанская область",
                    "zhambyl": "Жамбылская область"
                };

                return translations[regionCode] || regionCode;
            }
        </script>
    </form>
</body>

</html>

