# Portfolio Branch Page (HTML + Tailwind)

## Files
- `index.html` صفحة واحدة بدون هيدر/فوتر.
- `data.json` بيانات محوّلة من CSV.

## Expected JSON keys
- `branch_name` : اسم الفرع
- `annual_cost_total` : إجمالي التكلفة السنوية (رقم)
- `coverage_percent` : نسبة التغطية (35 أو 0.35)
- `cost_items` (اختياري) : بنود التكلفة السنوية [{name, amount}]
- `current_raised` (اختياري) : المتحقق الحالي في المحفظة

## Run
افتح `index.html` عبر أي سيرفر محلي (لأن fetch يحتاج http):
- VSCode Live Server
- أو `python -m http.server 5500` ثم افتح:
  http://localhost:5500
