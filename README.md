# AIRNOLOGY-23

## Preprocessing Plan Sementara
- `datetime` : buang (redundant)
- `datetime_iso` : dipisah pisah? terutama cari bulannya. Cari tau dibulan apa curah hujan paling tinggi
- `time-zone` : buang (soalnya sama semua keknya)
- `temp` : dijadiin float, cek juga ada yg beda nggak unitnya
- `visibility` : coba cari tau unique val nya apa aja, kalo cuma dikit mending dibikin kategorikal
- `d_point` : dijadiin float, cek juga ada yg beda nggak unitnya
- `feels` : dijadiin float, cek juga ada yg beda nggak unitnya
- `min_temp` : dijadiin float, cek juga ada yg beda nggak unitnya
- `max_temp` : dijadiin float, cek juga ada yg beda nggak unitnya
- `pressure` : dijadiin float, cek juga ada yg beda nggak unitnya
- `sea_level` : coba cari tau unique val nya apa aja, kalo cuma dikit mending dibikin kategorikal
- `grnd_level` : coba cari tau unique val nya apa aja, kalo cuma dikit mending dibikin kategorikal
- `hum` : cari tau kenapa ada yg diatas 100%
- `wind_spd` : dijadiin float, cek juga ada yg beda nggak unitnya
- `wind_deg` : dijadiin float, cek juga ada yg beda nggak unitnya
- `rain_3h` : cari tau korelasinya sama `rain_1h`. hipotesis: kalo `rain_3h` itu 0, kemungkinan besar `rain_1h` juga 0
- `snow_1h` : cari tau korelasinya sama `rain_1h`
- `snow_3h` : cari tau korelasinya sama `rain_1h`
- `clouds` : cari tau korelasinya sama `rain_1h`
- `rain_1h` : seragamin aja