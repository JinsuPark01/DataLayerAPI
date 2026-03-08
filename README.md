## 🏋️ Squat Counter (Wear OS)

### 📌 Overview
Wear OS 스마트워치의 센서를 활용해 사용자의 스쿼트 횟수를 측정하고  
측정 데이터를 스마트폰 앱으로 전송하는 피트니스 보조 애플리케이션.

### 🛠 Tech Stack
- Android (Kotlin)
- Wear OS
- SensorManager
- Android Data Layer API
- JSON Serialization

### ⚙️ Key Features
- Wear OS 워치의 **가속도계 / 자이로 센서**를 활용한 스쿼트 동작 감지
- 센서 데이터를 기반으로 **스쿼트 횟수 자동 측정**
- **Android Data Layer API**를 이용해 워치 → 스마트폰 데이터 전송

### 💡 Implementation Highlights
- `SensorManager`를 활용한 **실시간 센서 데이터 처리**
- Wear OS ↔ Android 간 **Data Layer 기반 통신 구조 구현**
- `WorkoutData` 객체를 **JSON 직렬화**하여 운동 데이터 전달
