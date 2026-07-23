# Contributing / راهنمای مشارکت

<p align="center">
  <b>فارسی</b> · <a href="#english">English</a>
</p>

---

## فارسی

از اینکه به جامعه ملحق شدید ممنونیم. این ریپو **عمومی (Public)** است؛ اعضا **دسترسی مستقیم برای Push روی `main` ندارند**.

راه مشارکت رسمی:

**Fork → تغییرات روی فورک خودتون → Pull Request به همین ریپو**

### مراحل قدم‌به‌قدم

1. روی صفحه ریپوی اصلی دکمه **Fork** را بزنید (یک کپی زیر اکانت خودتان ساخته می‌شود).
2. فورک خودتان را Clone کنید:

```bash
git clone https://github.com/<YOUR-USERNAME>/SSEF-LEET.git
cd SSEF-LEET
```

3. (پیشنهادی) ریپوی اصلی را به‌عنوان `upstream` اضافه کنید تا بتوانید آپدیت بگیرید:

```bash
git remote add upstream https://github.com/ArminShaikhy/SSEF-LEET.git
```

4. قبل از کار جدید، فورک را با ریپوی اصلی همگام کنید:

```bash
git fetch upstream
git checkout main
git merge upstream/main
```

5. فقط داخل پوشه خودتان کار کنید:

```text
Members/<github-username>/
  Week-01/
    solution.<ext>
    README.md
```

6. Commit و Push روی **فورک خودتان**:

```bash
git add Members/<github-username>/
git commit -m "feat(<username>): Week-01 Fizz Buzz"
git push origin main
```

7. در GitHub روی فورک خودتان **Open pull request** بزنید و PR را به  
   `ArminShaikhy/SSEF-LEET` → شاخه `main` بفرستید.

### قوانین مهم

1. **یک نفر = یک پوشه** — `Members/<github-username>/`
2. **یک هفته = یک پوشه** — شماره هفته با `Problems/` یکی باشد
3. **README کوتاه** — ترجیحاً از [`Templates/Solution-README.md`](./Templates/Solution-README.md)
4. ترجیحاً **هر PR مربوط به یک هفته** باشد

### انجام بدید / انجام ندید

| انجام بدید | انجام ندید |
| --- | --- |
| فقط داخل پوشه خودتون تغییر بدید | فایل/پوشه بقیه رو دست نزنید |
| از Fork + Pull Request استفاده کنید | مستقیم روی ریپوی اصلی Push نکنید |
| پیام کامیت واضح بنویسید | فایل‌های غیرمرتبط، باینری، یا secret نذارید |
| در ریویو محترمانه باشید | روش بقیه رو تمسخر نکنید |

### عنوان Pull Request

مثال‌ها:

- `feat(soohimi): Week-01 Fizz Buzz`
- `fix(sara): Week-01 Fizz Buzz`

### اضافه کردن سوال جدید (فقط ادمین)

```text
Problems/YYYY/Week-XX-Problem-Name/
  README.md      # از Templates/Problem-README.md
  assets/        # در صورت نیاز
```

### سوال دارید؟

از قالب‌های Issue داخل `.github/ISSUE_TEMPLATE/` استفاده کنید، یا داخل گروه بپرسید.

---

<a id="english"></a>

## English

Thanks for joining. This repository is **public**. Members do **not** push directly to `main` on the main repo.

The official contribution path is:

**Fork → work on your fork → open a Pull Request into this repo**

### Step by step

1. Click **Fork** on the main repo page (creates a copy under your account).
2. Clone **your fork**:

```bash
git clone https://github.com/<YOUR-USERNAME>/SSEF-LEET.git
cd SSEF-LEET
```

3. (Recommended) Add the original repo as `upstream` so you can sync:

```bash
git remote add upstream https://github.com/ArminShaikhy/SSEF-LEET.git
```

4. Before new work, sync your fork with the main repo:

```bash
git fetch upstream
git checkout main
git merge upstream/main
```

5. Work only under your own folder:

```text
Members/<github-username>/
  Week-01/
    solution.<ext>
    README.md
```

6. Commit and push to **your fork**:

```bash
git add Members/<github-username>/
git commit -m "feat(<username>): Week-01 Fizz Buzz"
git push origin main
```

7. On GitHub, open a **Pull Request** from your fork into  
   `ArminShaikhy/SSEF-LEET` → `main`.

### Rules

1. **One person = one folder** — `Members/<github-username>/`
2. **One week = one folder** — week number must match `Problems/`
3. **Short README** — Prefer [`Templates/Solution-README.md`](./Templates/Solution-README.md)
4. Prefer **one week per PR**

### Do / Don’t

| Do | Don’t |
| --- | --- |
| Change only your own member folder | Edit other members’ files |
| Use Fork + Pull Request | Push directly to the main repository |
| Write clear commit messages | Commit unrelated files, binaries, or secrets |
| Be respectful in reviews | Mock other people’s approaches |

### Pull request titles

Examples:

- `feat(soohimi): Week-01 Fizz Buzz`
- `fix(sara): Week-01 Fizz Buzz`

### Adding a new weekly problem (admins)

```text
Problems/YYYY/Week-XX-Problem-Name/
  README.md      # from Templates/Problem-README.md
  assets/        # if needed
```

### Questions?

Use the issue templates under `.github/ISSUE_TEMPLATE/`, or ask in the group chat.
