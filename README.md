<!DOCTYPE html>
<html lang="hi">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>India News — Home</title>
  <meta name="description" content="Latest India news, updates and breaking stories."/>
  <style>
    /* Simple responsive styling */
    :root{--accent:#d32f2f;--muted:#666}
    *{box-sizing:border-box}
    body{font-family:system-ui,Segoe UI,Roboto,'Noto Sans',sans-serif;margin:0;color:#111;line-height:1.45}
    header{background:#111;color:#fff;padding:14px 16px;display:flex;align-items:center;justify-content:space-between;gap:12px}
    header h1{font-size:1.05rem;margin:0}
    .container{max-width:1100px;margin:18px auto;padding:0 16px}
    .top-break{background:var(--accent);color:#fff;padding:8px 12px;border-radius:6px;display:inline-block;font-weight:600}
    .grid{display:grid;grid-template-columns:1fr;gap:18px}
    @media(min-width:880px){ .grid{grid-template-columns:2fr 1fr} }
    .card{background:#fff;border-radius:8px;padding:14px;box-shadow:0 6px 18px rgba(0,0,0,0.06)}
    .headline{font-size:1.15rem;margin:6px 0}
    .meta{color:var(--muted);font-size:0.9rem}
    .list-news{display:grid;gap:12px}
    .list-item{display:flex;gap:12px;align-items:flex-start}
    .thumb{width:120px;height:76px;background:#eee;border-radius:6px;flex-shrink:0;object-fit:cover}
    footer{padding:20px;text-align:center;color:var(--muted);font-size:0.9rem;margin-top:28px}
    nav a{color:#fff;text-decoration:none;margin-left:14px;font-weight:600}
    .categories{display:flex;gap:8px;flex-wrap:wrap;margin:8px 0}
    .cat{background:#f3f3f3;padding:6px 10px;border-radius:6px;font-weight:600}
  </style>
</head>
<body>
  <header>
    <h1>India News</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">India</a>
      <a href="#">World</a>
      <a href="#">Business</a>
      <a href="#">Sports</a>
    </nav>
  </header>

  <main class="container">
    <div style="display:flex;gap:16px;align-items:center;justify-content:space-between">
      <div class="top-break">BREAKING: बड़ा अपडेट अभी-अभी</div>
      <div class="meta">Updated: 21 Nov 2025</div>
    </div>

    <section class="grid" style="margin-top:14px">
      <div>
        <div class="card">
          <img src="https://via.placeholder.com/1000x420" alt="lead" style="width:100%;height:320px;object-fit:cover;border-radius:6px">
          <h2 class="headline">मुख्य खबर का शीर्षक — यह जगह हेडलाइन के लिए है</h2>
          <div class="meta">Author • 21 Nov 2025 • 2 min read</div>
          <p style="margin-top:10px;color:#333">यहाँ मुख्य खबर का संक्षेप लिखा जाएगा — उपयोगकर्ता को पढ़ने के लिए क्लिक करने को प्रेरित करे।</p>
        </div>

        <div style="margin-top:14px" class="card">
          <h3 style="margin:0 0 8px 0">Latest News</h3>
          <div class="list-news">
            <div class="list-item">
              <img class="thumb" src="https://via.placeholder.com/300x200" alt="">
              <div>
                <div style="font-weight:700">खबर 1 का छोटा शीर्षक</div>
                <div class="meta">2 hours ago</div>
              </div>
            </div>

            <div class="list-item">
              <img class="thumb" src="https://via.placeholder.com/300x200" alt="">
              <div>
                <div style="font-weight:700">खबर 2 का छोटा शीर्षक</div>
                <div class="meta">4 hours ago</div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <aside>
        <div class="card">
          <h4 style="margin:0 0 8px 0">Categories</h4>
          <div class="categories">
            <div class="cat">India</div><div class="cat">World</div><div class="cat">Business</div>
            <div class="cat">Tech</div><div class="cat">Entertainment</div><div class="cat">Sports</div>
          </div>
        </div>

        <div class="card" style="margin-top:12px">
          <h4 style="margin:0 0 8px 0">Trending</h4>
          <ol style="padding-left:18px;margin:0;color:#333">
            <li>टॉप ट्रेंडिंग खबर 1</li>
            <li>टॉप ट्रेंडिंग खबर 2</li>
            <li>टॉप ट्रेंडिंग खबर 3</li>
          </ol>
        </div>
      </aside>
    </section>

    <footer>
      © 2025 India News — Designed by you. All rights reserved.
    </footer>
  </main>
</body>
</html>
