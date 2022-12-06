# Бычков Вячеслав    

## Junior Frontend - разработчик
***
## Контактные данные:
Телефон: 8928(---)----

Telegram: @SlavaByk
[T.me](
https://web.telegram.org/z/)

Email: Slavykbyk@gmail.com
***
### Коротко о себе:

Возраст: 22 года

Образование: Высшее- оконченное 

Специальность: Прикладная информатика 
***
### Навыки:

* HTML, CSS

* SQL

* GIT

* VS Code 
 
* Adobe photoshop, Figma, Sony Vegas

### Пример кода

```
 public function actionContact()
    {
        $model = new ContactForm();
        if ($model->load(Yii::$app->request->post()) && $model->contact(Yii::$app->params['adminEmail'])) {
            Yii::$app->session->setFlash('contactFormSubmitted');

            return $this->refresh();
        }
        return $this->render('contact', [
            'model' => $model,
        ]);
    }

```

***

### Языки 

Русский - носитель 

Английский - A2



