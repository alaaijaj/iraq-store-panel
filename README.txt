Iraq Store update:
- يدعم logo.png تلقائيًا إذا رفعته داخل public
- الديفلوبر يُسحب تلقائيًا من Discord عبر DEVELOPER_DISCORD_ID
- إذا فشل السحب يرجع إلى fallback من settings.json

ما تعدله:
1) .env:
DEVELOPER_DISCORD_ID=Your Discord User ID

2) إذا عندك لوجو:
ارفع public/logo.png

ثم اعمل Commit و Deploy latest commit
