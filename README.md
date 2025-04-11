# Funksiyalar va objectlar bilan ishlash mashqlari

Random son yaratish Math.random() orqali qilinadi

## 1. O'yin Personaji ðŸŽ®

```javascript
/* Shart: O'yin qahramonini yaratuvchi funksiya tuzing.
Funksiya personajning ismi va kuchini qabul qilsin,
darajasi esa random (1-10) bo'lsin */

Test: createCharacter("Thanos", 100)
Kutilgan natija:
{
    name: "Thanos",
    power: 100,
    level: 7,
    info: "7-darajali Thanos, kuchi: 100"
}
```

## 2. Instagram Post ðŸ“±

```javascript
/* Shart: Post yaratuvchi funksiya tuzing.
Funksiya rasm linkini, sarlavhani va teglarni qabul qilsin.
Like va ko'rishlar soni random bo'lsin (0-1000) */

Test: createPost("photo.jpg", "Bugun zo'r kun", ["fun", "holiday"])
Kutilgan natija:
{
    image: "photo.jpg",
    title: "Bugun zo'r kun",
    tags: ["fun", "holiday"],
    likes: 234,
    views: 756
}
```

## 3. Pizza Buyurtma ðŸ•

```javascript
/* Shart: Pitsa buyurtma qilish funksiyasi tuzing.
Funksiya pitsa o'lchami va qo'shimchalarni qabul qilsin.
Narx o'lcham va qo'shimchalarga qarab hisoblansin */

Test: orderPizza("medium", ["cheese", "tomato"])
Kutilgan natija:
{
    size: "medium",
    toppings: ["cheese", "tomato"],
    price: 65000,
    time: "20 daqiqa"
}
```

## 4. Telegram Bot ðŸ¤–

```javascript
/* Shart: Telegram bot yaratuvchi funksiya tuzing.
Bot foydalanuvchi yuborgan xabarni tekshirib,
agar so'roq bo'lsa "Ha" yoki "Yo'q", boshqa holatlarda
"Tushunmadim" deb javob bersin */

Test: botReply("Bugun havo yaxshimi?")
Kutilgan natija:
{
    message: "Bugun havo yaxshimi?",
    reply: "Ha",
    time: "12:30"
}
```

## 5. YouTube Video ðŸŽ¥

```javascript
/* Shart: YouTube video ma'lumotlarini qaytaruvchi funksiya tuzing.
Funksiya video nomini va davomiyligini qabul qilsin.
Ko'rishlar soni va like/dislike random bo'lsin */

Test: createVideo("JavaScript Tutorial", "10:15")
Kutilgan natija:
{
    title: "JavaScript Tutorial",
    duration: "10:15",
    views: 15600,
    likes: 2300,
    dislikes: 150
}
```

## 6. Spotify Track ðŸŽµ

```javascript
/* Shart: Spotify treki yaratuvchi funksiya tuzing.
Funksiya qo'shiq nomi va ijrochisini qabul qilsin.
Tinglashlar soni random (1000-100000) bo'lsin */

Test: createTrack("Shape of You", "Ed Sheeran")
Kutilgan natija:
{
    title: "Shape of You",
    artist: "Ed Sheeran",
    listens: 45678,
    duration: "3:54",
    isPopular: true  // agar tinglashlar > 50000 bo'lsa
}
```

## 7. Film Rating ðŸŽ¬

```javascript
/* Shart: Film reytingini hisoblovchi funksiya tuzing.
Funksiya film haqidagi ma'lumotlar va foydalanuvchilar
bahosini qabul qilsin */

Test: rateMovie("Avatar", 2009, [9, 8, 10, 7, 9])
Kutilgan natija:
{
    title: "Avatar",
    year: 2009,
    ratings: [9, 8, 10, 7, 9],
    averageRating: 8.6,
    status: "Ajoyib"  // rating > 8 bo'lsa
}
```

## 8. Git Commit ðŸ’»

```javascript
/* Shart: Git commit yaratuvchi funksiya tuzing.
Funksiya commit xabari va fayllar ro'yxatini qabul qilsin */

Test: createCommit("Add new features", ["app.js", "style.css"])
Kutilgan natija:
{
    message: "Add new features",
    files: ["app.js", "style.css"],
    date: "2024-03-15",
    id: "a1b2c3d4",  // random string
    author: "User"
}
```

## 9. Online Do'kon ðŸ›ï¸

```javascript
/* Shart: Online do'kon mahsulotini yaratuvchi funksiya tuzing.
Funksiya mahsulot nomi va narxini qabul qilsin.
Chegirma random (0-30%) bo'lsin */

Test: createProduct("iPhone 15", 999)
Kutilgan natija:
{
    name: "iPhone 15",
    price: 999,
    discount: 15,
    finalPrice: 849,
    isAvailable: true
}
```

## 10. Weather App â›…

```javascript
/* Shart: Ob-havo ma'lumotlarini qaytaruvchi funksiya tuzing.
Funksiya shahar nomini va haroratni qabul qilsin.
Namlik va shamol tezligi random bo'lsin */

Test: getWeather("Tashkent", 25)
Kutilgan natija:
{
    city: "Tashkent",
    temperature: 25,
    humidity: 45,
    windSpeed: 8,
    status: "Quyoshli"  // haroratga qarab aniqlansin
}
```

## 11. User Profile ðŸ‘¤

```javascript
/* Shart: Foydalanuvchi profilini yaratuvchi funksiya tuzing.
Funksiya ism va yoshni qabul qilsin.
Avatar rasmi random tanlansin */

Test: createProfile("Alex", 25)
Kutilgan natija:
{
    name: "Alex",
    age: 25,
    avatar: "avatar3.png",
    joinDate: "2024-03-15",
    status: "online"
}
```

## 12. Car Info ðŸš—

```javascript
/* Shart: Mashina haqida ma'lumot beruvchi funksiya tuzing.
Funksiya model va yilni qabul qilsin.
Narx modelga qarab aniqlansin */

Test: getCarInfo("Tesla Model 3", 2023)
Kutilgan natija:
{
    model: "Tesla Model 3",
    year: 2023,
    price: 45000,
    color: "white",
    isElectric: true
}
```

## 13. Restaurant Menu ðŸ½ï¸

```javascript
/* Shart: Restoran menyu elementini yaratuvchi funksiya tuzing.
Funksiya taom nomi va narxini qabul qilsin.
Tayyorlash vaqti random (10-60 daqiqa) bo'lsin */

Test: createMenuItem("Osh", 45000)
Kutilgan natija:
{
    name: "Osh",
    price: 45000,
    prepTime: 25,
    category: "main",
    isSpicy: false
}
```

## 14. Sport Match âš½

```javascript
/* Shart: Sport o'yini natijasini yaratuvchi funksiya tuzing.
Funksiya ikki jamoa nomini va hisobni qabul qilsin */

Test: createMatch("Real Madrid", "Barcelona", "2:1")
Kutilgan natija:
{
    team1: "Real Madrid",
    team2: "Barcelona",
    score: "2:1",
    winner: "Real Madrid",
    duration: "90 min",
    stadium: "Santiago Bernabeu"
}
```
