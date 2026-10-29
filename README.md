library-management-system/
├── backend-spring/             # Java 17+ / Spring Boot
│   ├── pom.xml
│   └── src/main/
│       ├── java/com/library/
│       │   ├── config/
│       │   ├── common/
│       │   ├── entity/
│       │   ├── repository/
│       │   ├── service/
│       │   └── controller/
│       └── resources/
│           ├── application.yml
│           └── application-mail.yml
│
├── frontend-student/           # TV2: giao diện sinh viên
│   ├── package.json
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── services/
│       ├── App.jsx
│       └── main.jsx
│
├── frontend-admin/             # TV5 + phần QR của TV4
│   ├── package.json
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── services/
│       ├── App.jsx
│       └── main.jsx
│
├── database/
│   ├── schema.sql              # Tạo bảng MySQL
│   └── seed.sql                # Dữ liệu mẫu
│
├── docs/
│   ├── PHAN_CONG_CONG_VIEC.md
│   ├── USE_CASE.md
│   ├── QUY_TRINH_MUON_TRA.md
│   ├── API_DOCUMENTATION.md
│   └── TEST_CASES.md
│
├── .gitignore
└── README.md
