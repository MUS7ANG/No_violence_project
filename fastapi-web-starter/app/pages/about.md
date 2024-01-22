<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Form Title</title>

  <style>
    /* Add your existing styles here */

    input[type="checkbox"],
    input[type="radio"] {
      width: 20px;
      height: 20px;
      margin-right: 5px;
    }

    label {
      display: block;
      margin-bottom: 10px;
    }

    fieldset {
      border: 1px solid #ccc;
      padding: 10px;
      margin-bottom: 15px;
    }

    legend {
      font-weight: bold;
    }

    /* Styling for the submit button */
    input[type="submit"] {
      background-color: #1b1d4d; /* Blue color */
      color: #fff; /* White text color */
      padding: 20px 40px;
      border: none;
      border-radius: 0px;
      cursor: pointer;
      position: absolute;
      bottom: 20px;
      right: 160px;
    }
  </style>
</head>

<body>
  <form action="/submit" method="post">
    <div class="auto-group-v4rs-LQu" id="MVJfoqqjPWwUPCLvvJV4Rs">
      <h3>
        <p class="item--V2u" id="1:71">Этот опросник может помочь собрать информацию о проблемах жертв насилия и
          предоставить ценные данные для разработки программ поддержки.</p>
      </h3>
      <div class="auto-group-1bq1-Kw3" id="MVJgGARD4XMBsf42eF1BQ1">

        <fieldset>
          <legend>1. Какого вы пола?</legend>
          <label>
            <input type="radio" id="femaleGender" name="gender" value="female">
            Я - женщина
          </label>
          <label>
            <input type="radio" id="maleGender" name="gender" value="male">
            Я - мужчина
          </label>
        </fieldset>

        <fieldset>
          <legend>2. Ваш возраст</legend>
          <label>
            <input type="radio" id="ageUnder18" name="age" value="under18">
            Младше 18 лет
          </label>
          <label>
            <input type="radio" id="age18-24" name="age" value="18-24">
            18-24
          </label>
          <label>
            <input type="radio" id="age25-34" name="age" value="25-34">
            25-34
          </label>
          <label>
            <input type="radio" id="age35-44" name="age" value="35-44">
            35-44
          </label>
          <label>
            <input type="radio" id="age45-54" name="age" value="45-54">
            45-54
          </label>
          <label>
            <input type="radio" id="age55AndAbove" name="age" value="55AndAbove">
            55 и старше
          </label>
        </fieldset>

        <fieldset>
          <legend>3. Какой тип насилия вы пережили?</legend>
          <label>
            <input type="checkbox" id="physicalViolence" name="violenceType[]" value="physical">
            Физическое насилие
          </label>
          <label>
            <input type="checkbox" id="emotionalViolence" name="violenceType[]" value="emotional">
            Эмоциональное/Психологическое насилие
          </label>
          <label>
            <input type="checkbox" id="sexualViolence" name="violenceType[]" value="sexual">
            Сексуальное насилие
          </label>
          <label>
            <input type="checkbox" id="financialViolence" name="violenceType[]" value="financial">
            Финансовое насилие
          </label>
        </fieldset>

        <fieldset>
          <legend>4. Какие ресурсы или услуги вы бы хотели получить для решения своих проблем?</legend>
          <label>
            <input type="checkbox" id="psychologicalSupport" name="supportService[]" value="psychological">
            Психологическая поддержка и консультация
          </label>
          <label>
            <input type="checkbox" id="legalAssistance" name="supportService[]" value="legal">
            Юридическая помощь
          </label>
          <label>
            <input type="checkbox" id="securityServices" name="supportService[]" value="security">
            Услуги по безопасности и защите
          </label>
          <label>
            <input type="checkbox" id="housingEmploymentAssistance" name="supportService[]" value="housingEmployment">
            Помощь в поиске жилья или работе
          </label>
        </fieldset>
        <br>
        <br>

        <!-- Submit button -->
        <input type="submit" value="Отправить">

      </div>
    </div>
  </form>
</body>

</html>
