<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jennifer - Keuangan Jajan</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        .container {
            background: white;
            border-radius: 20px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            padding: 30px;
            width: 100%;
            max-width: 500px;
        }

        .app-title {
            text-align: center;
            margin-bottom: 30px;
        }

        .app-title h1 {
            font-size: 2.5em;
            color: #667eea;
            margin-bottom: 10px;
            cursor: pointer;
            transition: transform 0.3s ease;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.1);
        }

        .app-title h1:hover {
            transform: scale(1.05);
            color: #764ba2;
        }

        .app-title h1:active {
            transform: scale(0.95);
        }

        .app-title p {
            color: #666;
            font-size: 0.9em;
        }

        .balance-card {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 25px;
            border-radius: 15px;
            text-align: center;
            margin-bottom: 30px;
            box-shadow: 0 10px 20px rgba(102, 126, 234, 0.3);
        }

        .balance-label {
            font-size: 0.9em;
            opacity: 0.9;
            margin-bottom: 10px;
        }

        .balance-amount {
            font-size: 2.5em;
            font-weight: bold;
        }

        .menu-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 15px;
            margin-bottom: 30px;
        }

        .menu-item {
            background: #f8f9fa;
            border: 2px solid #e9ecef;
            border-radius: 12px;
            padding: 20px;
            text-align: center;
            cursor: pointer;
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
        }

        .menu-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
            border-color: #667eea;
            background: white;
        }

        .menu-item:active {
            transform: translateY(-2px);
        }

        .menu-icon {
            font-size: 2.5em;
            margin-bottom: 10px;
        }

        .menu-name {
            font-weight: bold;
            color: #333;
            margin-bottom: 5px;
        }

        .menu-price {
            color: #667eea;
            font-weight: bold;
            font-size: 1.1em;
        }

        .history-section {
            background: #f8f9fa;
            border-radius: 12px;
            padding: 20px;
            margin-bottom: 30px;
        }

        .history-title {
            font-weight: bold;
            color: #333;
            margin-bottom: 15px;
            font-size: 1.1em;
        }

        .history-list {
            max-height: 200px;
            overflow-y: auto;
        }

        .history-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px;
            background: white;
            border-radius: 8px;
            margin-bottom: 8px;
            animation: slideIn 0.3s ease;
        }

        @keyframes slideIn {
            from {
                opacity: 0;
                transform: translateY(-10px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .history-item-name {
            font-weight: 500;
            color: #333;
        }

        .history-item-price {
            color: #667eea;
            font-weight: bold;
        }

        .history-item-time {
            font-size: 0.8em;
            color: #999;
        }

        .reset-btn {
            width: 100%;
            padding: 15px;
            background: #dc3545;
            color: white;
            border: none;
            border-radius: 12px;
            font-size: 1em;
            font-weight: bold;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .reset-btn:hover {
            background: #c82333;
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(220, 53, 69, 0.3);
        }

        .reset-btn:active {
            transform: translateY(0);
        }

        .notification {
            position: fixed;
            top: 20px;
            right: 20px;
            background: #28a745;
            color: white;
            padding: 15px 20px;
            border-radius: 10px;
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
            transform: translateX(400px);
            transition: transform 0.3s ease;
            z-index: 1000;
        }

        .notification.show {
            transform: translateX(0);
        }

        .notification.error {
            background: #dc3545;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="app-title">
            <h1 onclick="showAppInfo()">🍜 Jennifer</h1>
            <p>Aplikasi Keuangan Jajan</p>
        </div>

        <div class="balance-card">
            <div class="balance-label">Sisa Uang Jajan</div>
            <div class="balance-amount" id="balance">Rp 50.000</div>
        </div>

        <div class="menu-grid">
            <div class="menu-item" onclick="beliJajan('Bakso', 15000)">
                <div class="menu-icon">🍜</div>
                <div class="menu-name">Bakso</div>
                <div class="menu-price">Rp 15.000</div>
            </div>
            
            <div class="menu-item" onclick="beliJajan('Chicuro', 10000)">
                <div class="menu-icon">🍗</div>
                <div class="menu-name">Chicuro</div>
                <div class="menu-price">Rp 10.000</div>
            </div>
            
            <div class="menu-item" onclick="beliJajan('Red Dog', 12000)">
                <div class="menu-icon">🌭</div>
                <div class="menu-name">Red Dog</div>
                <div class="menu-price">Rp 12.000</div>
            </div>
            
            <div class="menu-item" onclick="beliJajan('Mie Goreng', 8000)">
                <div class="menu-icon">🍝</div>
                <div class="menu-name">Mie Goreng</div>
                <div class="menu-price">Rp 8.000</div>
            </div>
        </div>

        <div class="history-section">
            <div class="history-title">📋 Riwayat Pembelian</div>
            <div class="history-list" id="historyList">
                <div style="text-align: center; color: #999; padding: 20px;">
                    Belum ada pembelian
                </div>
            </div>
        </div>

        <button class="reset-btn" onclick="resetKeuangan()">
            🔄 Reset Keuangan
        </button>
    </div>

    <div class="notification" id="notification"></div>

    <script>
        // Data keuangan
        let saldo = 50000;
        let riwayatPembelian = [];

        // Fungsi untuk membeli jajan
        function beliJajan(nama, harga) {
            if (saldo >= harga) {
                saldo -= harga;
                
                // Tambah ke riwayat
                const now = new Date();
                const waktu = now.getHours().toString().padStart(2, '0') + ':' + 
                             now.getMinutes().toString().padStart(2, '0');
                
                riwayatPembelian.unshift({
                    nama: nama,
                    harga: harga,
                    waktu: waktu
                });
                
                // Update tampilan
                updateTampilan();
                showNotification(`Berhasil membeli ${nama}! 🎉`);
                
                // Animasi pada balance
                animateBalance();
            } else {
                showNotification('Uang tidak cukup! 😢', 'error');
            }
        }

        // Fungsi untuk mereset keuangan
        function resetKeuangan() {
            if (confirm('Yakin ingin mereset keuangan? Saldo akan kembali ke Rp 50.000')) {
                saldo = 50000;
                riwayatPembelian = [];
                updateTampilan();
                showNotification('Keuangan berhasil direset! 🔄');
            }
        }

        // Fungsi untuk menampilkan info aplikasi
        function showAppInfo() {
            alert('🍜 Jennifer - Aplikasi Keuangan Jajan\n\n' +
                  'Aplikasi untuk mencatat pengeluaran jajan kamu!\n\n' +
                  'Fitur:\n' +
                  '• Catat pembelian jajan\n' +
                  '• Lihat riwayat pembelian\n' +
                  '• Reset keuangan\n\n' +
                  'Dibuat dengan ❤️');
        }

        // Fungsi untuk mengupdate tampilan
        function updateTampilan() {
            // Update saldo
            document.getElementById('balance').textContent = 
                'Rp ' + saldo.toLocaleString('id-ID');
            
            // Update riwayat
            const historyList = document.getElementById('historyList');
            
            if (riwayatPembelian.length === 0) {
                historyList.innerHTML = `
                    <div style="text-align: center; color: #999; padding: 20px;">
                        Belum ada pembelian
                    </div>
                `;
            } else {
                historyList.innerHTML = riwayatPembelian.map(item => `
                    <div class="history-item">
                        <div>
                            <div class="history-item-name">${item.nama}</div>
                            <div class="history-item-time">${item.waktu}</div>
                        </div>
                        <div class="history-item-price">-Rp ${item.harga.toLocaleString('id-ID')}</div>
                    </div>
                `).join('');
            }
        }

        // Fungsi untuk animasi balance
        function animateBalance() {
            const balanceElement = document.getElementById('balance');
            balanceElement.style.transform = 'scale(1.1)';
            balanceElement.style.transition = 'transform 0.3s ease';
            
            setTimeout(() => {
                balanceElement.style.transform = 'scale(1)';
            }, 300);
        }

        // Fungsi untuk notifikasi
        function showNotification(message, type = 'success') {
            const notification = document.getElementById('notification');
            notification.textContent = message;
            notification.className = 'notification';
            
            if (type === 'error') {
                notification.classList.add('error');
            }
            
            notification.classList.add('show');
            
            setTimeout(() => {
                notification.classList.remove('show');
            }, 2000);
        }

        // Update tampilan pertama kali
        updateTampilan();
    </script>
</body>
</html>
