# telco_customer_churn_analysis_using_power_BI

dataset yang saya gunakan adalah telco_customer_churn, yang saya peroleh dari kaggle  
link: kaggle.com/datasets/blastchar/telco-customer-churn  

raw dataset:  
| **Kolom**          | **Tipe Data**                                                         | **Deskripsi / Makna Bisnis**                                                                              |
| ------------------ | --------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- |
| `customerID`       | String                                                                | ID unik untuk setiap pelanggan.                                                                           |
| `gender`           | Kategori (Male/Female)                                                | Jenis kelamin pelanggan.                                                                                  |
| `SeniorCitizen`    | Numerik (0 atau 1)                                                    | Status usia lanjut: 1 = pelanggan lansia (biasanya ≥ 65 tahun), 0 = bukan.                                |
| `Partner`          | Kategori (Yes/No)                                                     | Apakah pelanggan memiliki pasangan hidup. Bisa memengaruhi stabilitas pelanggan.                          |
| `Dependents`       | Kategori (Yes/No)                                                     | Apakah pelanggan memiliki tanggungan (anak/orang tua). Biasanya pelanggan dengan tanggungan lebih stabil. |
| `tenure`           | Numerik (bulan)                                                       | Lama pelanggan berlangganan, dalam satuan bulan.                                                          |
| `PhoneService`     | Kategori (Yes/No)                                                     | Apakah pelanggan menggunakan layanan telepon.                                                             |
| `MultipleLines`    | Kategori (Yes/No/No phone service)                                    | Apakah pelanggan memiliki lebih dari satu jalur telepon.                                                  |
| `InternetService`  | Kategori (DSL/Fiber optic/No)                                         | Jenis layanan internet yang digunakan pelanggan.                                                          |
| `OnlineSecurity`   | Kategori (Yes/No/No internet service)                                 | Apakah pelanggan menggunakan layanan keamanan online tambahan.                                            |
| `OnlineBackup`     | Kategori (Yes/No/No internet service)                                 | Apakah pelanggan menggunakan layanan backup online.                                                       |
| `DeviceProtection` | Kategori (Yes/No/No internet service)                                 | Apakah pelanggan menggunakan layanan perlindungan perangkat.                                              |
| `TechSupport`      | Kategori (Yes/No/No internet service)                                 | Apakah pelanggan menggunakan dukungan teknis tambahan.                                                    |
| `StreamingTV`      | Kategori (Yes/No/No internet service)                                 | Apakah pelanggan menggunakan layanan streaming TV.                                                        |
| `StreamingMovies`  | Kategori (Yes/No/No internet service)                                 | Apakah pelanggan menggunakan layanan streaming film.                                                      |
| `Contract`         | Kategori (Month-to-month / One year / Two year)                       | Jenis kontrak berlangganan pelanggan.                                                                     |
| `PaperlessBilling` | Kategori (Yes/No)                                                     | Apakah pelanggan menerima tagihan tanpa kertas (digital).                                                 |
| `PaymentMethod`    | Kategori (Electronic check, Mailed check, Bank transfer, Credit card) | Metode pembayaran pelanggan.                                                                              |
| `MonthlyCharges`   | Numerik (USD)                                                         | Jumlah biaya bulanan yang dibayarkan pelanggan.                                                           |
| `TotalCharges`     | Numerik (USD)                                                         | Total biaya yang telah dibayarkan pelanggan sejak berlangganan.                                           |
| `Churn`            | Kategori (Yes/No)                                                     | Target utama: apakah pelanggan berhenti berlangganan (*Yes* = churn, *No* = tetap).                       |


## Data Cleaning
