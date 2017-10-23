# Implementasi PAAS
- masuk ke web Heroku lalalu lakukan pendaftaran akun
- install Heroku
- sudo add-apt-repository "deb https://cli-assets.heroku.com/branches/stable/apt ./"

- curl -L https://cli-assets.heroku.com/apt/release.key | sudo apt-key add -

- sudo apt-get update

- sudo apt-get install heroku
- heroku login (digunakan untuk login akun heroku)
- php -v (digunakan untuk cek versi php)
- composer -V (karena belum install langsung install saja menggunakan install  )
- git --version (karena sudah pasang git di ubuntu jadi tinggal cek saja)
- git clone https://github.com/heroku/php-getting-started.git (download isi file dari heroku, langsung saja ikuti karena belum membuat aplikasi)

- cd php-getting-started (masuk ke dalam folder dari file git yang sudah di download)
- heroku create (membuat file heroku di dalam folder php-getting-started hala ini digunakan agar saat isi file di deploy ke heroku terdeteksi)
- git push heroku master (deploy seluruh isi file kedalam heroku)
- heroku ps:scale web=1 (belum jelas fungsi nya)
-heroku open (membuka hasil kerja yang sudah dibuat)
