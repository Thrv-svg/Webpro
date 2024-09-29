<!DOCTYPE html>
<html>
<head>
    <title>Profil Pribadi</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
x
        .container {
            display: flex;
        }

        .column {
            flex: 50%;
        }

        .profile-image {
            width: 200px;
            height: 300px;
            background-color: #ccc;
            margin-right: 5px;
        }

        .video {
            width: 60%;
            height: 200px;
            background-color: #000;
            margin-left: -560px;
            margin-top: 45px;
        }

        .full-width {
            width: 100%;
        }

        .skills {
            margin-top: 20px;
        }

        .contact {
            margin-top: 20px;
        }

        .social-media {
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <h1>Profil Pribadi</h1>

    <div class="container">
        <!-- div: Mengelompokkan elemen untuk tata letak -->
        <div class="column">
            <img src="Profile.jpg" alt="Foto Profil" class="profile-image">
            <!-- img: Menampilkan gambar pada halaman -->
        </div>
        <div class="column">
            <video class="video" controls>
                <source src="video_perkenalan.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
            <!-- video: Menampilkan dan memutar video -->
        </div>
    </div>

    <h2>Tentang Saya</h2>
    <p>Halo! Saya adalah seorang pengembang web antusias dengan passion di bidang teknologi dan desain kreatif.</p>

    <h2>Keterampilan</h2>
    <table class="skills" border="1" cellpadding="5" cellspacing="0">
                <tr>
                    <th>Keterampilan</th>
                    <th>Tingkat</th>
                </tr>
                <tr>
                    <td>HTML/CSS</td>
                    <td>Mahir</td>
                </tr>
                <tr>
                    <td>JavaScript</td>  
        <!-- table, tr, th, td: Membuat dan mengatur data tabel -->
                    <td>Menengah</td>
                </tr>
                <tr>
                    <td>Python</td>
                    <td>Pemula</td>
                </tr>
            </table>

    <h2>Hubungi Saya</h2>
    <div class="contact">
        <form>
              <p><strong>Nama:</strong> Givo Syabani</p>
              <p><strong>Email:</strong> wahahasha@gmail.com</p>
              <label for="message">Pesan:</label><br>
              <textarea id="message" name="message" rows="4" cols="50"></textarea><br><br>
              <button type="button">Batal</button>
<!-- button: Memicu aksi saat diklik -->
              <input type="submit" value="Kirim Pesan">
<!-- input: Memasukkan data pengguna ke form -->
        </form>
        <!-- form: Menampung input untuk dikirimkan -->
    </div>    

    <div class="social-media">
        <a href="#">Linkedin</a> | 
        <a href="#">GitHub</a> | 
        <a href="#">Twitter</a>
        <!-- a: Membuat hyperlink ke halaman lain. -->
    </div>
</body>
</html>

