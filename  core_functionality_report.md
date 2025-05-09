При запуске приложения мы попадаем на экран логина или регистрации. После успешной авторизации пользователь выбирает коворкинг, в котором будет бронировать место, и переходит к основному экрану.

Если пользователь вошел в свой аккаунт:

---
Первый экран — интерактивная карта для бронирования мест.
Пользователь может выбрать несколько сидений и, нажав на кнопку, перейти к экрану оплаты. После успешной оплаты место бронируется и добавляется в базу данных. 
![first_screen](./2.gif)

---
Второй экран — мои брони. Здесь отображаются все места, которые пользователь когда-либо бронировал. При нажатии на конкретную бронь открывается QR-код, который администратор коворкинга может отсканировать для верификации пользователя на площадке, подтверждая, что бронь действительно принадлежит этому пользователю.
![second_screen](./photo_2025-03-03_17-26-46.jpg)

---
Третий экран — профиль. В этом разделе пользователь может просматривать и редактировать свои данные, а также выйти из аккаунта.
![third_screen](./photo_2025-03-04_09-47-27.jpg )

Если пользователь вошел как администратор: Администратор имеет возможность не только выбрать коворкинг, но и создать новый. Для этого необходимо загрузить файл .svg с разметкой, соответствующей документации по созданию коворкинга в Figma.
![figma](Снимок_экрана_2025-03-04_094803.png)

Первый экран — список пользователей. Здесь администратор может просматривать всех пользователей, видеть их брони, а также удалять пользователей или редактировать их брони.
Второй экран — сканер QR-кодов. Администратор может отсканировать QR-код гостя, чтобы получить информацию о его брони.
Третий экран — профиль. В этом разделе администратор может выйти из аккаунта.