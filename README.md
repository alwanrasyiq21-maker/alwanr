<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Website Profil Siswa</title>
    <style>
        body {
            font-family: Arial, Helvetica, sans-serif;
            background-color: #f5f5f5;
            margin: 0;
            padding: 0;
        }

        .container {
            width: 800px;
            margin: 30px auto;
            background-color: #ffffff;
            padding: 20px 30px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        h1 {
            border-bottom: 2px solid #ccc;
            padding-bottom: 10px;
        }

        .profile {
            display: flex;
            gap: 20px;
            margin-top: 20px;
        }

        .profile img {
            width: 180px;
            height: auto;
            border-radius: 4px;
        }

        .profile-info p {
            margin: 6px 0;
        }

        h2 {
            margin-top: 30px;
            border-bottom: 1px solid #ddd;
            padding-bottom: 5px;
        }

        ul {
            padding-left: 20px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 15px;
        }

        table, th, td {
            border: 1px solid #555;
        }

        th, td {
            padding: 10px;
            text-align: center;
        }

        th {
            background-color: #eaeaea;
        }

        footer {
            text-align: center;
            margin-top: 30px;
            color: #777;
            font-size: 14px;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Website Profil Siswa</h1>

    <div class="profile">
        <img src="https://image2url.com/r2/default/images/1771209382617-486839d6-4ef1-476f-a002-42508683f787.jpeg" alt="Foto Profil">
        <div class="profile-info">
            <p><strong>Nama:</strong> M Alwan Rasyiq</p>
            <p><strong>Kelas:</strong> XI IPA 4</p>
            <p><strong>Sekolah:</strong> SMAN 5 Cimahi</p>
            <p><strong>Cita-cita:</strong> Insinyur</p>
        </div>
    </div>

    <h2>Tentang Saya</h2>
    <p>
        Saya adalah siswa yang sedang belajar membuat website menggunakan HTML
        pada mata pelajaran Informatika.
    </p>

    <h2>Media Sosial & Kontak</h2>
    <ul>
        <li>Instagram: <a href="#">@4lwaann__</a></li>
        <li>GitHub: <a href="#">github.com/alwanrasyiq</a></li>
        <li>Email: <a href="#">alwanrasyiq21@gmail.com</a></li>
    </ul>

    <h2>Riwayat Pendidikan</h2>
    <table>
        <tr>
            <th>No</th>
            <th>Sekolah</th>
            <th>Tahun</th>
        </tr>
        <tr>
            <td>1</td>
            <td>SDIT Fitrah Insain</td>
            <td>2015 - 2021</td>
        </tr>
        <tr>
            <td>2</td>
            <td>SMPIT Fitrah Insani</td>
            <td>2021 - 2024</td>
        </tr>
        <tr>
            <td>3</td>
            <td>SMAN 5 Cimahi</td>
            <td>2024 - Sekarang</td>
        </tr>
    </table>

    <footer>
        ©️ 2026 | Website Profil Siswa - Informatika
    </footer>
</div>

</body>
</html>
