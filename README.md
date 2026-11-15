# LED Sign Board / LED ဆိုင်းဘုတ်

LINK ~~ {https://ath1t.github.io/led-signboard/}

[English](#english) | [မြန်မာ](#မြန်မာ)

---

## English

A mobile-friendly LED sign board for your phone. It draws a real dot-matrix display, scrolls or flashes your message, and works in full screen. It is a single `index.html` file with no build step and no dependencies.

### Features

- Dot-matrix LED look with glowing dots
- Four effects: scroll left, scroll right, still, blink
- Adjustable scroll speed, text size, dot size and colour (6 presets and a custom colour picker)
- Full screen mode, with controls that hide after 3 seconds (tap the screen to bring them back)
- Turn the sign sideways while holding the phone upright
- Mirror text
- Keeps the screen awake while the sign is showing
- Burmese and English interface, with a language switch in the menu
- Supports Burmese text on the sign
- Remembers your settings on the device

### How to use

1. Open the site in your phone's browser.
2. Tap **Edit** and type your message.
3. Choose an effect, colour and sizes.
4. Tap **Show sign**.
5. Tap **Full screen**. Tap the screen at any time to bring the buttons back.

**iPhone:** Safari does not support full screen for web pages. Tap Share, then **Add to Home Screen**, and open the sign from the new icon to hide the browser bars.

### Host it on GitHub Pages

1. On GitHub, create a new **public** repository.
2. Upload `index.html` (and this `README.md`) and commit.
3. Go to **Settings**, then **Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, choose `main` and `/ (root)`, then click **Save**.
4. Wait a few minutes (it can take up to about 10 minutes). Your site will be at `https://<username>.github.io/<repo-name>/`.

If the site does not publish, add an empty file named `.nojekyll` to the repo root.

### Notes

- The Burmese font (Noto Sans Myanmar) loads from Google Fonts. If it can't load, the phone's built-in Burmese font is used.
- Burmese letters are taller than Latin letters. If a message looks cramped, lower **Text size** or **Dot size**.

---

## မြန်မာ

ဖုန်းပေါ်တွင် သုံးနိုင်သော LED ဆိုင်းဘုတ် web app ဖြစ်သည်။ အစက်များဖြင့် ပြသသည့် LED မျက်နှာပြင်အစစ်ကဲ့သို့ ပုံဖော်ပေးပြီး စာသားကို ရွေ့စေခြင်း၊ မှိတ်တုတ်မှိတ်တုတ်ပြခြင်း၊ မျက်နှာပြင်အပြည့် ပြခြင်းတို့ ပြုလုပ်နိုင်သည်။ `index.html` ဖိုင်တစ်ခုတည်းဖြစ်ပြီး ထပ်ဆောင်းသွင်းစရာ မလိုပါ။

### လုပ်ဆောင်ချက်များ

- အလင်းပေါက်နေသော အစက်များဖြင့် LED ပုံစံ
- ပုံစံ ၄ မျိုး: ဘယ်သို့ ရွေ့၊ ညာသို့ ရွေ့၊ ငြိမ်၊ မှိတ်တုတ်
- ရွေ့နှုန်း၊ စာလုံးအရွယ်၊ အစက်အရွယ်နှင့် အရောင် ချိန်ညှိနိုင် (အရောင် ၆ မျိုးနှင့် ကိုယ်ပိုင်အရောင်ရွေးခြင်း)
- မျက်နှာပြင်အပြည့် ပြနိုင် (ခလုတ်များသည် ၃ စက္ကန့်အကြာတွင် ပျောက်သွားပြီး စခရင်ကို နှိပ်လျှင် ပြန်ပေါ်လာမည်)
- ဖုန်းကို မတ်တပ်ကိုင်ထားပြီး ဆိုင်းဘုတ်ကို ဘေးတိုက် လှည့်ပြနိုင်
- စာသားကို မှန်ပြောင်းပြန် ပြနိုင်
- ဆိုင်းဘုတ်ပြနေစဉ် စခရင် ပိတ်မသွားစေရန် ထိန်းပေးသည်
- မြန်မာ / English မီနူး (မီနူးထဲတွင် ဘာသာစကား ပြောင်းခလုတ်ပါသည်)
- ဆိုင်းဘုတ်ပေါ်တွင် မြန်မာစာသား ပြနိုင်
- သင်၏ ဆက်တင်များကို ဖုန်းထဲတွင် မှတ်ထားပေးသည်

### အသုံးပြုပုံ

1. ဖုန်း၏ ဘရောက်ဇာဖြင့် ဝက်ဘ်ဆိုက်ကို ဖွင့်ပါ။
2. **ပြင်ရန်** ကို နှိပ်ပြီး စာသား ရိုက်ထည့်ပါ။
3. ပုံစံ၊ အရောင်နှင့် အရွယ်အစားများကို ရွေးပါ။
4. **ပြသရန်** ကို နှိပ်ပါ။
5. **မျက်နှာပြင်အပြည့်** ကို နှိပ်ပါ။ ခလုတ်များ ပြန်လိုချင်လျှင် စခရင်ကို နှိပ်ပါ။

**iPhone:** Safari တွင် ဝက်ဘ်စာမျက်နှာများအတွက် မျက်နှာပြင်အပြည့် မရပါ။ Share ကို နှိပ်ပြီး **Add to Home Screen** ကို ရွေးပါ။ ထို့နောက် ပေါ်လာသော icon မှ ဖွင့်လျှင် ဘရောက်ဇာဘား မပါဘဲ ပြသနိုင်သည်။

### GitHub Pages တွင် တင်ခြင်း

1. GitHub တွင် **Public** repository အသစ် ဖန်တီးပါ။
2. `index.html` (နှင့် ဤ `README.md`) ကို Upload လုပ်ပြီး Commit လုပ်ပါ။
3. **Settings** ထဲမှ **Pages** သို့ သွားပါ။ "Build and deployment" အောက်တွင် Source ကို **Deploy from a branch** ရွေးပါ၊ Branch ကို `main` နှင့် `/ (root)` ရွေးပြီး **Save** နှိပ်ပါ။
4. မိနစ်အနည်းငယ် စောင့်ပါ (အများဆုံး ၁၀ မိနစ်ခန့် ကြာနိုင်သည်)။ ဝက်ဘ်ဆိုက်လိပ်စာမှာ `https://<username>.github.io/<repo-name>/` ဖြစ်သည်။

ဝက်ဘ်ဆိုက် မပေါ်လျှင် repo ၏ root တွင် `.nojekyll` အမည်ဖြင့် ဗလာဖိုင်တစ်ခု ထည့်ပါ။

### မှတ်ချက်များ

- မြန်မာဖောင့် (Noto Sans Myanmar) ကို Google Fonts မှ ခေါ်သုံးသည်။ မရလျှင် ဖုန်းထဲရှိ မြန်မာဖောင့်ကို သုံးမည်။
- မြန်မာစာလုံးများသည် အင်္ဂလိပ်စာလုံးထက် မြင့်သောကြောင့် စာသား ကျပ်နေလျှင် **စာလုံးအရွယ်** သို့မဟုတ် **အစက်အရွယ်** ကို လျှော့ပါ။

---

Vibe Coded By Thio
