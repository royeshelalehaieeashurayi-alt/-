<!DOCTYPE html>
<html lang="fa" dir="rtl">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>سایت بسته است</title>
    <meta
      name="description"
      content="به دلیل مشکلات داخلی این سایت بسته شده است و تا اطلاع بعدی برگردانده نمی‌شود."
    />
    <meta name="theme-color" content="#14120f" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Lalezar&family=Vazirmatn:wght@400;500;700&display=swap"
      rel="stylesheet"
    />
    <style>
      :root {
        --font-sans: Vazirmatn, "Tahoma", sans-serif;
        --font-display: Lalezar, Vazirmatn, serif;
        --color-ink: #14120f;
        --color-paper: #f3eee4;
        --color-seal: #9a2f2b;
        --color-muted: #6e675d;
        --color-line: #d9d0c3;
        --color-fg: #1c1914;
        --color-rule: rgb(243 238 228 / 0.08);
        --radius: 0.25rem;
      }

      html {
        color-scheme: dark;
        background: var(--color-ink);
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
      }

      body {
        margin: 0;
        min-height: 100dvh;
        font-family: var(--font-sans);
        color: var(--color-paper);
        background-color: var(--color-ink);
        background-image:
          linear-gradient(to left, var(--color-rule) 1px, transparent 1px),
          linear-gradient(to bottom, var(--color-rule) 1px, transparent 1px);
        background-size: 3rem 3rem;
      }

      .stage {
        min-height: 100dvh;
        display: flex;
        align-items: center;
        justify-content: center;
        padding: 2.5rem 1rem 2rem;
      }

      .bar {
        position: fixed;
        inset-inline: 0;
        top: 0;
        height: 0.25rem;
        background: var(--color-seal);
      }

      .sheet {
        width: min(100%, 36rem);
        background: var(--color-paper);
        color: var(--color-fg);
        border-radius: var(--radius);
        box-shadow: 0 1.5rem 4rem rgb(0 0 0 / 0.38);
        padding: 0.55rem;
        animation: sheet-in 420ms cubic-bezier(0.2, 0.7, 0.2, 1) both;
      }

      .sheet-frame {
        border: 1px solid var(--color-line);
        border-inline-start: 0.28rem solid var(--color-seal);
        padding: 1.35rem 1.25rem 1.15rem;
      }

      .sheet-head {
        display: flex;
        align-items: flex-start;
        justify-content: space-between;
        gap: 1rem;
        margin-bottom: 1.75rem;
      }

      .kicker {
        margin: 0;
        font-size: 0.8rem;
        font-weight: 700;
        color: var(--color-seal);
      }

      .meta {
        margin: 0.35rem 0 0;
        font-size: 0.8rem;
        font-weight: 500;
        color: var(--color-muted);
        font-variant-numeric: tabular-nums;
      }

      .stamp {
        flex: none;
        width: 4.75rem;
        height: 4.75rem;
        border-radius: 999px;
        border: 2px solid var(--color-seal);
        box-shadow: inset 0 0 0 1px var(--color-seal);
        color: var(--color-seal);
        display: grid;
        place-items: center;
        transform: rotate(-14deg);
        background: radial-gradient(
          circle at 50% 50%,
          transparent 58%,
          rgb(154 47 43 / 0.08) 59%
        );
      }

      .stamp span {
        font-family: var(--font-display);
        font-size: 1.35rem;
        line-height: 1;
      }

      .notice {
        margin: 0;
        font-size: 1.65rem;
        font-weight: 700;
        line-height: 1.55;
        text-wrap: balance;
      }

      .facts {
        margin: 1.6rem 0 0;
      }

      .facts > div {
        display: flex;
        align-items: center;
        justify-content: space-between;
        gap: 1rem;
        padding: 0.8rem 0;
        border-top: 1px solid var(--color-line);
      }

      .facts dt {
        margin: 0;
        font-size: 0.85rem;
        font-weight: 500;
        color: var(--color-muted);
      }

      .facts dd {
        margin: 0;
        font-size: 0.95rem;
        font-weight: 700;
      }

      .status {
        display: inline-flex;
        align-items: center;
        gap: 0.4rem;
      }

      .status svg {
        width: 1rem;
        height: 1rem;
        color: var(--color-seal);
      }

      .sheet-foot {
        display: flex;
        align-items: center;
        justify-content: space-between;
        gap: 0.75rem;
        margin-top: 1.15rem;
        padding-top: 0.85rem;
        border-top: 1px solid var(--color-line);
        font-size: 0.78rem;
        font-weight: 500;
        color: var(--color-muted);
      }

      .live {
        display: inline-flex;
        align-items: center;
        gap: 0.4rem;
        color: var(--color-seal);
        font-weight: 700;
      }

      .live i {
        width: 0.45rem;
        height: 0.45rem;
        border-radius: 999px;
        background: var(--color-seal);
      }

      @media (min-width: 40rem) {
        .sheet-frame {
          padding: 1.75rem 1.7rem 1.35rem;
        }

        .notice {
          font-size: 1.9rem;
        }
      }

      @media (prefers-reduced-motion: reduce) {
        .sheet {
          animation: none;
        }
      }

      @keyframes sheet-in {
        from {
          opacity: 0;
          transform: translateY(0.6rem);
        }
        to {
          opacity: 1;
          transform: none;
        }
      }
    </style>
  </head>
  <body>
    <main class="stage">
      <div class="bar"></div>
      <article class="sheet">
        <div class="sheet-frame">
          <header class="sheet-head">
            <div>
              <p class="kicker">اطلاعیه رسمی</p>
              <p class="meta">شماره ۱۴۰۵–۰۱ · ۱ آبان ۱۴۰۵</p>
            </div>
            <div class="stamp" aria-hidden="true">
              <span>بسته</span>
            </div>
          </header>

          <h1 class="notice">
            به دلیل مشکلات داخلی این سایت بسته شده است و تا اطلاع بعدی برگردانده
            نمی‌شود.
          </h1>

          <dl class="facts">
            <div>
              <dt>علت</dt>
              <dd>مشکلات داخلی</dd>
            </div>
            <div>
              <dt>وضعیت</dt>
              <dd class="status">
                <span>غیرفعال</span>
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24"
                  fill="none"
                  stroke="currentColor"
                  stroke-width="2"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  aria-hidden="true"
                >
                  <rect width="18" height="11" x="3" y="11" rx="2" ry="2"></rect>
                  <path d="M7 11V7a5 5 0 0 1 10 0v4"></path>
                </svg>
              </dd>
            </div>
            <div>
              <dt>بازگشت</dt>
              <dd>تا اطلاع بعدی</dd>
            </div>
          </dl>

          <footer class="sheet-foot">
            <span class="live">
              <i></i>
              سرویس متوقف است
            </span>
            <span>همه صفحات در دسترس نیستند</span>
          </footer>
        </div>
      </article>
    </main>
  </body>
</html>
