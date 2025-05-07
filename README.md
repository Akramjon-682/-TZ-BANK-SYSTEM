# TZ-BANK-SYSTEM

banking_system/
│
├── schema/                     # Barcha jadvallarni yaratish kodi shu yerda
│   └── __init__.py             # Hamma jadval klasslari shu faylda bo'ladi
│
├── data_gen/                  # Ma'lumot generatsiyasi (200 tadan har bir jadval uchun)
│   └── generate_data.py
│
├── kpi/                       # Har bir KPI uchun alohida fayl
│   ├── total_users.py
│   ├── vip_users.py
│   ├── suspicious_transactions.py
│   ├── avg_transaction_amount.py
│   └── ...
│
├── utils/                     # Qo‘shimcha foydali funksiyalar
│   └── db.py                  # Ma’lumotlar bazasi bilan ishlash (SQLAlchemy)
│
├── run.py                     # Loyihani ishga tushuruvchi fayl
└── requirements.txt           # Kerakli kutubxonalar ro‘yxati
