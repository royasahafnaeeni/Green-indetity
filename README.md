<!doctype html>
<html lang="fa" dir="rtl">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<meta name="theme-color" content="#174b38">
<title>هویت سبز | آرشیو مدرسه</title>
<style>
:root{--forest:#174b38;--forest2:#23684d;--sage:#dce9df;--cream:#f7f7f1;--ink:#20332a;--muted:#6c7b72;--line:#e4e9e3;--card:#fff;--accent:#8cae78;--shadow:0 10px 30px #173b2810}
*{box-sizing:border-box}body{margin:0;background:var(--cream);color:var(--ink);font-family:Tahoma,"Segoe UI",sans-serif}button,input,select,textarea{font:inherit}button{cursor:pointer}
.app{min-height:100vh;display:grid;grid-template-columns:260px 1fr}.side{background:var(--forest);color:#fff;padding:24px 16px;display:flex;flex-direction:column;gap:22px}.brand{display:flex;align-items:center;gap:12px;padding:4px 8px}.logo{width:48px;height:48px;border-radius:15px;background:#ffffff1c;display:grid;place-items:center;overflow:hidden;font-size:26px}.logo img{width:100%;height:100%;object-fit:cover}.brand h1{font-size:19px;margin:0}.brand small{display:block;color:#c8ddce;margin-top:5px;font-size:11px;letter-spacing:.4px}.nav{display:grid;gap:7px}.nav button{border:0;background:transparent;color:#e4eee7;text-align:right;padding:12px 14px;border-radius:12px;display:flex;align-items:center;gap:11px}.nav button.active,.nav button:hover{background:#ffffff1c;color:#fff}.nav .ico{font-size:18px;width:22px;text-align:center}.side-note{margin-top:auto;color:#c8ddce;font-size:11px;line-height:1.9;padding:12px}
main{padding:28px 34px;max-width:1500px;width:100%;margin:auto}.top{display:flex;justify-content:space-between;align-items:center;gap:16px;margin-bottom:26px}.eyebrow{font-size:12px;color:var(--muted);margin-bottom:7px}.top h2{margin:0;font-size:25px}.actions{display:flex;gap:9px;flex-wrap:wrap}.btn{border:1px solid var(--line);background:#fff;color:var(--ink);padding:10px 14px;border-radius:11px;font-size:13px}.btn.primary{background:var(--forest);border-color:var(--forest);color:white}.btn.soft{background:var(--sage);border-color:var(--sage);color:var(--forest)}
.hero{background:linear-gradient(115deg,#174b38,#327454);color:white;border-radius:20px;padding:25px 28px;display:flex;justify-content:space-between;align-items:center;gap:20px;margin-bottom:20px;box-shadow:var(--shadow)}.hero h3{font-size:22px;margin:0 0 9px}.hero p{color:#e0eee4;margin:0;font-size:13px;line-height:1.9}.hero-mark{font-size:54px;opacity:.9}
.stats{display:grid;grid-template-columns:repeat(4,1fr);gap:13px;margin-bottom:22px}.stat,.panel,.tile{background:var(--card);border:1px solid var(--line);border-radius:16px;box-shadow:var(--shadow)}.stat{padding:17px}.stat .label{font-size:12px;color:var(--muted)}.stat strong{display:block;font-size:28px;margin-top:10px;color:var(--forest)}.stat .hint{font-size:11px;color:var(--muted);margin-top:4px}
.section-head{display:flex;justify-content:space-between;align-items:center;margin:24px 0 12px;gap:12px}.section-head h3{font-size:16px;margin:0}.section-head p{font-size:11px;color:var(--muted);margin:5px 0 0}
.tiles{display:grid;grid-template-columns:repeat(4,1fr);gap:13px}.tile{padding:17px;text-align:right;border:1px solid var(--line);color:var(--ink);display:block;width:100%}.tile:hover{border-color:#9db9a1;transform:translateY(-1px)}.tile .symbol{font-size:23px}.tile b{display:block;margin:10px 0 5px;font-size:13px}.tile small{color:var(--muted);font-size:11px}
.panel{padding:20px}.empty{padding:30px 15px;text-align:center;color:var(--muted);font-size:13px}.empty .big{font-size:32px;margin-bottom:8px}
.activity-list{display:grid;gap:10px}.activity{display:flex;align-items:center;justify-content:space-between;gap:12px;border:1px solid var(--line);padding:13px;border-radius:12px}.activity b{font-size:13px}.activity small{display:block;color:var(--muted);margin-top:5px;font-size:11px}.pill{font-size:10px;background:var(--sage);color:var(--forest);padding:6px 9px;border-radius:30px;white-space:nowrap}
.page{display:none}.page.active{display:block}
.form-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:14px}.field{display:grid;gap:7px}.field.full{grid-column:1/-1}.field label{font-size:12px;color:var(--muted)}.field input,.field select,.field textarea{width:100%;border:1px solid var(--line);border-radius:10px;padding:11px;background:#fff;color:var(--ink);outline-color:#8eaf8f}.field textarea{min-height:90px;resize:vertical}.upload{border:1.5px dashed #a8bca9;border-radius:13px;padding:18px;background:#f9fbf8}.upload input{border:0;padding:0;background:transparent}.file-note{font-size:11px;color:var(--muted);margin-top:8px;line-height:1.8}
.gallery{display:grid;grid-template-columns:repeat(4,1fr);gap:12px}.media{border:1px solid var(--line);border-radius:12px;overflow:hidden;background:#fff}.media img,.media video{width:100%;height:135px;object-fit:cover;background:#e9eee8}.media div{padding:9px;font-size:11px;overflow-wrap:anywhere}
.settings-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:14px}
.toast{position:fixed;bottom:20px;left:20px;background:#173f32;color:#fff;padding:12px 16px;border-radius:12px;box-shadow:var(--shadow);display:none;z-index:20;font-size:13px}
.modal{position:fixed;inset:0;background:#10271dcc;display:none;align-items:center;justify-content:center;padding:18px;z-index:10}.modal.show{display:flex}.modal-card{background:#fff;border-radius:18px;padding:22px;width:min(720px,100%);max-height:90vh;overflow:auto}.modal-head{display:flex;justify-content:space-between;align-items:center;margin-bottom:18px}.modal-head h3{margin:0}.close{border:0;background:#eef3ee;border-radius:9px;padding:7px 11px}
footer{color:var(--muted);font-size:10px;margin-top:28px;line-height:1.8}
[dir="ltr"] .nav button,[dir="ltr"] .tile{text-align:left}[dir="ltr"] .activity{direction:ltr}
@media(max-width:950px){.app{grid-template-columns:1fr}.side{padding:12px 14px;gap:10px}.brand{padding:3px 5px}.nav{display:flex;overflow:auto;gap:5px}.nav button{white-space:nowrap;padding:9px 11px;font-size:12px}.side-note{display:none}main{padding:20px 17px}.tiles{grid-template-columns:repeat(2,1fr)}}
@media(max-width:600px){.top{align-items:flex-start;flex-direction:column}.top h2{font-size:21px}.hero{padding:20px}.hero h3{font-size:18px}.hero-mark{font-size:40px}.stats{grid-template-columns:repeat(2,1fr)}.gallery{grid-template-columns:repeat(2,1fr)}.form-grid,.settings-grid{grid-template-columns:1fr}.field.full{grid-column:auto}.actions{width:100%}.actions .btn{flex:1}}
</style>
</head>
<body>
<div class="app">
<aside class="side">
  <div class="brand"><div class="logo" id="brandLogo">🌿</div><div><h1 id="brandName">هویت سبز</h1><small>GREEN IDENTITY ARCHIVE</small></div></div>
  <nav class="nav" id="nav">
    <button class="active" data-page="home"><span class="ico">⌂</span><span data-fa="نمای کلی" data-en="Overview">نمای کلی</span></button>
    <button data-page="goals"><span class="ico">◎</span><span data-fa="اهداف طرح" data-en="Program goals">اهداف طرح</span></button>
    <button data-page="activities"><span class="ico">▤</span><span data-fa="فعالیت‌ها" data-en="Activities">فعالیت‌ها</span></button>
    <button data-page="gallery"><span class="ico">▧</span><span data-fa="آرشیو رسانه" data-en="Media archive">آرشیو رسانه</span></button>
    <button data-page="reports"><span class="ico">▥</span><span data-fa="گزارش عملکرد" data-en="Reports">گزارش عملکرد</span></button>
    <button data-page="settings"><span class="ico">⚙</span><span data-fa="تنظیمات و پشتیبان" data-en="Settings & backup">تنظیمات و پشتیبان</span></button>
  </nav>
  <div class="side-note" data-fa="نمایش عمومی و مدیریت آنلاین · داده‌ها در پایگاه داده مدرسه نگهداری می‌شوند." data-en="Offline prototype · Data is stored in this browser. Create backups regularly.">نمایش عمومی و مدیریت آنلاین · داده‌ها در پایگاه داده مدرسه نگهداری می‌شوند.</div>
</aside>
<main>
  <div class="top"><div><div class="eyebrow" id="dateLabel">آرشیو مدرسه · نسخه اولیه</div><h2 id="pageTitle">نمای کلی</h2></div><div class="actions"><button class="btn" id="langBtn">English</button><button class="btn" id="authBtn">ورود / حساب کاربری</button><button class="btn primary" id="quickAdd" hidden>＋ ثبت فعالیت</button></div></div>

  <section class="page active" id="page-home">
    <div class="hero"><div><h3 data-fa="مدرسه‌ای برای آینده‌ای سبزتر" data-en="A greener school, a better future">مدرسه‌ای برای آینده‌ای سبزتر</h3><p data-fa="اهداف، فعالیت‌ها و مستندات محیط‌زیستی مدرسه؛ ساده، منظم و در دسترس." data-en="School sustainability goals, activities and evidence — clear, organized and accessible.">اهداف، فعالیت‌ها و مستندات محیط‌زیستی مدرسه؛ ساده، منظم و در دسترس.</p></div><div class="hero-mark">🌱</div></div>
    <div class="stats">
      <div class="stat"><div class="label" data-fa="فعالیت‌های ثبت‌شده" data-en="Activities recorded">فعالیت‌های ثبت‌شده</div><strong id="statActivities">۰</strong><div class="hint" data-fa="تمام پرونده‌های اجرایی" data-en="All activity records">تمام پرونده‌های اجرایی</div></div>
      <div class="stat"><div class="label" data-fa="اهداف تعریف‌شده" data-en="Goals defined">اهداف تعریف‌شده</div><strong id="statGoals">۴</strong><div class="hint" data-fa="چهار محور پیشنهادی" data-en="Four suggested pillars">چهار محور پیشنهادی</div></div>
      <div class="stat"><div class="label" data-fa="فایل‌های مستندات" data-en="Evidence files">فایل‌های مستندات</div><strong id="statFiles">۰</strong><div class="hint" data-fa="عکس، ویدئو و سند" data-en="Photos, videos and documents">عکس، ویدئو و سند</div></div>
      <div class="stat"><div class="label" data-fa="فعالیت‌های تکمیل‌شده" data-en="Completed activities">فعالیت‌های تکمیل‌شده</div><strong id="statDone">۰</strong><div class="hint" data-fa="بر اساس وضعیت پرونده‌ها" data-en="Based on record status">بر اساس وضعیت پرونده‌ها</div></div>
    </div>
    <div class="section-head"><div><h3 data-fa="شروع سریع" data-en="Quick actions">شروع سریع</h3><p data-fa="برای هر کار، مسیر مشخصی در نظر گرفته شده است." data-en="A clear place for every task.">برای هر کار، مسیر مشخصی در نظر گرفته شده است.</p></div></div>
    <div class="tiles">
      <button class="tile" data-goto="activities"><span class="symbol">📝</span><b data-fa="ثبت فعالیت جدید" data-en="Add an activity">ثبت فعالیت جدید</b><small data-fa="شرح کار و نتیجه اجرا" data-en="Describe action and result">شرح کار و نتیجه اجرا</small></button>
      <button class="tile" data-goto="gallery"><span class="symbol">📷</span><b data-fa="مشاهده عکس و فیلم‌ها" data-en="Browse photos & videos">مشاهده عکس و فیلم‌ها</b><small data-fa="آرشیو همه مستندات" data-en="Browse all evidence">آرشیو همه مستندات</small></button>
      <button class="tile" data-goto="goals"><span class="symbol">🎯</span><b data-fa="مشاهده اهداف طرح" data-en="View program goals">مشاهده اهداف طرح</b><small data-fa="چه چیزی باید محقق شود؟" data-en="What are we working toward?">چه چیزی باید محقق شود؟</small></button>
      <button class="tile" data-goto="reports"><span class="symbol">📊</span><b data-fa="گزارش و خروجی" data-en="Reports & export">گزارش و خروجی</b><small data-fa="نمایش روشن عملکرد" data-en="Clear performance overview">نمایش روشن عملکرد</small></button>
    </div>
    <div class="section-head"><div><h3 data-fa="آخرین فعالیت‌ها" data-en="Recent activities">آخرین فعالیت‌ها</h3><p data-fa="آخرین پرونده‌هایی که ثبت کرده‌اید." data-en="Your latest records.">آخرین پرونده‌هایی که ثبت کرده‌اید.</p></div><button class="btn" data-goto="activities" data-fa="مشاهده همه" data-en="View all">مشاهده همه</button></div>
    <div class="panel"><div id="recentList" class="activity-list"><div class="empty"><div class="big">🌿</div>هنوز فعالیتی ثبت نشده است. از دکمه «ثبت فعالیت» شروع کنید.</div></div></div>
  </section>

  <section class="page" id="page-goals">
    <div class="hero"><div><h3 data-fa="چهار ستون مدرسه سبز" data-en="Four pillars of a green school">چهار ستون مدرسه سبز</h3><p data-fa="چارچوب پیشنهادی برگرفته از رویکردهای بین‌المللی مدارس پایدار." data-en="A suggested framework inspired by international green-school approaches.">چارچوب پیشنهادی برگرفته از رویکردهای بین‌المللی مدارس پایدار.</p></div><div class="hero-mark">🎯</div></div>
    <div class="tiles">
      <div class="tile"><span class="symbol">🏫</span><b data-fa="مدیریت و راهبری" data-en="Governance">مدیریت و راهبری</b><small data-fa="سیاست‌ها، شورای سبز و برنامه‌ریزی" data-en="Policies, green team and planning">سیاست‌ها، شورای سبز و برنامه‌ریزی</small></div>
      <div class="tile"><span class="symbol">💧</span><b data-fa="امکانات و عملیات" data-en="Facilities & operations">امکانات و عملیات</b><small data-fa="آب، انرژی، پسماند و فضای سبز" data-en="Water, energy, waste and greenery">آب، انرژی، پسماند و فضای سبز</small></div>
      <div class="tile"><span class="symbol">📚</span><b data-fa="آموزش و یادگیری" data-en="Teaching & learning">آموزش و یادگیری</b><small data-fa="یادگیری محیط‌زیستی و پروژه‌های دانش‌آموزی" data-en="Environmental learning and student projects">یادگیری محیط‌زیستی و پروژه‌های دانش‌آموزی</small></div>
      <div class="tile"><span class="symbol">🤝</span><b data-fa="مشارکت اجتماعی" data-en="Community engagement">مشارکت اجتماعی</b><small data-fa="خانواده، محله و نهادهای همکار" data-en="Families, neighborhood and partners">خانواده، محله و نهادهای همکار</small></div>
    </div>
    <div class="section-head"><h3 data-fa="حوزه‌های اجرایی پیشنهادی" data-en="Suggested action areas">حوزه‌های اجرایی پیشنهادی</h3></div>
    <div class="panel" style="line-height:2.2;font-size:13px">تفکیک و کاهش پسماند · صرفه‌جویی آب و انرژی · تنوع زیستی و فضای سبز · تغذیه سالم · حمل‌ونقل پایدار · آموزش و فرهنگ‌سازی · مشارکت خانواده‌ها</div>
  </section>

  <section class="page" id="page-activities">
    <div class="section-head"><div><h3 data-fa="پرونده فعالیت‌ها" data-en="Activity records">پرونده فعالیت‌ها</h3><p data-fa="هر اقدام مدرسه را به‌صورت یک پرونده مستقل ثبت کنید." data-en="Keep each school action as a separate record.">هر اقدام مدرسه را به‌صورت یک پرونده مستقل ثبت کنید.</p></div><button class="btn primary" id="addActivity">＋ فعالیت جدید</button></div>
    <div class="panel"><div id="allActivities" class="activity-list"><div class="empty">هنوز پرونده‌ای ثبت نشده است.</div></div></div>
  </section>

  <section class="page" id="page-gallery">
    <div class="section-head"><div><h3 data-fa="آرشیو عکس، فیلم و اسناد" data-en="Photos, videos & documents">آرشیو عکس، فیلم و اسناد</h3><p data-fa="رسانه‌ها هنگام ثبت هر فعالیت به همان پرونده پیوند می‌خورند." data-en="Files are attached to their activity record.">رسانه‌ها هنگام ثبت هر فعالیت به همان پرونده پیوند می‌خورند.</p></div></div>
    <div class="panel"><div id="galleryGrid" class="gallery"><div class="empty">هنوز فایلی بارگذاری نشده است.</div></div></div>
  </section>

  <section class="page" id="page-reports">
    <div class="section-head"><div><h3 data-fa="گزارش عملکرد" data-en="Performance report">گزارش عملکرد</h3><p data-fa="خلاصه شفاف از پرونده‌های ثبت‌شده." data-en="A clear summary of recorded activities.">خلاصه شفاف از پرونده‌های ثبت‌شده.</p></div><button class="btn primary" id="printReport">چاپ / ذخیره PDF</button></div>
    <div class="stats">
      <div class="stat"><div class="label">کل فعالیت‌ها</div><strong id="rTotal">۰</strong></div>
      <div class="stat"><div class="label">تکمیل‌شده</div><strong id="rDone">۰</strong></div>
      <div class="stat"><div class="label">در حال اجرا</div><strong id="rProgress">۰</strong></div>
      <div class="stat"><div class="label">مستندات</div><strong id="rFiles">۰</strong></div>
    </div>
    <div class="panel"><h3 style="font-size:14px">فهرست فعالیت‌ها</h3><div id="reportList" class="activity-list"></div><p class="file-note">برای خروجی PDF از گزینه چاپ مرورگر، مقصد «Save as PDF / ذخیره به‌صورت PDF» را انتخاب کنید.</p></div>
  </section>

  <section class="page" id="page-settings">
    <div class="section-head"><div><h3 data-fa="تنظیمات و پشتیبان‌گیری" data-en="Settings & backup">تنظیمات و پشتیبان‌گیری</h3><p data-fa="هویت مدرسه را شخصی‌سازی و از آرشیو محافظت کنید." data-en="Personalize your school identity and protect your archive.">هویت مدرسه را شخصی‌سازی و از آرشیو محافظت کنید.</p></div></div>
    <div class="settings-grid">
      <div class="panel">
        <h3 style="font-size:14px;margin-top:0" data-fa="هویت مدرسه" data-en="School identity">هویت مدرسه</h3>
        <div class="field"><label data-fa="نام مدرسه" data-en="School name">نام مدرسه</label><input id="schoolName" placeholder="نام مدرسه"></div><br>
        <div class="field"><label data-fa="بارگذاری لوگو" data-en="Upload logo">بارگذاری لوگو</label><input id="logoInput" type="file" accept="image/*"></div><br>
        <button class="btn primary" id="saveIdentity">ذخیره تغییرات</button>
      </div>
      <div class="panel">
        <h3 style="font-size:14px;margin-top:0" data-fa="پشتیبان‌گیری کامل" data-en="Full backup">پشتیبان‌گیری کامل</h3>
        <p style="font-size:12px;line-height:1.9;color:var(--muted)" data-fa="یک نسخه از اطلاعات و فایل‌های بارگذاری‌شده تهیه کنید و در حافظه‌ای جداگانه نگه دارید." data-en="Export your records and uploaded files, then keep the backup on a separate drive.">یک نسخه از اطلاعات و فایل‌های بارگذاری‌شده تهیه کنید و در حافظه‌ای جداگانه نگه دارید.</p>
        <button class="btn primary" id="backupBtn">⬇ دریافت نسخه پشتیبان</button><hr style="border:0;border-top:1px solid var(--line);margin:17px 0">
        <div class="field"><label data-fa="بازیابی نسخه پشتیبان" data-en="Restore backup">بازیابی نسخه پشتیبان</label><input id="restoreInput" type="file" accept=".json,application/json"></div><br>
        <button class="btn" id="restoreBtn">بازیابی آرشیو</button>
      </div>
      <div class="panel">
        <h3 style="font-size:14px;margin-top:0">ظاهر و زبان | Appearance & language</h3>
        <div class="field"><label data-fa="رنگ اصلی" data-en="Main color">رنگ اصلی</label><select id="themeColor"><option value="#174b38">سبز جنگلی</option><option value="#476b4b">سبز زیتونی</option><option value="#236c70">سبز فیروزه‌ای</option></select></div><br>
        <button class="btn" id="applyTheme">اعمال رنگ</button>
      </div>
      <div class="panel">
        <h3 style="font-size:14px;margin-top:0">راهنمای نگهداری</h3>
        <p style="font-size:12px;line-height:2;color:var(--muted)">۱. مرتب نسخه پشتیبان بگیرید.<br>۲. نسخه پشتیبان را روی فلش یا هارد جداگانه نگه دارید.<br>۳. حافظه مرورگر را پاک نکنید مگر اینکه نسخه پشتیبان داشته باشید.<br>۴. برای انتقال به دستگاه دیگر، ابتدا پشتیبان بگیرید و سپس آن را بازیابی کنید.</p>
      </div>
    </div>
  </section>
  <footer>اتصال آزمایشی به پایگاه داده آنلاین هویت سبز · دسترسی مدیریتی نیازمند ورود است.</footer>
</main>
</div>

<div class="modal" id="activityModal"><div class="modal-card">
  <div class="modal-head"><h3 id="modalTitle">ثبت فعالیت جدید</h3><button class="close" id="closeModal">✕</button></div>
  <form id="activityForm">
    <div class="form-grid">
      <div class="field full"><label>عنوان فعالیت *</label><input id="aTitle" required placeholder="مثلاً کاشت نهال در حیاط مدرسه"></div>
      <div class="field"><label>حوزه فعالیت</label><select id="aCategory"><option>مدیریت پسماند</option><option>آب و انرژی</option><option>فضای سبز و تنوع زیستی</option><option>آموزش محیط‌زیست</option><option>سلامت و تغذیه</option><option>مشارکت اجتماعی</option><option>مدیریت و راهبری</option><option>سایر</option></select></div>
      <div class="field"><label>تاریخ اجرا</label><input id="aDate" type="date"></div>
      <div class="field"><label>مسئول اجرا</label><input id="aOwner" placeholder="نام مسئول یا گروه"></div>
      <div class="field"><label>وضعیت</label><select id="aStatus"><option>در حال اجرا</option><option>تکمیل‌شده</option><option>برنامه‌ریزی‌شده</option></select></div>
      <div class="field full"><label>شرح فعالیت و هدف</label><textarea id="aDescription" placeholder="چه کاری انجام شد و با چه هدفی؟"></textarea></div>
      <div class="field full"><label>نتیجه و دستاورد</label><textarea id="aResult" placeholder="نتیجه قابل مشاهده یا عددی فعالیت"></textarea></div>
      <div class="field full"><label>افزودن عکس، فیلم یا سند</label><div class="upload"><input id="aFiles" type="file" multiple accept="image/*,video/*,.pdf,.doc,.docx,.xls,.xlsx"><div class="file-note">فایل‌ها در آرشیو محلی این مرورگر ذخیره می‌شوند. برای ویدئوهای حجیم، فضای دستگاه و امکان پشتیبان‌گیری را در نظر بگیرید.</div></div></div>
    </div><br><div class="actions"><button class="btn primary" type="submit">ذخیره پرونده فعالیت</button><button class="btn" type="button" id="cancelModal">انصراف</button></div>
  </form>
</div></div>
<div class="modal" id="authModal"><div class="modal-card" style="max-width:430px">
  <div class="modal-head"><h3>ورود کاربران هویت سبز</h3><button class="close" id="closeAuth">✕</button></div>
  <form id="loginForm"><div class="field"><label>ایمیل</label><input id="loginEmail" type="email" required autocomplete="username" placeholder="name@example.com"></div><br>
  <div class="field"><label>رمز عبور</label><input id="loginPassword" type="password" required autocomplete="current-password"></div><br>
  <button class="btn primary" type="submit">ورود امن</button><p class="file-note">حساب شما پس از ورود، بر اساس نقش ثبت‌شده در سامانه دسترسی می‌گیرد. فقط مدیر اصلی امکان ویرایش دارد؛ سایر کاربران فقط مشاهده می‌کنند.</p></form>
</div></div>
<div class="toast" id="toast"></div>
<script src="https://cdn.jsdelivr.net/npm/@supabase/supabase-js@2"></script>
<script>
const SUPABASE_URL='https://fzshwjuxdsezdbgdydid.supabase.co';
const SUPABASE_KEY='sb_publishable_gsLXIsHl0dHfBlns9m07bA_r2JxVFW0';
const sb=window.supabase.createClient(SUPABASE_URL,SUPABASE_KEY);
let activities=[], goals=[], attachments=[], lang='fa', editingId=null, pendingLogo=null, currentUser=null, currentProfile=null;
const $=id=>document.getElementById(id);
// تنها حساب دارای نقش admin و وضعیت فعال اجازه تغییر داده‌ها را دارد.
const canEdit=()=>!!currentUser && !!currentProfile?.is_active && currentProfile?.role==='admin';
const isAdmin=()=>canEdit() && currentProfile.role==='admin';
function toast(s){$('toast').textContent=s;$('toast').style.display='block';setTimeout(()=>$('toast').style.display='none',3500)}
function fmt(n){return lang==='fa'?new Intl.NumberFormat('fa-IR').format(n):String(n)}
function esc(s=''){return String(s).replace(/[&<>"']/g,c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[c]))}
function go(page){document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));$('page-'+page).classList.add('active');document.querySelectorAll('.nav button').forEach(b=>b.classList.toggle('active',b.dataset.page===page));const labels={home:['نمای کلی','Overview'],goals:['اهداف طرح','Program goals'],activities:['فعالیت‌ها','Activities'],gallery:['آرشیو رسانه','Media archive'],reports:['گزارش عملکرد','Reports'],settings:['تنظیمات و پشتیبان','Settings & backup']};$('pageTitle').textContent=labels[page][lang==='fa'?0:1]}
function setEditorUI(){
 $('quickAdd').hidden=!canEdit();$('addActivity').hidden=!canEdit();$('saveIdentity').hidden=!canEdit();$('backupBtn').hidden=!canEdit();$('restoreBtn').hidden=!canEdit();$('restoreInput').disabled=!canEdit();$('logoInput').disabled=!canEdit();$('schoolName').disabled=!canEdit();
 $('authBtn').textContent=currentUser?`خروج (${canEdit()?'مدیر اصلی':'فقط مشاهده'})`:'ورود / حساب کاربری';
 $('dateLabel').textContent=currentUser?`${currentUser.email} · ${canEdit()?'مدیر اصلی · دسترسی ویرایش':(currentProfile?.is_active?'دسترسی فقط مشاهده':'حساب غیرفعال · نمایش عمومی')}`:'نمایش عمومی · محتوای منتشرشده';
}
async function loadIdentity(){const {data,error}=await sb.from('school_settings').select('school_name,logo_data_url').eq('id',true).maybeSingle();if(error){console.warn(error);return}if(data){$('brandName').textContent=data.school_name||'هویت سبز';$('schoolName').value=data.school_name||'';$('brandLogo').innerHTML=data.logo_data_url?`<img src="${data.logo_data_url}" alt="logo">`:'🌿'}}
async function loadData(){
 let aq=sb.from('activities').select('*').order('created_at',{ascending:false});
 if(!currentUser) aq=aq.eq('is_published',true);
 const [ar,gr]=await Promise.all([aq,sb.from('goals').select('*').order('created_at',{ascending:true})]);
 if(ar.error) throw ar.error;if(gr.error) throw gr.error;
 activities=ar.data||[];goals=currentUser?(gr.data||[]):(gr.data||[]).filter(g=>g.is_published);
 const ids=activities.map(a=>a.id);attachments=[];
 if(ids.length){let q=sb.from('activity_attachments').select('*').in('activity_id',ids);if(!currentUser)q=q.eq('is_public',true);const x=await q;if(x.error)throw x.error;attachments=x.data||[]}
 render();
}
function filesFor(id){return attachments.filter(x=>x.activity_id===id)}
function activityRow(a){const fs=filesFor(a.id);const controls=canEdit()?`<div style="display:flex;gap:7px;align-items:center;flex-wrap:wrap"><span class="pill">${a.is_published?'منتشرشده':'پیش‌نویس'}</span><button class="btn" onclick="editRecord('${a.id}')">ویرایش</button><button class="btn" onclick="togglePublish('${a.id}')">${a.is_published?'لغو انتشار':'انتشار'}</button><button class="btn" onclick="removeRecord('${a.id}')">حذف</button></div>`:`<span class="pill">${esc(a.status)}</span>`;
 return `<div class="activity"><div style="min-width:0"><b>${esc(a.title)}</b><small>${esc(a.category||'')} · ${esc(a.activity_date||'بدون تاریخ')} · ${esc(a.owner||'بدون مسئول')} · ${fmt(fs.length)} مستند</small>${a.description?`<small>${esc(a.description)}</small>`:''}${a.result?`<small>نتیجه: ${esc(a.result)}</small>`:''}</div>${controls}</div>`}
function render(){
 const done=activities.filter(a=>a.status==='تکمیل‌شده').length,files=attachments.length;
 $('statActivities').textContent=fmt(activities.length);$('statGoals').textContent=fmt(goals.length);$('statFiles').textContent=fmt(files);$('statDone').textContent=fmt(done);
 $('rTotal').textContent=fmt(activities.length);$('rDone').textContent=fmt(done);$('rProgress').textContent=fmt(activities.filter(a=>a.status==='در حال اجرا').length);$('rFiles').textContent=fmt(files);
 $('recentList').innerHTML=activities.length?activities.slice(0,4).map(activityRow).join(''):'<div class="empty">هنوز فعالیت منتشرشده‌ای وجود ندارد.</div>';
 $('allActivities').innerHTML=activities.length?activities.map(activityRow).join(''):'<div class="empty">هنوز پرونده‌ای برای نمایش وجود ندارد.</div>';
 $('reportList').innerHTML=activities.length?activities.map(a=>`<div class="activity"><div><b>${esc(a.title)}</b><small>${esc(a.category||'')} · ${esc(a.activity_date||'بدون تاریخ')}</small></div><span class="pill">${esc(a.status)}</span></div>`).join(''):'<div class="empty">گزارشی برای نمایش وجود ندارد.</div>';
 $('galleryGrid').innerHTML=attachments.length?attachments.map(f=>{const url=f._url||'';return `<div class="media">${f.mime_type?.startsWith('image/')?`<img src="${url}" alt="">`:f.mime_type?.startsWith('video/')?`<video src="${url}" controls></video>`:`<div style="height:135px;display:grid;place-items:center;font-size:34px">📄</div>`}<div><b>${esc(f.file_name)}</b><br><span style="color:#6c7b72">${esc(activities.find(a=>a.id===f.activity_id)?.title||'')}</span>${url?`<br><a href="${url}" target="_blank" rel="noopener">مشاهده / دریافت</a>`:''}</div></div>`}).join(''):'<div class="empty" style="grid-column:1/-1">هنوز مستندی برای نمایش وجود ندارد.</div>';
}
async function refresh(){await loadData();}
async function hydrateAttachmentUrls(){for(const f of attachments){if(f.bucket_id==='green-public'){const {data}=sb.storage.from(f.bucket_id).getPublicUrl(f.storage_path);f._url=data.publicUrl}else if(currentUser){const {data,error}=await sb.storage.from(f.bucket_id).createSignedUrl(f.storage_path,3600);if(!error)f._url=data.signedUrl}}}
async function reload(){await loadData();await hydrateAttachmentUrls();render()}
async function loadProfile(){if(!currentUser){currentProfile=null;setEditorUI();return}const {data,error}=await sb.from('profiles').select('id,full_name,role,is_active').eq('id',currentUser.id).maybeSingle();if(error)throw error;currentProfile=data;setEditorUI();if(!canEdit()&&data?.role!=='pending')toast('حساب شما فقط دسترسی مشاهده دارد؛ امکان ویرایش فعال نیست.');}
async function onAuthChanged(session){currentUser=session?.user||null;await loadProfile();await reload();}
window.editRecord=async id=>{if(!canEdit())return;const a=activities.find(x=>x.id===id);if(!a)return;editingId=id;$('activityForm').reset();$('modalTitle').textContent='ویرایش فعالیت';$('aTitle').value=a.title;$('aCategory').value=a.category||'سایر';$('aDate').value=a.activity_date||'';$('aOwner').value=a.owner||'';$('aStatus').value=a.status||'در حال اجرا';$('aDescription').value=a.description||'';$('aResult').value=a.result||'';$('activityModal').classList.add('show')};
window.removeRecord=async id=>{if(!canEdit()||!confirm('این پرونده و پیوست‌های آن حذف شود؟'))return;try{const fs=filesFor(id);for(const f of fs)await sb.storage.from(f.bucket_id).remove([f.storage_path]);const {error}=await sb.from('activities').delete().eq('id',id);if(error)throw error;await reload();toast('پرونده حذف شد.')}catch(e){toast('خطا در حذف: '+e.message)}};
window.togglePublish=async id=>{if(!canEdit())return;const a=activities.find(x=>x.id===id);if(!a)return;try{const next=!a.is_published;const fs=filesFor(id);
 // Move evidence between private/public buckets so unpublished files are never publicly accessible.
 for(const f of fs){const target=next?'green-public':'green-private';if(f.bucket_id===target)continue;const {data:blob,error:de}=await sb.storage.from(f.bucket_id).download(f.storage_path);if(de)throw de;const newPath=f.storage_path;const {error:up}=await sb.storage.from(target).upload(newPath,blob,{contentType:f.mime_type||'application/octet-stream',upsert:true});if(up)throw up;const {error:mu}=await sb.from('activity_attachments').update({bucket_id:target,is_public:next}).eq('id',f.id);if(mu)throw mu;await sb.storage.from(f.bucket_id).remove([f.storage_path]);}
 const {error}=await sb.from('activities').update({is_published:next}).eq('id',id);if(error)throw error;await reload();toast(next?'فعالیت منتشر شد.':'انتشار فعالیت لغو شد.');}catch(e){toast('خطا در تغییر وضعیت انتشار: '+e.message)}};
function showModal(a=null){if(!canEdit())return;editingId=a?.id||null;$('activityForm').reset();$('modalTitle').textContent='ثبت فعالیت جدید';$('activityModal').classList.add('show')}
$('nav').addEventListener('click',e=>{const b=e.target.closest('button[data-page]');if(b)go(b.dataset.page)});document.querySelectorAll('[data-goto]').forEach(b=>b.addEventListener('click',()=>go(b.dataset.goto)));
$('quickAdd').onclick=$('addActivity').onclick=()=>showModal();$('closeModal').onclick=$('cancelModal').onclick=()=>$('activityModal').classList.remove('show');
$('activityForm').onsubmit=async e=>{e.preventDefault();if(!canEdit())return;try{const old=activities.find(a=>a.id===editingId);const payload={title:$('aTitle').value.trim(),category:$('aCategory').value,activity_date:$('aDate').value||null,owner:$('aOwner').value,status:$('aStatus').value,description:$('aDescription').value,result:$('aResult').value,created_by:currentUser.id};let id=editingId;if(id){const {error}=await sb.from('activities').update(payload).eq('id',id);if(error)throw error}else{const {data,error}=await sb.from('activities').insert(payload).select('id').single();if(error)throw error;id=data.id}
 for(const f of $('aFiles').files){const safe=f.name.replace(/[^\p{L}\p{N}._-]/gu,'_');const path=`${id}/${crypto.randomUUID()}-${safe}`;const bucket=old?.is_published?'green-public':'green-private';const {error:up}=await sb.storage.from(bucket).upload(path,f,{contentType:f.type||'application/octet-stream',upsert:false});if(up)throw up;const {error:meta}=await sb.from('activity_attachments').insert({activity_id:id,file_name:f.name,mime_type:f.type,file_size:f.size,bucket_id:bucket,storage_path:path,is_public:bucket==='green-public',uploaded_by:currentUser.id});if(meta)throw meta;}
 $('activityModal').classList.remove('show');await reload();toast('پرونده در پایگاه داده ذخیره شد.');}catch(err){toast('ذخیره ناموفق بود: '+err.message)}};
$('authBtn').onclick=async()=>{if(currentUser){if(confirm('از حساب کاربری خارج شوید؟')){await sb.auth.signOut();await onAuthChanged(null)}}else $('authModal').classList.add('show')};$('closeAuth').onclick=()=>$('authModal').classList.remove('show');
$('loginForm').onsubmit=async e=>{e.preventDefault();const {data,error}=await sb.auth.signInWithPassword({email:$('loginEmail').value.trim(),password:$('loginPassword').value});if(error){toast('ورود انجام نشد: '+error.message);return}$('authModal').classList.remove('show');$('loginPassword').value='';await onAuthChanged(data.session);toast('ورود انجام شد.')};
sb.auth.onAuthStateChange((_event,session)=>{setTimeout(()=>onAuthChanged(session).catch(e=>toast(e.message)),0)});
$('saveIdentity').onclick=async()=>{if(!canEdit())return;try{let logo=null;if($('logoInput').files[0]){const f=$('logoInput').files[0];logo=await new Promise((res,rej)=>{const r=new FileReader();r.onload=()=>res(r.result);r.onerror=rej;r.readAsDataURL(f)})}const patch={school_name:$('schoolName').value.trim(),updated_by:currentUser.id};if(logo)patch.logo_data_url=logo;const {error}=await sb.from('school_settings').update(patch).eq('id',true);if(error)throw error;await loadIdentity();toast('تنظیمات مدرسه ذخیره شد.')}catch(e){toast('ذخیره تنظیمات ناموفق بود: '+e.message)}};
$('applyTheme').onclick=()=>{document.documentElement.style.setProperty('--forest',$('themeColor').value);toast('رنگ اصلی تغییر کرد.')};
function download(name,blob){const a=document.createElement('a'),u=URL.createObjectURL(blob);a.href=u;a.download=name;a.click();setTimeout(()=>URL.revokeObjectURL(u),1500)}
$('backupBtn').onclick=async()=>{if(!canEdit())return;try{const payload={app:'GreenIdentityArchive',version:2,exportedAt:new Date().toISOString(),activities,goals,attachments,schoolName:$('schoolName').value};download('green-identity-cloud-backup-'+new Date().toISOString().slice(0,10)+'.json',new Blob([JSON.stringify(payload)],{type:'application/json'}));toast('نسخه پشتیبان اطلاعات متنی آماده شد؛ فایل‌های رسانه‌ای باید جداگانه از Storage دریافت شوند.')}catch(e){toast(e.message)}};
$('restoreBtn').onclick=async()=>{if(!canEdit())return;const f=$('restoreInput').files[0];if(!f){toast('ابتدا فایل پشتیبان JSON را انتخاب کنید.');return}if(!confirm('محتوای نسخه پشتیبان به آرشیو آنلاین منتقل شود؟ فعالیت‌ها به‌صورت پیش‌نویس وارد می‌شوند.'))return;try{const pack=JSON.parse(await f.text());if(pack.app!=='GreenIdentityArchive'||!Array.isArray(pack.activities))throw new Error('ساختار فایل پشتیبان معتبر نیست.');for(const old of pack.activities){const row={id:old.id,title:old.title||'فعالیت بدون عنوان',category:old.category||null,activity_date:old.date||null,owner:old.owner||null,status:old.status||'در حال اجرا',description:old.description||null,result:old.result||null,is_published:false,created_by:currentUser.id};const {error:ae}=await sb.from('activities').upsert(row,{onConflict:'id'});if(ae)throw ae;const {data:existing,error:qe}=await sb.from('activity_attachments').select('file_name').eq('activity_id',old.id);if(qe)throw qe;const known=new Set((existing||[]).map(x=>x.file_name));for(const f0 of (old.files||[])){if(known.has(f0.name))continue;const blob=await (await fetch(f0.data)).blob();const path=`${old.id}/${crypto.randomUUID()}-${f0.name.replace(/[^\p{L}\p{N}._-]/gu,'_')}`;const {error:ue}=await sb.storage.from('green-private').upload(path,blob,{contentType:f0.type||blob.type||'application/octet-stream',upsert:false});if(ue)throw ue;const {error:me}=await sb.from('activity_attachments').insert({activity_id:old.id,file_name:f0.name,mime_type:f0.type||blob.type,file_size:f0.size||blob.size,bucket_id:'green-private',storage_path:path,is_public:false,uploaded_by:currentUser.id});if(me)throw me;}}const settingsPatch={school_name:pack.settings?.schoolName||'سوشیانت دانش پویان',updated_by:currentUser.id};if(pack.settings?.logo)settingsPatch.logo_data_url=pack.settings.logo;const {error:se}=await sb.from('school_settings').update(settingsPatch).eq('id',true);if(se)throw se;await loadIdentity();await reload();toast('انتقال پشتیبان انجام شد؛ فعالیت‌ها پیش‌نویس باقی ماندند.')}catch(e){toast('انتقال پشتیبان ناموفق بود: '+e.message)}};$('printReport').onclick=()=>window.print();
$('langBtn').onclick=()=>{lang=lang==='fa'?'en':'fa';document.documentElement.lang=lang;document.documentElement.dir=lang==='fa'?'rtl':'ltr';document.querySelectorAll('[data-fa]').forEach(el=>el.textContent=el.dataset[lang]);$('langBtn').textContent=lang==='fa'?'English':'فارسی';go(document.querySelector('.nav button.active')?.dataset.page||'home')};
(async()=>{try{const {data:{session}}=await sb.auth.getSession();currentUser=session?.user||null;await loadProfile();await loadIdentity();await reload();setEditorUI();}catch(e){console.error(e);toast('اتصال به پایگاه داده برقرار نشد: '+e.message)}})();
</script>
<style>@media print{.side,.top .actions,.btn,footer{display:none!important}.app{display:block}main{padding:0}.page{display:none!important}#page-reports{display:block!important}.panel,.stat{box-shadow:none}}</style>
</body></html>
