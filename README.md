<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
<html>
<head>
  <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
  <meta http-equiv="Content-Style-Type" content="text/css">
  <title></title>
  <meta name="Generator" content="Cocoa HTML Writer">
  <meta name="CocoaVersion" content="2113.65">
  <style type="text/css">
    p.p2 {margin: 0.0px 0.0px 16.0px 0.0px; font: 12.0px Helvetica; color: #151516; -webkit-text-stroke: #151516}
    p.p6 {margin: 0.0px 0.0px 12.0px 0.0px; font: 12.0px Helvetica; color: #151516; -webkit-text-stroke: #151516}
    p.p7 {margin: 0.0px 0.0px 0.0px 0.0px; font: 12.0px Helvetica; color: #343736; -webkit-text-stroke: #343736; background-color: #e4eaf4}
    p.p8 {margin: 0.0px 0.0px 0.0px 0.0px; font: 12.0px Helvetica; color: #343736; -webkit-text-stroke: #343736; background-color: #e4eaf4; min-height: 14.0px}
    p.p9 {margin: 0.0px 0.0px 0.0px 0.0px; font: 12.0px Helvetica; color: #343736; -webkit-text-stroke: #343736; min-height: 14.0px}
    li.li4 {margin: 0.0px 0.0px 8.0px 0.0px; font: 12.0px Helvetica; color: #151516; -webkit-text-stroke: #151516}
    span.s1 {font: 24.0px 'Apple Color Emoji'; font-kerning: none}
    span.s2 {font-kerning: none}
    span.s3 {font: 18.0px 'Apple Color Emoji'; font-kerning: none}
    span.s4 {-webkit-text-stroke: 0px #000000}
    span.s5 {font-kerning: none; color: #343736; background-color: #e4eaf4; -webkit-text-stroke: 0px #343736}
    ol.ol1 {list-style-type: decimal}
    ul.ul1 {list-style-type: disc}
    ul.ul2 {list-style-type: circle}
  </style>
</head>
<body>
<h1 style="margin: 0.0px 0.0px 8.0px 0.0px; font: 24.0px Helvetica; color: #151516; -webkit-text-stroke: #151516"><span class="s1">💰</span><span class="s2"><b> Pencatat Keuangan Pribadi (Supabase Edition)</b></span></h1>
<p class="p2"><span class="s2">Aplikasi web sederhana namun powerful untuk mencatat pemasukan dan pengeluaran pribadi. Dibangun menggunakan <b>HTML, Tailwind CSS, dan Vanilla JS</b>, serta terintegrasi dengan <b>Supabase</b> sebagai database cloud real-time.</span></p>
<h2 style="margin: 0.0px 0.0px 8.0px 0.0px; font: 18.0px Helvetica; color: #151516; -webkit-text-stroke: #151516"><span class="s3">🌟</span><span class="s2"><b> Fitur Utama</b></span></h2>
<ul class="ul1">
  <li class="li4"><span class="s4"><b></b></span><span class="s2"><b>Cloud Storage:</b> Data tersimpan aman di Supabase (PostgreSQL), tidak hilang saat browser ditutup.</span></li>
  <li class="li4"><span class="s4"><b></b></span><span class="s2"><b>Dashboard Interaktif:</b> Grafik visual (Chart.js) untuk melihat arus kas, pemasukan, dan pengeluaran.</span></li>
  <li class="li4"><span class="s4"><b></b></span><span class="s2"><b>Laporan Lengkap:</b></span></li>
  <ul class="ul2">
    <li class="li4"><span class="s4"></span><span class="s2">Laporan Bulanan dengan Rincian.</span></li>
    <li class="li4"><span class="s4"></span><span class="s2">Laporan Tahunan (Grid 12 Bulan).</span></li>
  </ul>
  <li class="li4"><span class="s4"><b></b></span><span class="s2"><b>Ekspor Data:</b></span></li>
  <ul class="ul2">
    <li class="li4"><span class="s4"></span><span class="s2">Download Laporan sebagai <b>PDF</b> (Format A4 Landscape).</span></li>
    <li class="li4"><span class="s4"></span><span class="s2">Download Riwayat Transaksi sebagai <b>Excel (.xlsx)</b>.</span></li>
  </ul>
  <li class="li4"><span class="s4"><b></b></span><span class="s2"><b>Deteksi Anomali:</b> Fitur pintar untuk mendeteksi pengeluaran yang tidak wajar (3x lipat dari rata-rata).</span></li>
  <li class="li4"><span class="s4"><b></b></span><span class="s2"><b>Manajemen Kategori:</b> Tambah, edit, dan hapus kategori pemasukan/pengeluaran sesuka hati.</span></li>
</ul>
<h2 style="margin: 0.0px 0.0px 8.0px 0.0px; font: 18.0px Helvetica; color: #151516; -webkit-text-stroke: #151516"><span class="s3">🚀</span><span class="s2"><b> Cara Penggunaan (Deployment)</b></span></h2>
<p class="p2"><span class="s2">Anda bisa menjalankan aplikasi ini langsung tanpa instalasi server (Serverless).</span></p>
<h3 style="margin: 0.0px 0.0px 8.0px 0.0px; font: 14.0px Helvetica; color: #151516; -webkit-text-stroke: #151516"><span class="s2"><b>1. Persiapan File</b></span></h3>
<p class="p2"><span class="s2">Pastikan file utama aplikasi Anda bernama </span><span class="s5">index.html</span><span class="s2">.</span></p>
<h3 style="margin: 0.0px 0.0px 8.0px 0.0px; font: 14.0px Helvetica; color: #151516; -webkit-text-stroke: #151516"><span class="s2"><b>2. Konfigurasi Database (Supabase)</b></span></h3>
<p class="p6"><span class="s2">Aplikasi ini membutuhkan tabel transactions dan categories di Supabase Anda.</span></p>
<p class="p6"><span class="s2">Jalankan perintah SQL berikut di SQL Editor Supabase Anda:</span></p>
<p class="p7"><span class="s2">-- 1. Tabel Kategori</span></p>
<p class="p7"><span class="s2">create table if not exists categories (</span></p>
<p class="p7"><span class="s2"><span class="Apple-converted-space">  </span>id bigint generated by default as identity primary key,</span></p>
<p class="p7"><span class="s2"><span class="Apple-converted-space">  </span>created_at timestamp with time zone default timezone('utc'::text, now()) not null,</span></p>
<p class="p7"><span class="s2"><span class="Apple-converted-space">  </span>name text not null,</span></p>
<p class="p7"><span class="s2"><span class="Apple-converted-space">  </span>type text not null,</span></p>
<p class="p7"><span class="s2"><span class="Apple-converted-space">  </span>description text,</span></p>
<p class="p7"><span class="s2"><span class="Apple-converted-space">  </span>user_id uuid</span></p>
<p class="p7"><span class="s2">);</span></p>
<p class="p8"><span class="s2"></span><br></p>
<p class="p7"><span class="s2">-- 2. Tabel Transaksi</span></p>
<p class="p7"><span class="s2">create table if not exists transactions (</span></p>
<p class="p7"><span class="s2"><span class="Apple-converted-space">  </span>id bigint generated by default as identity primary key,</span></p>
<p class="p7"><span class="s2"><span class="Apple-converted-space">  </span>created_at timestamp with time zone default timezone('utc'::text, now()) not null,</span></p>
<p class="p7"><span class="s2"><span class="Apple-converted-space">  </span>date date,</span></p>
<p class="p7"><span class="s2"><span class="Apple-converted-space">  </span>type text,</span></p>
<p class="p7"><span class="s2"><span class="Apple-converted-space">  </span>category text,</span></p>
<p class="p7"><span class="s2"><span class="Apple-converted-space">  </span>amount numeric,</span></p>
<p class="p7"><span class="s2"><span class="Apple-converted-space">  </span>description text,</span></p>
<p class="p7"><span class="s2"><span class="Apple-converted-space">  </span>user_id uuid</span></p>
<p class="p7"><span class="s2">);</span></p>
<p class="p8"><span class="s2"></span><br></p>
<p class="p7"><span class="s2">-- 3. Aktifkan RLS (Row Level Security)</span></p>
<p class="p7"><span class="s2">alter table categories enable row level security;</span></p>
<p class="p7"><span class="s2">alter table transactions enable row level security;</span></p>
<p class="p8"><span class="s2"></span><br></p>
<p class="p7"><span class="s2">-- 4. Kebijakan Akses (Untuk Demo/Public)</span></p>
<p class="p7"><span class="s2">create policy "Enable all access for categories" on categories for all using (true) with check (true);</span></p>
<p class="p7"><span class="s2">create policy "Enable all access for transactions" on transactions for all using (true) with check (true);</span></p>
<p class="p9"><span class="s2"></span><br></p>
<h3 style="margin: 0.0px 0.0px 8.0px 0.0px; font: 14.0px Helvetica; color: #151516; -webkit-text-stroke: #151516"><span class="s2"><b>3. Hosting di GitHub Pages</b></span></h3>
<ol class="ol1">
  <li class="li4"><span class="s4"></span><span class="s2">Upload file </span><span class="s5">index.html</span><span class="s2"> ke repository GitHub.</span></li>
  <li class="li4"><span class="s4"></span><span class="s2">Masuk ke <b>Settings</b> &gt; <b>Pages</b>.</span></li>
  <li class="li4"><span class="s4"></span><span class="s2">Pada bagian <b>Build and deployment</b>, pilih Branch: </span><span class="s5">main</span><span class="s2"> lalu klik <b>Save</b>.</span></li>
  <li class="li4"><span class="s4"></span><span class="s2">Tunggu beberapa saat, link website Anda akan muncul!</span></li>
</ol>
<h2 style="margin: 0.0px 0.0px 8.0px 0.0px; font: 18.0px Helvetica; color: #151516; -webkit-text-stroke: #151516"><span class="s3">🛠️</span><span class="s2"><b> Teknologi yang Digunakan</b></span></h2>
<ul class="ul1">
  <li class="li4"><span class="s4"><b></b></span><span class="s2"><b>Frontend:</b> HTML5, JavaScript (ES6 Modules)</span></li>
  <li class="li4"><span class="s4"><b></b></span><span class="s2"><b>Styling:</b> Tailwind CSS (CDN)</span></li>
  <li class="li4"><span class="s4"><b></b></span><span class="s2"><b>Database:</b> Supabase (PostgreSQL)</span></li>
  <li class="li4"><span class="s4"><b></b></span><span class="s2"><b>Charts:</b> Chart.js</span></li>
  <li class="li4"><span class="s4"><b></b></span><span class="s2"><b>PDF Generation:</b> jsPDF &amp; html2canvas</span></li>
  <li class="li4"><span class="s4"><b></b></span><span class="s2"><b>Excel:</b> SheetJS (xlsx)</span></li>
</ul>
<h2 style="margin: 0.0px 0.0px 8.0px 0.0px; font: 18.0px Helvetica; color: #151516; -webkit-text-stroke: #151516"><span class="s3">⚠️</span><span class="s2"><b> Catatan Keamanan</b></span></h2>
<p class="p2"><span class="s2">Proyek ini menggunakan <i>Anon Key</i> Supabase di sisi klien. Pastikan Anda telah mengatur <i>Row Level Security (RLS)</i> di Supabase jika ingin data benar-benar privat per pengguna.</span></p>
</body>
</html>
