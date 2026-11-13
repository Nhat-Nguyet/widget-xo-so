# Lottery results

The latest results for Vietnam's three regional lotteries and Vietlott, updated after each draw.

*[Đọc bản tiếng Việt](README.md)*

**See it running:** https://nhatnguyet.org/widget/xo-so

## Paste these two lines

```html
<div data-widget="xo-so"></div>
<script async src="https://nhatnguyet.org/embed/w.js"></script>
```

No account, no API key, nothing to pay.

## What it gives your page

The latest draw for the three regions and Vietlott in four styles: by draw, rotating through every draw, all special prizes and Jackpots at once, or the full prize table. The widget picks up new results after each day's draws, so you never update it by hand.

## Worth knowing before you embed

- Published results only: the special and main prizes of the regional draws, and Vietlott's numbers and Jackpot value.
- No statistics, no predictions, no number tips.
- For the full table and a ticket checker, readers click through to Nhật Nguyệt.

## The steps

1. Paste the snippet into a sidebar or at the end of an article.
2. Pick a style with data-kieu: tab (by draw), xoay (rotating), tong-hop (all draws) or bang (full table).
3. Set data-loai to mien-bac, mien-trung, mien-nam, mega-6-45 or power-6-55 to choose the draw shown first.
4. Pick light or dark to match your site right in the preview.

## Where to paste it

**WordPress.** Add a *Custom HTML* block to the post, or a *Text* widget in
the sidebar, and paste both lines there. Do not paste into the ordinary
editor: it will show the code as text instead of running it.

**Wix, Squarespace, Shopify.** Use the *Embed HTML* / *Custom HTML* block.

**Hand-written sites.** Paste it straight where you want the widget. If you
embed several widgets, the `<script>` line only needs to appear once on the
page.

**A note on width.** The widget fits the width of wherever you put it. If that is narrower than 280px, add
`data-size="compact"`; if it is a wide horizontal strip, use
`data-size="wide"`.

## Make it match your page

| Attribute | Values | Meaning |
|---|---|---|
| `data-widget` | `xo-so` | Required |
| `data-theme` | light or dark | Defaults to light |
| `data-accent` | #b5402f | Accent colour as a 6-digit hex value, to match your own branding |
| `data-lang` | vi or en | Defaults to vi |
| `data-size` | compact, standard or wide | Level of detail for the width you have: compact drops secondary detail, wide lays out horizontally. Defaults to standard |
| `data-kieu` | tab, xoay, tong-hop or bang | Display style of the lottery widget: by draw, rotating, all draws or full table |
| `data-loai` | mien-bac, mien-trung, mien-nam, mega-6-45 or power-6-55 | The tab the lottery results widget opens on; defaults to mien-bac |

With every attribute this widget accepts, it looks like this:

```html
<div data-widget="xo-so" data-theme="dark" data-accent="#1f6f5c" data-lang="en" data-size="compact"></div>
<script async src="https://nhatnguyet.org/embed/w.js"></script>
```

Want to see it for yourself before it goes near your real page? Open
[`vi-du/index.html`](vi-du/index.html) in a browser, nothing to install.

## A few things we ask

- Free for personal and business websites, with no display limit.
- Keep the attribution line at the foot of the widget. That is what you give
  in return for free use.
- Do not embed on gambling, adult, fraudulent sites or anything unlawful
  under Vietnamese law.
- The content is folk knowledge and cultural convention, offered as
  reference, not as health, financial or legal advice.

Full text: [`TERMS.md`](TERMS.md) · [https://nhatnguyet.org/widget/dieu-khoan](https://nhatnguyet.org/widget/dieu-khoan)

## Who we are

Nhat Nguyet (https://nhatnguyet.org) is a Vietnamese reference site for calendrical and
cultural knowledge: the lunar calendar computed for Vietnam's own time zone,
the sexagenary cycle, solar terms, auspicious hours, astrology, feng shui,
and a glossary of terms.

There is one thing we try hard to keep clear, even inside a 300px frame:
which parts are computed, and which are folk convention.

Lunar dates, sexagenary names and solar terms are **computed**. Run the same
calculation and you get the same answer, and we publish the underlying
datasets under CC BY 4.0 so you can check for yourself.

Auspicious hours, Bat Trach directions and Lo Ban rule bands are **cultural
convention**. There are real lookup tables behind them, but they are not
measurements. The widget tells you what the table says; how much weight to
give it is yours to decide.

Where the schools disagree, we say so, rather than quietly picking a side and
presenting it as the only reading.

Open data: [GitHub](https://github.com/Nhat-Nguyet/du-lieu-am-lich) ·
[Hugging Face](https://huggingface.co/datasets/nhatnguyet)

## Something not right?

Open an issue in this repository. We do read them.

The whole widget library: [https://nhatnguyet.org/widget](https://nhatnguyet.org/widget)
