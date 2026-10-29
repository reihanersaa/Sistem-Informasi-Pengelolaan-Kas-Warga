# 📊 Project Roadmap & WBS Level 3

Berikut adalah visualisasi jadwal perkembangan proyek berdasarkan WBS Level 3 menggunakan Gantt Chart.

```mermaid
gantt
title Jadwal Pelaksanaan Proyek
dateFormat  YYYY-MM-DD
axisFormat  %d-%b
section Fase 1: Analisis
Analisis Kebutuhan Sistem (WBS 1.1) :active, task1, 2026-11-02, 4d
Desain UI/UX Halaman Utama (WBS 1.2) : task2, after task1, 3d
section Fase 2: Pengembangan
Setup Database & Arsitektur (WBS 2.1) : task3, after task1, 5d
Implementasi API Backend (WBS 2.2)    : task4, after task3, 6d
Integrasi Front-End & Back-End (WBS 2.3) : task5, after task2 task4, 4d
section Fase 3: Pengujian
Manual & Automation Testing (WBS 3.1) : task6, after task5, 4d
Deployment ke Production (WBS 3.2)    : milestone, task7, after task6, 0d
   ```
