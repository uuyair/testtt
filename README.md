# Agency homepage + Decap CMS (free)

1. GitHub မှာ repo အသစ်ဖွင့်ပြီး ဒီ folder အားလုံးကို တင်ပါ။
2. `admin/config.yml` ထဲက `repo:` ကို `သင့်-username/သင့်-repo` နဲ့ ပြောင်းပါ။
3. Netlify မှာ "Add new site -> Import from Git" ကိုရွေးပြီး repo ကိုချိတ်ပါ။ Build command မလို၊ Publish directory က `/` ပဲ။
4. Netlify: Site configuration -> Access & security -> OAuth မှာ GitHub provider ကို ထည့်ပါ (Decap ရဲ့ GitHub login အတွက်)။ အသေးစိတ်ကို Decap docs ("GitHub backend") မှာ စစ်ပါ။
5. `သင့်-site/admin/` ကိုဖွင့်ပြီး GitHub နဲ့ login ဝင်ပါ။ စာသားပြင်၊ Save/Publish လုပ်ရင် site ပြန် deploy ဖြစ်ပါမယ်။

စမ်းချင်ရင် local: `npx decap-server` နဲ့ `python3 -m http.server` ကိုအတူ run ပြီး `localhost:8000/admin/` ကိုဖွင့်ပါ။
