# 目的地主题配置

生成 HTML 清单时，根据目的地选择对应主题。主题包含：国旗、色彩、地标emoji、美食emoji、当地问候语、旅行名言。

## 使用方式

读取本文件，找到匹配的目的地主题，填入 HTML 模板的 `{{PLACEHOLDER}}` 变量。

如果目的地不在下表中，选择最接近的地区主题，或使用「通用旅行」主题。

---

## 意大利 🇮🇹

```yaml
flag: 🇮🇹
primary: "#E8505B"
secondary: "#F9A826"
accent: "#4A90D9"
hero_emojis: 🏛️🍝🍷🛵
food_emojis: 🍕🍝🍦☕🧀
greeting: "La dolce vita! 甜蜜的生活即将开始 ✨"
food_note: "从那不勒斯披萨到佛罗伦萨牛排，从罗马冰淇淋到托斯卡纳红酒...每一口都是艺术。"
quote: "Italy is a dream that keeps returning for the rest of your life."
quote_attr: "Anna Akhmatova"
progress_empty: "还没开始？别担心，罗马不是一天建成的 🏗️"
progress_start: "好的开始！斗兽场在向你招手 🏟️"
progress_halfway: "过半啦！你已经比一半人更接近意大利了 🛵"
progress_almost: "快了！别忘了给妈妈带个Gucci 👜"
progress_done: "Tutto pronto! 一切就绪，去拥抱甜蜜的生活吧！🍷✨"
```

## 日本 🇯🇵

```yaml
flag: 🇯🇵
primary: "#E84560"
secondary: "#2D3561"
accent: "#F7C873"
hero_emojis: ⛩️🍣🗻🎌
food_emojis: 🍣🍜🍱🍵🍡
greeting: "ようこそ！樱花与红叶，四季皆景 🌸"
food_note: "从筑地寿司到京都抹茶，从大阪章鱼烧到札幌拉面...这是味蕾的朝圣之旅。"
quote: "The journey itself is my home."
quote_attr: "松尾芭蕉 (Matsuo Bashō)"
progress_empty: "まだ始まっていません。でも大丈夫、一歩ずつ！👣"
progress_start: "第一歩！浅草寺的雷门在等你 ⛩️"
progress_halfway: "折り返し！你已经比排队吃一蘭拉面的人还快了 🍜"
progress_almost: "もうすぐ！准备好迎接おもてなし了吗？🎌"
progress_done: "準備完了！日本の旅が待っています！🌸✨"
```

## 法国 🇫🇷

```yaml
flag: 🇫🇷
primary: "#002395"
secondary: "#ED2939"
accent: "#FFFFFF"
hero_emojis: 🗼🥐🍷🎨
food_emojis: 🥐🧀🥖🍷🍰
greeting: "Bon voyage! 艺术、美食、浪漫，都在等着你 🎭"
food_note: "可颂、奶酪、红酒、马卡龙...法国人把生活过成了一道甜品。"
quote: "Paris is always a good idea."
quote_attr: "Audrey Hepburn"
progress_empty: "Pas encore commencé? 不急，法国人从来不急 🥐"
progress_start: "好的开始！埃菲尔铁塔已经亮灯了 💡"
progress_halfway: "À mi-chemin! 你已经比塞纳河游船还快了 🚢"
progress_almost: "Presque! 卢浮宫的蒙娜丽莎在对你微笑 🎨"
progress_done: "C'est prêt! 去享受法式生活吧！🥂✨"
```

## 瑞士 🇨🇭

```yaml
flag: 🇨🇭
primary: "#D52B1E"
secondary: "#4A8FE7"
accent: "#FFD700"
hero_emojis: 🏔️🚂🏕️⛷️
food_emojis: 🧀🍫🧀🫕🥾
greeting: "Grüezi! 阿尔卑斯的雪峰在呼唤你 ⛰️"
food_note: "芝士火锅、瑞士巧克力、山间小火车上的热可可...阿尔卑斯的一切都那么治愈。"
quote: "The mountains are calling and I must go."
quote_attr: "John Muir"
progress_empty: "还没开始？山就在那里，不会跑 ⛰️"
progress_start: "第一步！少女峰的齿轮火车已经启动 🚂"
progress_halfway: "过半！你的准备比瑞士手表还精准 ⌚"
progress_almost: "快了快了！别忘了带巧克力回来 🍫"
progress_done: "Alles ist bereit! 阿尔卑斯在等你！🏔️✨"
```

## 英国 🇬🇧

```yaml
flag: 🇬🇧
primary: "#1D3557"
secondary: "#E63946"
accent: "#A8DADC"
hero_emojis: 🏰☕🎡👑
food_emojis: 🍳☕🍺🥧🐟
greeting: "Mind the gap! 从大本钟到苏格兰高地，英伦风范 🎡"
food_note: "英式早餐、下午茶、炸鱼薯条、Sunday Roast...别再说英国没有美食了！"
quote: "The world is a book and those who do not travel read only one page."
quote_attr: "St. Augustine"
progress_empty: "Keep calm and carry on...准备材料！👑"
progress_start: "开局不错！伦敦眼已经转起来了 🎡"
progress_halfway: "过半！你的效率让英国人都震惊了（他们还在排队）☕"
progress_almost: "就快！别忘了带伞，虽然可能用不上 🌂"
progress_done: "Brilliant! 英国之旅，走起！🇬🇧✨"
```

## 美国 🇺🇸

```yaml
flag: 🇺🇸
primary: "#B31942"
secondary: "#0A3161"
accent: "#FFD700"
hero_emojis: 🗽🌉🎢🦅
food_emojis: 🍔🌮🥯🍩☕
greeting: "Welcome to the land of dreams! 从纽约到加州，无尽的可能性 🗽"
food_note: "纽约披萨、德州烤肉、加州牛油果吐司、新英格兰龙虾卷...一个国家的美食就是整个世界。"
quote: "Not all those who wander are lost."
quote_attr: "J.R.R. Tolkien"
progress_empty: "Ready to start? 美国那么大，值得好好准备 🌎"
progress_start: "好的开始！自由女神已经举起火炬 🗽"
progress_halfway: "Halfway there! 你已经比66号公路的中点还远了 🛣️"
progress_almost: "Almost! 签证官最欣赏准备充分的人 💪"
progress_done: "You're all set! 去追逐美国梦吧！🌟✨"
```

## 澳大利亚 🇦🇺

```yaml
flag: 🇦🇺
primary: "#00843D"
secondary: "#FFCD00"
accent: "#0072CE"
hero_emojis: 🦘🐨🏄🌊
food_emojis: 🥩🍤☕🥑🍳
greeting: "G'day mate! 阳光、沙滩、考拉和袋鼠在等你 🦘"
food_note: "澳式早午餐、海鲜拼盘、Tim Tam、flat white...还有世界上最棒的咖啡文化。"
quote: "The gladdest moment in human life is a departure into unknown lands."
quote_attr: "Sir Richard Burton"
progress_empty: "No worries mate! 慢慢来，澳洲人从不着急 🦘"
progress_start: "上路了！悉尼歌剧院的帆已经扬起 ⛵"
progress_halfway: "过半！你的进度比考拉爬树快多了 🐨"
progress_almost: "快了！大洋路的十二门徒在等你 🌊"
progress_done: "Beauty! 一切就绪，去享受阳光吧！☀️✨"
```

## 通用旅行主题（其他国家/不确定时使用）

```yaml
flag: 🌍
primary: "#FF6B6B"
secondary: "#4ECDC4"
accent: "#FFE66D"
hero_emojis: ✈️🌍🗺️🧳
food_emojis: 🍽️🥂🍰🍹✨
greeting: "世界那么大，你马上就要去看看了 🌍"
food_note: "每个地方都有属于自己的味道。带着好奇心出发，舌尖会带你找到最美的风景。"
quote: "Twenty years from now you will be more disappointed by the things you didn't do than by the ones you did do."
quote_attr: "Mark Twain"
progress_empty: "千里之行，始于足下。开始准备吧！👣"
progress_start: "好的开始是成功的一半！继续加油 💪"
progress_halfway: "过半啦！旅行的脚步声越来越近了 🎒"
progress_almost: "快了快了！护照准备好了吗？🛂"
progress_done: "全部就绪！去拥抱这个世界吧！🌍✨"
```
