# SSEF-LEET — Programming Community

<p align="center">
  <b>فارسی</b> · <a href="#english">English</a>
</p>

---

# 👋 خوش اومدید به ریپازیتوری گروه

سلام به همگی 🌱

از اونجایی که قرار شده هر هفته (یا بعضی وقتا دو بار در هفته) سوال‌های LeetCode رو با هم حل کنیم، تصمیم گرفتیم همه‌ی تمرین‌ها و راه‌حل‌هامون رو داخل یک ریپازیتوری GitHub نگهداری کنیم.

هدف این ریپازیتوری فقط آپلود کردن جواب سوال‌ها نیست؛ می‌خوایم یه آرشیو مرتب و تمیز داشته باشیم که هر کسی بتونه بعداً برگرده، راه‌حل‌های بقیه رو ببینه، ایده بگیره و روند پیشرفتش رو هم دنبال کنه.

پس قبل از اینکه اولین Pull Request خودتون رو باز کنید، لطفاً این راهنما رو یه بار بخونید.

### 🔀 چطور جواب آپلود کنیم؟ (مهم)

این ریپو **Public** است و اعضا مستقیم روی `main` پوش نمی‌زنند.

1. ریپو را **Fork** کنید  
2. روی **فورک خودتان** جواب را داخل `Members/<github-username>/` بگذارید  
3. به ریپوی اصلی **Pull Request** بزنید  

جزئیات کامل: [`CONTRIBUTING.md`](./CONTRIBUTING.md)

---

## 📂 ساختار ریپازیتوری

```text
SSEF-LEET/
├── README.md
├── CONTRIBUTING.md
├── LICENSE
├── Problems/          # سوال‌های هفتگی (فقط ادمین)
│   └── 2026/
│       └── Week-01-Fizz-Buzz/
├── Members/           # جواب‌های اعضا
├── Templates/         # قالب README
└── .github/           # قالب Issue و Pull Request
```

### 📌 پوشه `Problems`

داخل این پوشه، سوال‌های هر هفته قرار می‌گیرن. هر هفته یک فولدر جدید ساخته می‌شه.

مثال:

```text
Problems/
└── 2026/
    └── Week-01-Fizz-Buzz/
```

داخل هر فولدر معمولاً این موارد وجود داره:

- توضیح سوال
- لینک LeetCode
- درجه سختی
- محدودیت‌ها (Constraints)
- مثال‌ها
- اگر لازم باشه، چند نکته یا راهنمایی

**نیازی نیست داخل این پوشه چیزی تغییر بدید.**  
این قسمت فقط توسط ادمین یا مسئول‌های ریپازیتوری مدیریت می‌شه.

### 👤 پوشه `Members`

این قسمت مهم‌ترین بخش برای شماست. هر عضو گروه یک پوشه مخصوص به خودش داره.

```text
Members/
├── your-github-username/
├── …
```

اگر هنوز پوشه‌ای به اسم خودتون وجود نداره، فقط یک بار اون رو ایجاد کنید و از اون به بعد همیشه جواب‌هاتون رو داخل همون قرار بدید.

**ترجیحاً اسم پوشه همون Username گیت‌هابتون باشه** تا همه راحت‌تر بتونن پیداتون کنن.

### 📅 جواب سوال‌های هر هفته

داخل پوشه‌ی خودتون، برای هر هفته یک فولدر جدا بسازید:

```text
Members/
└── Soohimi/
    ├── Week-01/
    ├── Week-02/
    └── Week-03/
```

داخل هر هفته:

```text
Week-01/
├── solution.js
└── README.md
```

اگر سوال رو با چند زبان حل کردید، مشکلی نیست:

```text
Week-05/
├── solution.py
├── solution.cpp
├── solution.js
└── README.md
```

### 📝 فایل README کنار جواب

اگر دوست داشتید (و ترجیحاً این کار رو انجام بدید)، کنار هر جواب یک `README.md` بذارید و خیلی خلاصه بنویسید:

- راه‌حلتون چی بوده
- از چه الگوریتم یا دیتا استراکچری استفاده کردید
- Time Complexity
- Space Complexity

حتی چند خط هم کافیه. قالب آماده: [`Templates/Solution-README.md`](./Templates/Solution-README.md)

---

## ❌ لطفاً این کارها رو انجام ندید

- پوشه یا فایل بقیه رو تغییر ندید.
- اسم پوشه‌ها رو عوض نکنید.
- ساختار ریپازیتوری رو بدون هماهنگی تغییر ندید.
- فایل‌های غیرمرتبط داخل ریپو قرار ندید.
- اگر فکر می‌کنید ساختار نیاز به تغییر داره، اول داخل گروه مطرح کنید.

## ✅ قبل از باز کردن Pull Request

- کدتون اجرا می‌شه.
- فایل‌ها فقط داخل پوشه خودتون در **فورک** قرار گرفتن.
- اسم پوشه‌ها درست نوشته شده (`Week-01`, `Week-02`, …).
- فورکتون را با ریپوی اصلی همگام کردید (`upstream`).

همین چند مورد ساده باعث می‌شه کمتر به Merge Conflict بخوریم.

---

## 🤝 هدف این ریپازیتوری رقابت نیست

قرار نیست همه دقیقاً یک جواب بنویسن. جذابیت این پروژه اینه که هر نفر ممکنه از یه روش متفاوت استفاده کنه.

پس حتماً:

- جواب بقیه رو ببینید.
- سوال بپرسید.
- اگر راه بهتری پیدا کردید پیشنهاد بدید.
- اگر کسی مشکلی داشت کمکش کنید.

همه اینجا هستیم که کنار هم یاد بگیریم.

## ❤️ حرف آخر

اشتباه کردن طبیعیه. قرار نیست همه از روز اول بهترین راه‌حل رو بنویسن. مهم اینه که هر هفته یه قدم جلوتر از هفته قبل باشیم.

امیدواریم این ریپازیتوری تبدیل بشه به یه مرجع خوب از راه‌حل‌های مختلف.  
موفق باشید و حسابی کد بزنید! 🚀

---

<a id="english"></a>

# 👋 Welcome to the group repository

Hey everyone 🌱

We’re solving LeetCode problems together about once or twice a week, so we keep every problem and every solution in this GitHub repo.

This isn’t only about uploading answers. We want a clean archive you can revisit later — to read other people’s approaches, steal good ideas, and track your own progress.

Please read this guide once before your first pull request.

### 🔀 How do I upload a solution? (important)

This repo is **public**. Members do **not** push directly to `main`.

1. **Fork** this repository  
2. On **your fork**, put your solution under `Members/<github-username>/`  
3. Open a **Pull Request** into the main repo  

Full details: [`CONTRIBUTING.md`](./CONTRIBUTING.md)

---

## 📂 Repository structure

```text
SSEF-LEET/
├── README.md
├── CONTRIBUTING.md
├── LICENSE
├── Problems/          # Weekly problems (admins only)
│   └── 2026/
│       └── Week-01-Fizz-Buzz/
├── Members/           # Member solutions
├── Templates/         # README templates
└── .github/           # Issue & Pull Request templates
```

### 📌 `Problems`

Weekly challenges live here. Each week gets its own folder, for example:

```text
Problems/
└── 2026/
    └── Week-01-Fizz-Buzz/
```

A typical week folder includes the statement, LeetCode link, difficulty, constraints, examples, and optional hints.

**You don’t need to edit anything under `Problems/`.** Admins maintain that part.

### 👤 `Members`

This is your area. Each member has one personal folder:

```text
Members/
├── your-github-username/
├── …
```

Create it once if it doesn’t exist yet, then always put your solutions there.

**Prefer your GitHub username as the folder name** so people can find you easily.

### 📅 Weekly solutions

Inside your folder, create one folder per week:

```text
Members/
└── Soohimi/
    ├── Week-01/
    ├── Week-02/
    └── Week-03/
```

Example contents:

```text
Week-01/
├── solution.js
└── README.md
```

Multiple languages are fine:

```text
Week-05/
├── solution.py
├── solution.cpp
├── solution.js
└── README.md
```

### 📝 Solution README

Please (when you can) add a short `README.md` next to your code covering:

- Your approach
- Algorithm / data structure used
- Time complexity
- Space complexity

A few lines is enough. Template: [`Templates/Solution-README.md`](./Templates/Solution-README.md)

---

## ❌ Please don’t

- Change other people’s files or folders
- Rename folders casually
- Change the repo structure without discussion
- Commit unrelated files
- If you think the structure should change, raise it in the group first

## ✅ Before opening a Pull Request

- Your code runs
- Files are only under your own folder on **your fork**
- Week folder names match (`Week-01`, `Week-02`, …)
- Your fork is synced with the main repo (`upstream`)

This keeps merge conflicts down.

---

## 🤝 This is not a competition

Different solutions are the point. Read others’ work, ask questions, suggest improvements, and help when someone is stuck. We’re here to learn together.

## ❤️ Closing note

Mistakes are normal. You don’t need the perfect answer on day one — just one step better each week.

Let’s turn this repo into a solid reference of many approaches. Happy coding! 🚀
