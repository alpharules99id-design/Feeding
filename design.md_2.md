# Dairy Feeding Management System
## Design Document

## 1. Tujuan
Aplikasi untuk mengelola proses feeding sapi perah mulai dari Loader hingga Reporting.

---

## 2. Struktur Menu

Dashboard
Loader
Mixing
Distribution
Monitoring
Warehouse
Inventory
KPI
Analytics
History
Reports
User Management
Settings

---

## 3. User Role

### Admin
- Kelola User
- Semua akses

### Supervisor
- Dashboard
- Monitoring
- KPI
- Report

### Operator Loader
- Input Loader

### Operator Mixer
- Mixing

### Operator Distribusi
- Distribution

---

## 4. Warna

Primary : #1976D2
Success : #4CAF50
Warning : #FFC107
Danger : #F44336

Background : #F5F5F5

---

## 5. Dashboard

Card
- Total Batch Hari Ini
- Sedang Mixing
- Sedang Distribusi
- Selesai
- Keterlambatan

Chart
- Mixing Time
- Feed Usage
- Waste

---

## 6. Loader

Input

Tanggal
Shift
Operator
Pen
Recipe
Tonase Awal
Tonase Setelah Molases
Status

Button
Save
Cancel

---

## 7. Mixing

Menampilkan
- Batch Queue
- Countdown Timer
- Status
- Berangkat

---

## 8. Distribution

Menampilkan
- Truck
- Driver
- Pen Tujuan
- ETA
- Status

---

## 9. Monitoring

Realtime

🟢 Idle
🟡 Mixing
🔵 OTW
🟣 Distribution
✅ Finish

---

## 10. Warehouse

Stock Bahan
FIFO
Expiry
Minimum Stock

---

## 11. KPI

Loader Accuracy
Mixing Time
Distribution Delay
Feed Waste
Operator Performance

---

## 12. Database

Users
Feed_Batch
Loader
Mixer
Distribution
Warehouse
Inventory
History

---

## 13. Flow

Loader
↓
Mixing
↓
Distribution
↓
Monitoring
↓
History
↓
Report