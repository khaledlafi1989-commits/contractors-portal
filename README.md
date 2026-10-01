# بوابة المقاولين الذكية

موقع ثابت (HTML/CSS/JS) منقول من Claude Artifact دون تغيير التصميم أو البيانات.

## التشغيل محليًا
    npm run dev        # http://localhost:3000

## النشر على Vercel
    npx vercel login
    npx vercel --prod

الإعدادات في `vercel.json` (المخرجات من مجلد `public`، بدون Framework).

## ملاحظة
ميزة "البحث الذكي بالذكاء الاصطناعي" تعتمد على بيئة claude.ai (`window.claude`)،
وعند عدم توفرها يخفيها الكود تلقائيًا ويبقى البحث اليدوي بالمعايير يعمل كاملاً.
