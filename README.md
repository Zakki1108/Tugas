<?php
// Program sederhana: menghitung luas dan keliling persegi panjang

// Mendeklarasikan variabel untuk menyimpan panjang dan lebar
$panjang = readline('Masukan Nilai Panjang:'); 
$lebar = readline('Masukan Nilai Lebar:');     
$luas = $panjang * $lebar;  
$keliling = 2 * ($panjang + $lebar);  

// Menampilkan hasil perhitungan
echo "Panjang: " . $panjang . "<br>";
echo "Lebar: " . $lebar . "<br>";
echo "Luas persegi panjang: " . $luas . "<br>";
echo "Keliling persegi panjang: " . $keliling . "<br>";
?>
