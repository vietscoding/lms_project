# Structure of the Website

VietLMS
├── resources/views/                      # Tệp giao diện (Blade: .blade.php)
│   ├── layouts/                         # Layout chính
│   │   └── app.blade.php                # Layout chung (nav, footer)
│   ├── auth/                            # Module Authentication
│   │   ├── login.blade.php              # Form đăng nhập
│   │   └── register.blade.php           # Form đăng ký
│   ├── dashboard/                       # Module Dashboard
│   │   ├── admin/                       # Dashboard cho Quản trị
│   │   │   ├── index.blade.php          # Trang chính admin
│   │   │   ├── users.blade.php          # Quản lý người dùng
│   │   │   └── courses.blade.php        # Quản lý khóa học
│   │   ├── teacher/                     # Dashboard cho Giáo viên
│   │   │   ├── index.blade.php          # Trang chính giáo viên
│   │   │   ├── courses.blade.php        # Quản lý khóa học cá nhân
│   │   │   └── assessments.blade.php    # Quản lý bài kiểm tra
│   │   └── student/                     # Dashboard cho Học sinh
│   │       ├── index.blade.php          # Trang chính học sinh
│   │       ├── courses.blade.php        # Danh sách khóa học
│   │       ├── progress.blade.php       # Tiến độ học tập
│   │       └── discussions.blade.php    # Diễn đàn thảo luận
│   ├── search/                          # Module Tìm kiếm
│   │   └── index.blade.php              # Trang tìm kiếm
│   └── settings/                        # Module Cài đặt
│       ├── profile.blade.php            # Hồ sơ cá nhân
│       └── system.blade.php             # Cài đặt hệ thống (Admin)
├── public/                              # Tệp tĩnh (CSS, JS, images)
│   ├── css/app.css                      # CSS (Bootstrap hoặc custom)
│   ├── js/app.js                        # JavaScript (tương tác frontend)
│   └── images/                          # Hình ảnh (logo, banner)
├── app/Http/Controllers/                 # Logic backend (PHP)
│   ├── AuthController.php               # Xử lý đăng nhập/đăng ký
│   ├── CourseController.php             # Quản lý khóa học
│   ├── AssessmentController.php         # Quản lý bài kiểm tra
│   ├── DiscussionController.php         # Quản lý diễn đàn
│   └── UserController.php               # Quản lý người dùng
├── routes/web.php                       # Định tuyến (PHP)
├── database/migrations/                 # Cấu trúc cơ sở dữ liệu (PHP)
│   ├── create_users_table.php           # Bảng users
│   ├── create_courses_table.php         # Bảng courses
│   ├── create_assessments_table.php     # Bảng assessments
│   └── create_discussions_table.php     # Bảng discussions
└── .env                                 # Cấu hình (DB, app settings)