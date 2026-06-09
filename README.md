<<<<<<< Updated upstream
# 🎮 PRU213 - C# Programming & Unity | Lab 01

![Unity](https://img.shields.io/badge/Unity-100000?style=for-the-badge&logo=unity&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

Chào mừng bạn đến với kho lưu trữ (repository) cho **Lab 01** thuộc môn học **PRU213**. Đây là sản phẩm thực hành của **Nhóm 06**.

## 👥 Thành viên Nhóm 06

| STT | Họ và Tên | MSSV | Vai trò |
| :---: | :--- | :---: | :--- |
| 1 | **Nguyễn Tiến Thành** | `HE186221` | Thành viên |
| 2 | **Phạm Hiền Tâm** | `HE182476` | Thành viên |
| 3 | **Trần Quốc Trung Hiếu** | `HE182395` |  Team Leader |
| 4 | **Phạm Việt Hưng** | `HE161180` | Thành viên |
| 5 | **Cao Đức Quang Anh** | `HE180227` | Thành viên |

---

## 📝 Thông tin dự án
* **Môn học:** PRU213 - C# Programming & Unity
* **Bài tập:** Lab 01
* **Giảng viên hướng dẫn:** `Mai Ngọc Lương`

**Mục tiêu của Lab:**
> *[Ghi chú ngắn gọn về các tính năng C# hoặc component Unity mà nhóm đã thực hành trong Lab này. Ví dụ: Làm quen với giao diện Unity, tạo script C# cơ bản để di chuyển nhân vật, v.v.]*

## 📁 Cấu trúc thư mục

Dự án được xây dựng trên nền tảng Unity 3D/2D, bao gồm các thư mục cốt lõi:
- 📂 `Assets/`: Chứa toàn bộ tài nguyên của dự án (Scripts C#, Scenes, Prefabs, Materials,...).
- 📂 `Packages/`: Các thư viện và packages phụ thuộc của Unity.
- 📂 `ProjectSettings/`: Các cấu hình thiết lập môi trường cho project.

## ⚙️ Hướng dẫn cài đặt & Chạy dự án

1. Clone repository này về máy tính của bạn:
   ```bash
   git clone [https://github.com/NguyenTienThanh22/Lab-1.git](https://github.com/NguyenTienThanh22/Lab-1.git)
=======
# Tower Defense Lab 1 - Group 06

## 📋 Thông Tin Dự Án

**Tên dự án:** Tower Defense Game - Map 1  
**Nhóm:** GR06  
**Môn học:** Game Development  
**Engine:** Unity 6000.4.6f1  
**Ngôn ngữ:** C#

---

## 🎮 Giới Thiệu

Đây là dự án Lab 1 xây dựng game Tower Defense 2D cơ bản với các tính năng chiến thuật phòng thủ kinh điển. Người chơi sẽ đặt các tháp (Heroes) để tiêu diệt các làn sóng quái vật (Enemies) trước khi chúng đến cuối đường.

---

## 🎯 Mục Tiêu Lab

- Xây dựng hệ thống game Tower Defense hoàn chỉnh
- Triển khai cơ chế spawn enemies theo waves
- Thiết kế hệ thống tháp với AI tự động bắn
- Quản lý tài nguyên và điểm sống
- Tạo các loại quái vật với kỹ năng đặc biệt

---

## ✨ Tính Năng Chính

### 🏰 Hệ Thống Tháp (Heroes)
- **Đặt tháp:** Người chơi có thể đặt tháp tại các vị trí Platform được định sẵn
- **Tự động tấn công:** Tháp tự động tìm và bắn quái gần nhất trong tầm
- **Hệ thống đạn:** Sử dụng Object Pooling để tối ưu hiệu suất
- **Range tùy chỉnh:** Mỗi loại tháp có tầm bắn và sát thương khác nhau
- **Animation:** Hiệu ứng hoạt hình khi tháp tấn công
- **Âm thanh:** Âm thanh riêng cho mỗi đợt tấn công

### 👾 Hệ Thống Quái (Enemies)

#### Quái Thường
- Di chuyển theo đường đi (Waypoint System)
- Thanh máu hiển thị trực quan
- Trao thưởng tài nguyên khi bị tiêu diệt

#### Quái Đặc Biệt - Kỹ Năng Boss

1. **Giáp Mỏng** (Thin Armor)
   - Nhận nhiều sát thương hơn từ tháp bắn xa
   - Buff damage +20% khi khoảng cách > 3 đơn vị

2. **Nhanh Nhẹn** (Agility)
   - 20% tỉ lệ né đòn đánh đầu tiên
   - Cơ chế dodge thông minh

3. **Nổi Giận** (Rage)
   - Tăng tốc gấp đôi khi máu < 50%
   - Trở nên nguy hiểm hơn khi bị thương

4. **Phân Chia** (Division)
   - Định kỳ sinh ra 2 Slime nhỏ phía sau
   - Spawn thêm 2 Slime khi bị tiêu diệt
   - Lính nhỏ kế thừa đường đi của Boss

### 🎲 Game Mechanics

- **Hệ thống sóng:** Quái xuất hiện theo waves với độ khó tăng dần
- **Tài nguyên:** Thu thập gold từ quái để xây tháp
- **Điểm sống:** Mất máu khi quái đến cuối đường
- **Speed Control:** Điều chỉnh tốc độ game (1x, 2x)
- **Object Pooling:** Tái sử dụng đối tượng để tối ưu performance

---

## 🗂️ Cấu Trúc Dự Án

```
TowerDefense_Lab1_GR06/
├── TowerDefense_Lab1/
│   ├── Assets/
│   │   ├── Asset_map_1/
│   │   │   ├── Art/                    # Sprites, textures
│   │   │   ├── Asset/                  # Quái, tháp, map assets
│   │   │   ├── Prefabs/               # Enemy, Hero, UI prefabs
│   │   │   ├── ScriptableObjects/     # Data configs
│   │   │   ├── Scripts/
│   │   │   │   ├── Enemy_Map1/        # Enemy logic
│   │   │   │   ├── Hero_Map1/         # Tower logic
│   │   │   │   └── Utils_Map1/        # Game managers
│   │   │   ├── Scene/                 # Game scenes
│   │   │   └── Settings/              # URP, Render settings
│   │   ├── LevelPlay/                 # IronSource SDK
│   │   └── Resources/
│   └── ProjectSettings/
└── README.md
```

---

## 🔧 Các Script Chính

| Script | Chức năng |
|--------|-----------|
| `GameManager_Map1.cs` | Quản lý game state, resources, lives |
| `Enemy_Map1.cs` | Logic quái vật, di chuyển, kỹ năng |
| `Hero_Map1.cs` | Logic tháp, tìm target, bắn đạn |
| `Spawner_Map1.cs` | Spawn enemies theo waves |
| `Path_Map1.cs` | Hệ thống waypoint |
| `Platform_Map1.cs` | Vị trí đặt tháp |
| `Projectile_Map1.cs` | Logic đạn bay |
| `UIController_Map1.cs` | Cập nhật UI |
| `ObjectPooler_Map1.cs` | Object pooling system |
| `LevelManager.cs` | Quản lý levels |

---

## 🎨 Assets

- **2D Sprites:** Tower Defense Basic, Health Bar, UI Elements
- **Background:** Map Level 1, Home Screen
- **Audio:** Background music, attack sounds
- **TextMesh Pro:** Hệ thống font hiện đại

---

## 🚀 Hướng Dẫn Chạy

1. **Yêu cầu:**
   - Unity Editor 6000.4.6f1 hoặc cao hơn
   - TextMesh Pro package
   - Universal Render Pipeline (URP)

2. **Các bước:**
   ```bash
   # Clone repository
   git clone https://github.com/your-username/TowerDefense_Lab1_GR06.git
   
   # Mở project trong Unity Hub
   # Chọn thư mục: TowerDefense_Lab1_GR06/TowerDefense_Lab1
   
   # Mở scene MainMenu.unity hoặc Game_Map1.unity
   # Nhấn Play
   ```

3. **Scenes:**
   - `MainMenu.unity` - Menu chính
   - `Game_Map1.unity` - Gameplay map 1

---

## 🎮 Cách Chơi

1. Bắt đầu với tài nguyên ban đầu (500 gold) và 5 mạng
2. Chọn loại tháp từ UI
3. Click vào Platform (vị trí xanh lục) để đặt tháp
4. Tháp sẽ tự động bắn quái trong tầm
5. Thu thập gold từ quái bị tiêu diệt
6. Xây thêm tháp để chống các wave mạnh hơn
7. Game over khi hết mạng

---

## 🛠️ Công Nghệ Sử Dụng

- **Unity 6000.4** - Game Engine
- **C#** - Ngôn ngữ lập trình
- **Universal Render Pipeline (URP)** - Render pipeline
- **TextMesh Pro** - Advanced text rendering
- **Unity Input System** - Input handling
- **ScriptableObjects** - Data-driven design
- **Object Pooling** - Performance optimization
- **Event System** - Decoupled architecture

---

## 📊 Design Patterns

- **Singleton Pattern:** GameManager, LevelManager
- **Object Pool Pattern:** Projectiles, Enemies
- **Observer Pattern:** Event-driven communication
- **ScriptableObject Pattern:** Data configuration
- **Component Pattern:** Modular game objects

---

## 👥 Thành Viên Nhóm

Group 06 - Tower Defense Team

---

## 📝 Ghi Chú

- Project sử dụng IronSource LevelPlay SDK (có thể dùng cho ads sau này)
- Universal Render Pipeline được cấu hình cho 2D
- Đã tối ưu với Object Pooling
- Hỗ trợ multiple resolutions

---

## 📜 License

Educational project - For learning purposes only

---

## 🔮 Kế Hoạch Tương Lai

- [ ] Thêm nhiều loại tháp
- [ ] Thêm map mới
- [ ] Hệ thống upgrade tháp
- [ ] Power-ups và special abilities
- [ ] Leaderboard system
- [ ] Mobile build optimization

---

**Phát triển bởi Group 06 | Game Development Lab 1**
>>>>>>> Stashed changes
