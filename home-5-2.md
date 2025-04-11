# Shartli operatorlar mashqlari (if else, ternary, switch case)

1. **Ball baholash**
   ```javascript
   Shart: O'quvchining ballini baholang:
   - 90-100: "A'lo"
   - 70-89: "Yaxshi"
   - 60-69: "Qoniqarli"
   - 0-59: "Qoniqarsiz"

   Test qiymatlari:
   ball = 85
   ball = 95
   ball = 65
   ball = 45

   Kutilgan natijalar:
   "Yaxshi"
   "A'lo"
   "Qoniqarli"
   "Qoniqarsiz"
   ```

2. **Hafta kunlari**
   ```javascript
   Shart: Raqamga qarab hafta kunini aniqlang (1-7)
   Agar raqam noto'g'ri bo'lsa "Noto'g'ri raqam" qaytaring

   Test qiymatlari:
   kun = 3
   kun = 7
   kun = 8

   Kutilgan natijalar:
   "Chorshanba"
   "Yakshanba"
   "Noto'g'ri raqam"
   ```

3. **Yoshga qarab toifa aniqlash**
   ```javascript
   Shart: Yoshga qarab toifani aniqlang:
   - 0-12: "Bola"
   - 13-19: "O'smir"
   - 20-59: "Katta"
   - 60+: "Qariya"

   Test qiymatlari:
   yosh = 8
   yosh = 15
   yosh = 45
   yosh = 65

   Kutilgan natijalar:
   "Bola"
   "O'smir"
   "Katta"
   "Qariya"
   ```

4. **Katta son**
   ```javascript
   Shart: Uchta sondan eng kattasini toping.
   Ternary operatordan foydalaning.

   Test qiymatlari:
   a = 5, b = 8, c = 3
   a = 10, b = 10, c = 10
   a = 2, b = 2, c = 3

   Kutilgan natijalar:
   8
   10
   3
   ```

5. **Oy kunlari**
   ```javascript
   Shart: Oy raqamiga qarab, shu oydagi kunlar sonini qaytaring.
   Kabisa yilini hisobga olmang.

   Test qiymatlari:
   oy = 2
   oy = 7
   oy = 13

   Kutilgan natijalar:
   28
   31
   "Noto'g'ri oy"
   ```

6. **Login tekshirish**
   ```javascript
   Shart: Login va parolni tekshiring:
   admin/12345 - "Xush kelibsiz, Admin"
   user/password - "Xush kelibsiz, Foydalanuvchi"
   Boshqa holat - "Login yoki parol xato"

   Test qiymatlari:
   login = "admin", parol = "12345"
   login = "user", parol = "password"
   login = "admin", parol = "wrong"

   Kutilgan natijalar:
   "Xush kelibsiz, Admin"
   "Xush kelibsiz, Foydalanuvchi"
   "Login yoki parol xato"
   ```

7. **Fasl aniqlovchi**
   ```javascript
   Shart: Oy raqamiga qarab, qaysi fasl ekanligini aniqlang.

   Test qiymatlari:
   oy = 1
   oy = 4
   oy = 7
   oy = 10

   Kutilgan natijalar:
   "Qish"
   "Bahor"
   "Yoz"
   "Kuz"
   ```

8. **Raqamni so'zga o'girish**
   ```javascript
   Shart: 1 dan 5 gacha bo'lgan raqamni so'z bilan yozing

   Test qiymatlari:
   raqam = 1
   raqam = 3
   raqam = 7

   Kutilgan natijalar:
   "bir"
   "uch"
   "noto'g'ri raqam"
   ```

9. **Baho tavsifi**
   ```javascript
   Shart: Bahoga qarab tavsif bering:
   5 - "A'lo"
   4 - "Yaxshi"
   3 - "Qoniqarli"
   2 - "Qoniqarsiz"
   1 - "Yomon"

   Test qiymatlari:
   baho = 5
   baho = 3
   baho = 0

   Kutilgan natijalar:
   "A'lo"
   "Qoniqarli"
   "Noto'g'ri baho"
   ```

10. **Yil fasllari**
    ```javascript
    Shart: Fasl nomiga qarab, shu faslga tegishli oylarni qaytaring

    Test qiymatlari:
    fasl = "qish"
    fasl = "yoz"
    fasl = "kecha"

    Kutilgan natijalar:
    "Dekabr, Yanvar, Fevral"
    "Iyun, Iyul, Avgust"
    "Bunday fasl yo'q"
    ```

11. **Son tavsifi**
    ```javascript
    Shart: Sonni tekshiring:
    - Musbat yoki manfiy
    - Juft yoki toq
    Ternary operatordan foydalaning

    Test qiymatlari:
    son = 4
    son = -3
    son = 0

    Kutilgan natijalar:
    "Musbat juft son"
    "Manfiy toq son"
    "Nol"
    ```

12. **Rang kodi**
    ```javascript
    Shart: Rangning nomiga qarab, uning kodini qaytaring:
    qizil -> #FF0000
    yashil -> #00FF00
    ko'k -> #0000FF

    Test qiymatlari:
    rang = "qizil"
    rang = "yashil"
    rang = "qora"

    Kutilgan natijalar:
    "#FF0000"
    "#00FF00"
    "Bunday rang kodi yo'q"
    ```

Izohlar:
1. Har bir mashqni uch xil usulda yechish mumkin:
   - if...else
   - ternary operator
   - switch case

2. Mashqlarni bajarishda:
   - Kodingiz tushunarli bo'lishi
   - Barcha holatlar tekshirilishi
   - Xatolar to'g'ri qayta ishlanishi kerak

3. O'quvchilar uchun qo'shimcha vazifalar:
   - Har bir masalani kamida ikki xil usulda yeching
   - O'z test holatlaringizni qo'shing
   - Xatolarni qayta ishlashni takomillashtiring
