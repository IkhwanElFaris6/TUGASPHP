<?php
error_reporting(E_ALL);
ini_set('display_errors', 1);

if ($_SERVER['REQUEST_METHOD'] === 'POST') {

    $nama = $_POST['nama'];
    $email = $_POST['email'];
    $nilai = $_POST['nilai'];

    if ($nilai > 70) {
        $hasil = "Lulus";
    } else {
        $hasil = "Remedial";
    }

    echo "<h2>Hasil Ujian</h2>";
    echo "Nama: $nama<br>";
    echo "Email: $email<br>";
    echo "Nilai Ujian: $nilai<br>";
    echo "Status: $hasil<br>";
} else {
    echo "Form tidak dikirim dengan metode POST!";
}
?>
