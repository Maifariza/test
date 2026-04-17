lib/
│
├── main.dart                
│
├── models/                   
│   ├── user.dart
│   ├── event.dart
│   ├── attendance.dart
│   ├── gallery.dart
│   ├── kas.dart
│   └── division.dart
│
├── controllers/               
│   ├── auth_provider.dart
│   ├── event_provider.dart
│   ├── attendance_provider.dart
│   ├── gallery_provider.dart
│   ├── kas_provider.dart
│   ├── member_provider.dart
│   └── theme_provider.dart
│
├── services/                
│   ├── auth_service.dart
│   ├── event_service.dart
│   ├── attendance_service.dart
│   ├── gallery_service.dart
│   ├── kas_service.dart
│   └── member_service.dart
│
├── pages/                    # Semua UI
│   ├── home_page.dart
│   ├── login_page.dart
│   ├── register_page.dart
│
│   ├── event_page.dart
│   ├── event_detail_page.dart
│   ├── event_form_page.dart
│
│   ├── attendance_page.dart
│   ├── attendance_history_page.dart
│
│   ├── gallery_page.dart
│
│   ├── kas_page.dart
│   ├── kas_form_page.dart
│
│   ├── member_page.dart
│   ├── member_detail_page.dart
│
│   └── profile_page.dart
│
└── widgets/                  # Komponen reusable
    ├── event_card.dart
    ├── gallery_card.dart
    ├── member_card.dart
    ├── loading_skeleton.dart
    └── empty_state.dart
