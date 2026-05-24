# iot-api-homework
fun project using JSON
# Smart Water Reminder System

ეს არის IoT სისტემა რომელიც ადამიანს ახსენებს წყლის დალევას.

## Components
- ESP32
- RTC Clock
- LED
- Buzzer
- Water Sensor

## API
GET /water/status
POST /water/drink
POST /device/reminder

## Purpose
ჯანმრთელობის გაუმჯობესება და წყლის მიღების კონტროლი
magaria tan dzaan Smart Lock არის ჭკვიანი საკეტის სისტემა, რომელიც აკონტროლებს კარის დაბლოკვის მდგომარეობას, ბატარეის დონეს და ავტორიზებულ მომხმარებლებს.

მონაცემები: Device Name: Smart Lock Battery Level: 91% Lock Status: Locked Authorized Users: Giorgi, Nika, Ana

JSON მონაცემის მაგალითი: { "device": "Smart Lock", "battery": 91, "isLocked": true, "users": ["Giorgi", "Nika", "Ana"] }

ფუნქციები:

საკეტის სტატუსის შემოწმება ბატარეის დონის მონიტორინგი ავტორიზებული მომხმარებლების მართვა მონაცემების JSON ფორმატში შენახვა

გამოყენება: ეს სისტემა გამოიყენება ჭკვიან სახლებში, ოფისებში და IoT უსაფრთხოების პროექტებში.

ტექნოლოგიები: Python, JSON, IoT Devices
