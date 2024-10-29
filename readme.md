# การใช้งาน Vue.js เบื้องต้น

## โครงสร้างโปรเจกต์

```
.
├── my_vue.html
└── README.md
```

## ฟีเจอร์

- การแสดงข้อความผ่าน Data Binding ด้วย `{{ }}`
- การจัดการข้อมูลผ่าน Options API ของ Vue.js

## ตัวอย่างโค้ด

โค้ดหลักในการสร้าง Vue Instance:

```javascript
const app = Vue.createApp({
    data() {
        return {
            message: 'Hello, vue.js',
            name: 'jetsada tonsri'
        }
    }
}).mount('#app')
```

## วิธีการรัน

1. เปิดไฟล์ `my_vue.html` ในเบราว์เซอร์
2. จะเห็นข้อความ "Hello, vue.js" และ "jetsada tonsri" แสดงบนหน้าเว็บ
