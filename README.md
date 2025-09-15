<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>README - MKS JAYA Konstruksi</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #f8f9fa;
            color: #333;
            line-height: 1.6;
            padding: 20px;
            max-width: 1000px;
            margin: 0 auto;
        }
        
        .header {
            text-align: center;
            padding: 30px 0;
            background: linear-gradient(135deg, #1e5799 0%, #2989d8 100%);
            color: white;
            border-radius: 10px;
            margin-bottom: 30px;
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        
        h2 {
            color: #1e5799;
            margin: 25px 0 15px;
            padding-bottom: 10px;
            border-bottom: 2px solid #1e5799;
        }
        
        h3 {
            color: #2989d8;
            margin: 20px 0 10px;
        }
        
        .content {
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        
        .section {
            margin-bottom: 30px;
        }
        
        .logo {
            font-size: 2rem;
            font-weight: bold;
            margin-bottom: 10px;
        }
        
        .info-box {
            background: #f0f7ff;
            padding: 20px;
            border-radius: 8px;
            margin: 15px 0;
            border-left: 4px solid #1e5799;
        }
        
        .steps {
            margin-left: 20px;
        }
        
        .steps li {
            margin-bottom: 10px;
        }
        
        .code-block {
            background: #2d2d2d;
            color: #f8f8f2;
            padding: 15px;
            border-radius: 5px;
            overflow-x: auto;
            margin: 15px 0;
            font-family: 'Courier New', monospace;
        }
        
        .tag {
            display: inline-block;
            background: #e9ecef;
            padding: 3px 8px;
            border-radius: 4px;
            font-family: 'Courier New', monospace;
            font-size: 0.9em;
        }
        
        .button {
            display: inline-block;
            background: #1e5799;
            color: white;
            padding: 10px 20px;
            border-radius: 5px;
            text-decoration: none;
            margin: 10px 5px;
            font-weight: bold;
        }
        
        .button:hover {
            background: #2989d8;
        }
        
        .features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin: 20px 0;
        }
        
        .feature {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 8px;
            border-left: 4px solid #2989d8;
        }
        
        .screenshot {
            text-align: center;
            margin: 20px 0;
        }
        
        .screenshot img {
            max-width: 100%;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 15px 0;
        }
        
        table, th, td {
            border: 1px solid #ddd;
        }
        
        th, td {
            padding: 12px 15px;
            text-align: left;
        }
        
        th {
            background-color: #f0f7ff;
        }
        
        .footer {
            text-align: center;
            margin-top: 40px;
            padding: 20px;
            color: #6c757d;
        }
        
        @media (max-width: 768px) {
            body {
                padding: 10px;
            }
            
            .features {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="header">
        <div class="logo">MKS JAYA KONSTRUKSI</div>
        <p>Landing Page Documentation</p>
    </div>
    
    <div class="content">
        <div class="section">
            <h2>📋 Deskripsi Proyek</h2>
            <p>Landing page responsif untuk MKS JAYA Konstruksi yang menampilkan layanan konstruksi profesional termasuk pemasangan atap baja ringan, plafon, kusen aluminium, pembangunan rumah/ruko/gudang, dan desain konstruksi.</p>
            
            <div class="info-box">
                <p><strong>Alamat:</strong> Jl. Dahlia E No, 6 - GPI</p>
                <p><strong>Telepon:</strong> 085256530667</p>
                <p><strong>Fitur Utama:</strong> Responsif, Integrasi WhatsApp, Form Pemesanan, Galeri Proyek</p>
            </div>
        </div>
        
        <div class="section">
            <h2>🚀 Cara Menggunakan</h2>
            
            <h3>1. Hosting Landing Page</h3>
            <ol class="steps">
                <li>Salin seluruh kode HTML</li>
                <li>Buat file baru dengan nama <span class="tag">index.html</span></li>
                <li>Tempel kode ke dalam file</li>
                <li>Simpan dan upload ke hosting provider (Netlify, GitHub Pages, atau hosting lain)</li>
            </ol>
            
            <h3>2. Bagikan di Facebook</h3>
            <ol class="steps">
                <li>Dapatkan URL halaman yang sudah dihosting</li>
                <li>Posting URL tersebut di timeline Facebook atau grup terkait</li>
                <li>Facebook akan otomatis men-generate preview dengan gambar dan deskripsi</li>
            </ol>
            
            <h3>3. Customisasi Konten</h3>
            <ol class="steps">
                <li>Ganti teks, gambar, dan informasi kontak sesuai kebutuhan</li>
                <li>Ubah warna dengan mengganti kode warna CSS</li>
                <li>Tambahkan gambar proyek nyata ke bagian galeri</li>
            </ol>
        </div>
        
        <div class="section">
            <h2>🛠️ Teknologi yang Digunakan</h2>
            <ul class="steps">
                <li><strong>HTML5</strong> - Struktur halaman web</li>
                <li><strong>CSS3</strong> - Styling dan layout responsif</li>
                <li><strong>JavaScript</strong> - Interaksi dan fungsi formulir</li>
                <li><strong>Font Awesome</strong> - Ikon yang digunakan</li>
                <li><strong>Google Fonts</strong> - Font Roboto</li>
            </ul>
        </div>
        
        <div class="section">
            <h2>⭐ Fitur Utama</h2>
            <div class="features">
                <div class="feature">
                    <h3><i class="fas fa-mobile-alt"></i> Desain Responsif</h3>
                    <p>Tampilan optimal di semua perangkat (desktop, tablet, smartphone)</p>
                </div>
                <div class="feature">
                    <h3><i class="fab fa-whatsapp"></i> Integrasi WhatsApp</h3>
                    <p>Pelanggan dapat langsung menghubungi via WhatsApp dengan satu klik</p>
                </div>
                <div class="feature">
                    <h3><i class="fas fa-form"></i> Form Pemesanan</h3>
                    <p>Formulir pemesanan dengan validasi dan konfirmasi</p>
                </div>
                <div class="feature">
                    <h3><i class="fab fa-facebook"></i> Optimasi Facebook</h3>
                    <p>Meta tags khusus untuk tampilan optimal saat dibagikan di Facebook</p>
                </div>
            </div>
        </div>
        
        <div class="section">
            <h2>📝 Struktur Kode</h2>
            
            <h3>Meta Tags untuk Facebook</h3>
            <div class="code-block">
&lt;meta property="og:title" content="MKS JAYA Konstruksi"&gt;
&lt;meta property="og:description" content="Jasa konstruksi profesional..."&gt;
&lt;meta property="og:image" content="URL_GAMBAR_ANDA"&gt;
&lt;meta property="og:url" content="URL_WEBSITE_ANDA"&gt;
&lt;meta property="og:type" content="website"&gt;
            </div>
            
            <h3>Bagian Penting HTML</h3>
            <table>
                <tr>
                    <th>Bagian</th>
                    <th>Deskripsi</th>
                </tr>
                <tr>
                    <td>Header</td>
                    <td>Informasi perusahaan dan kontak</td>
                </tr>
                <tr>
                    <td>Layanan</td>
                    <td>Daftar layanan yang ditawarkan</td>
                </tr>
                <tr>
                    <td>Galeri</td>
                    <td>Foto-foto proyek sebelumnya</td>
                </tr>
                <tr>
                    <td>Form Pemesanan</td>
                    <td>Formulir pemesanan dengan validasi</td>
                </tr>
                <tr>
                    <td>Footer</td>
                    <td>Informasi hak cipta dan sosial media</td>
                </tr>
            </table>
        </div>
        
        <div class="section">
            <h2>🎨 Customisasi</h2>
            
            <h3>Mengganti Informasi Perusahaan</h3>
            <p>Edit bagian berikut dalam kode HTML:</p>
            <div class="code-block">
&lt;div class="company-name"&gt;MKS JAYA&lt;/div&gt;
&lt;div class="company-tag"&gt;Konstruksi&lt;/div&gt;
&lt;div class="company-address"&gt;Jl. Dahlia E No, 6 - GPI&lt;/div&gt;
&lt;div class="company-phone"&gt;085256530667&lt;/div&gt;
            </div>
            
            <h3>Mengganti Warna Tema</h3>
            <p>Ubah variabel warna utama dalam CSS:</p>
            <div class="code-block">
:root {
  --primary-color: #1e5799;
  --secondary-color: #2989d8;
  --accent-color: #ff6b00;
}
            </div>
        </div>
        
        <div class="section">
            <h2>📊 Optimasi untuk Facebook</h2>
            
            <h3>Langkah-langkah Optimasi</h3>
            <ol class="steps">
                <li>Ganti <span class="tag">og:image</span> dengan gambar representatif bisnis Anda</li>
                <li>Update <span class="tag">og:url</span> dengan URL website setelah dihosting</li>
                <li>Pastikan gambar og:image berukuran minimal 1200x630 piksel</li>
                <li>Test tampilan pratinjau menggunakan <a href="https://developers.facebook.com/tools/debug/" target="_blank">Facebook Sharing Debugger</a></li>
            </ol>
            
            <h3>Tips untuk Hasil Terbaik</h3>
            <ul class="steps">
                <li>Gunakan gambar yang menarik dan relevan</li>
                <li>Buat deskripsi yang jelas dan menarik perhatian</li>
                <li>Pastikan website sudah online sebelum dibagikan</li>
                <li>Test di berbagai perangkat untuk memastikan responsivitas</li>
            </ul>
        </div>
        
        <div class="section">
            <h2>🔧 Troubleshooting</h2>
            
            <h3>Masalah Umum dan Solusi</h3>
            <table>
                <tr>
                    <th>Masalah</th>
                    <th>Solusi</th>
                </tr>
                <tr>
                    <td>Preview tidak muncul di Facebook</td>
                    <td>Gunakan Facebook Debugger untuk refresh cache</td>
                </tr>
                <tr>
                    <td>Tampilan tidak responsif</td>
                    <td>Periksa meta viewport tag dan CSS media queries</td>
                </tr>
                <tr>
                    <td>Form tidak mengirim ke WhatsApp</td>
                    <td>Periksa format nomor telepon (harus dengan kode negara)</td>
                </tr>
                <tr>
                    <td>Gambar tidak muncul</td>
                    <td>Pastikan URL gambar benar dan dapat diakses</td>
                </tr>
            </table>
        </div>
        
        <div class="section">
            <h2>📞 Support</h2>
            <p>Jika Anda mengalami kesulitan atau memiliki pertanyaan tentang landing page ini, silakan hubungi:</p>
            <div class="info-box">
                <p><strong>Telepon/WhatsApp:</strong> 085256530667</p>
                <p><strong>Alamat:</strong> Jl. Dahlia E No, 6 - GPI</p>
            </div>
        </div>
        
        <div class="section">
            <a href="#" class="button"><i class="fas fa-download"></i> Download Kode Lengkap</a>
            <a href="#" class="button" style="background-color: #25D366;"><i class="fab fa-whatsapp"></i> Hubungi WhatsApp</a>
        </div>
    </div>
    
    <div class="footer">
        <p>© 2023 MKS JAYA Konstruksi - Dokumentasi Landing Page</p>
    </div>

    <script>
        // Fungsi untuk smooth scrolling
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth'
                    });
                }
            });
        });
        
        // Simulasi download button
        document.querySelector('.button').addEventListener('click', function(e) {
            e.preventDefault();
            alert('Untuk mendapatkan kode lengkap, simpan halaman ini sebagai HTML file melalui browser Anda (Ctrl+S atau File > Save Page As).');
        });
    </script>
</body>
</html>
