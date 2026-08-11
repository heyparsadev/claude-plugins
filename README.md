# claude-plugins

**پلاگین‌های Claude Code — نوشتهٔ پارسا.** اعتبارسنجی ایده، استراتژی کسب‌وکار، و طراحی iOS. هر سه از یک مارکت‌پلیس نصب می‌شن.

Claude Code plugins by Parsa — startup validation, business strategy, and iOS design tooling. All three install from one marketplace.

---

## نصب / Install

از داخل Claude Code (توصیه‌شده) / From inside Claude Code (recommended):

```
/plugin marketplace add https://github.com/heyparsadev/claude-plugins.git
```

یا با CLI / Or via the CLI:

```bash
claude plugin marketplace add https://github.com/heyparsadev/claude-plugins.git
```

> 💡 از URL کامل `https://...git` استفاده کن (نه شکل کوتاه `owner/repo`) تا clone از HTTPS انجام شه و به SSH key نیاز نباشه.
> Use the full `https://...git` URL (not the `owner/repo` shorthand) so cloning uses HTTPS and needs no SSH key.

بعد هر کدوم رو که خواستی نصب کن / Then install whichever you want:

```
/plugin install venture@parsa-plugins
/plugin install founder-playbook@parsa-plugins
/plugin install liquid-glass@parsa-plugins
```

بعد یک سشن جدید Claude Code باز کن — پلاگین‌ها اول سشن لود می‌شن.
Then start a new Claude Code session; plugins load at session start.

---

## پلاگین‌ها / Plugins

### venture

سوئیت دستیار بیزینسی: مارکت‌ریسرچ، تحلیل رقبا، کشف مشتری، سنجش PMF، استراتژی GTM، اقتصاد واحد و بازبینی هیئت‌مدیره‌ای — همه زنجیرشده در یک workspace مشترک برای هر ونچر.

Business copilot suite — market research, competitor analysis, customer discovery, PMF, GTM, unit economics, board-style review, chained through a shared per-venture workspace.

→ [heyparsadev/claude-venture-plugin](https://github.com/heyparsadev/claude-venture-plugin)

### founder-playbook

اعتبارسنجی مرحلهٔ ایده بر پایهٔ *The Founder's Playbook* (Anthropic, 2026): ایدهٔ خام را به فرضیهٔ آزمون‌پذیر تبدیل می‌کند، red-team می‌کند، بازار و رقبا را تحقیق می‌کند، مصاحبهٔ مشتری را طراحی و سنتز می‌کند، و تصمیم ساخت را پشت شواهد نمره‌دار گیت می‌کند.

Idea-stage validation built on *The Founder's Playbook* — hypothesis, red-team, research, customer discovery, and an evidence-gated build decision.

→ [heyparsadev/claude-idea-validator](https://github.com/heyparsadev/claude-idea-validator)

### liquid-glass

دیزاین‌سیستم Liquid Glass برای iOS 26 در SwiftUI: مرجع API، اصول HIG، توکن‌های طراحی، الگوهای حرکت، قواعد دسترس‌پذیری و کارایی، آنتی‌پترن‌ها، کتابخانهٔ الگو و ۹ نمونهٔ صفحهٔ کامل که در Xcode 26 کامپایل می‌شن.

iOS 26 Liquid Glass design system for SwiftUI — API reference, HIG, tokens, motion, accessibility, performance, anti-patterns, pattern library, nine compiling examples.

→ [heyparsadev/liquid-glass-skill](https://github.com/heyparsadev/liquid-glass-skill)

---

`venture` و `founder-playbook` با هم interop دارن: اگه `ventures/<slug>/VENTURE.md` موجود باشه از هم استفاده می‌کنن. پوشه‌ها جدان، پس تداخلی نیست.

هر پلاگین از ریپوی خودش هم مستقیم نصب می‌شه — README همون ریپو رو ببین.
Each plugin can also be installed directly from its own repo; see that repo's README.

---

## License

MIT
