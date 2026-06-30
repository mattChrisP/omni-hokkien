🔊 **Playable comparison page:** https://mattchrisp.github.io/omni-hokkien/

Side-by-side SG Hokkien speech-QA: **① Native Q3-Omni** vs **② Q2.5 → trained bridge → Q3 talker**, on the same questions.


### Eval set v1

| Question | ① Native Q3 reply | ② Q2.5-bridge reply |
|---|---|---|
| 🎧 讲著就心酸，有闲再佮你坐咧食一杯啦。 | 好啦，有闲再联络，保重啊！ ([▶](samples/v1__sg_audio_996_04_ah-wei__native.wav)) | 好啊，多谢你，保庇你今年顺顺。 ([▶](samples/v1__sg_audio_996_04_ah-wei__bridge.wav)) |
| 🎧 阿辉，你今仔日阁爱去学校接囡仔啰？ | 是啊，我爱去学校门口等伊，真麻烦。 ([▶](samples/v1__sg_audio_999_01_mei-ling__native.wav)) | 是啊，伊讲欲去补习，我嘛无办法。 ([▶](samples/v1__sg_audio_999_01_mei-ling__bridge.wav)) |
| 🎧 先生，你是来载孙的吗？ | 是啊，我带伊来遮食饭。 ([▶](samples/v1__sg_audio_991_01_ah-ma__native.wav)) | 是啊，我查某囝去国外做工，想讲来拜拜求平安。 ([▶](samples/v1__sg_audio_991_01_ah-ma__bridge.wav)) |
| 🎧 阿公，下摆你阁讲予我听，我真想欲知影以前的代志。 | 好啦，明仔载我煮予你食，咱做伙回味一下。 ([▶](samples/v1__sg_audio_993_07_jia-hao__native.wav)) | 好啦，讲予你听，毋过爱听紧，莫予我讲甲太慢。 ([▶](samples/v1__sg_audio_993_07_jia-hao__bridge.wav)) |
| 🎧 彼时阵的生活应该真辛苦吧？你看遮的厝规间拢破破烂烂的。 | 辛苦是辛苦，毋过大家拢真suka，厝边头尾感情好，现在住组屋，隔壁拢无咧讲话。 ([▶](samples/v1__sg_audio_993_03_jia-hao__native.wav)) | 辛苦是辛苦，毋过大家拢真suka，逐家互相照顾，生活嘛真快活。 ([▶](samples/v1__sg_audio_993_03_jia-hao__bridge.wav)) |
| 🎧 美玲，今暗欲食啥物？楼下小贩中心有啥好呷？ | 我无爱食彼间，太油矣。不如去食鱼头炉，汤头清，食了较爽。 ([▶](samples/v1__sg_audio_998_01_ah-hui__native.wav)) | 我无所谓啦，看你爱食啥。彼间肉脞面排甲真长，我无爱排队。 ([▶](samples/v1__sg_audio_998_01_ah-hui__bridge.wav)) |
| 💬 *I have a headache, what should I do?* | 汝先去厝内歇睏，食药仔，看会好无。 ([▶](samples/v1__en_text_00__native.wav)) | 汝去给医生看，叫医生开药予你。 ([▶](samples/v1__en_text_00__bridge.wav)) |
| 💬 *Can you recommend something nice to eat for dinner?* | 好啊，我带你去吃那间出名的福建面，彼间排甲真长，毋过味道确实赞。 ([▶](samples/v1__en_text_01__native.wav)) | 好啊，我知影有一间真出名，你欲食啥？ ([▶](samples/v1__en_text_01__bridge.wav)) |
| 💬 *How was your day today?* | 唉，真累。做工做到半死，薪水拢无起，真无意思。 ([▶](samples/v1__en_text_02__native.wav)) | 无啥物，去楼下咖啡店食饭，顺紲去makan。 ([▶](samples/v1__en_text_02__bridge.wav)) |

### Eval set v2

| Question | ① Native Q3 reply | ② Q2.5-bridge reply |
|---|---|---|
| 🎧 知影啦，我一定早早伫遐等你。多谢你啊林叔！ | 好，按呢咱就按呢讲好矣，明仔载见！ ([▶](samples/v2__sg_audio_990_06_ah-mei__native.wav)) | 免客气，大家拢是邻居，互相照顾一下。 ([▶](samples/v2__sg_audio_990_06_ah-mei__bridge.wav)) |
| 🎧 有啦，昨昏吵甲我拢无好睏。 | 按呢毋通，明仔载我共伊讲看觅。 ([▶](samples/v2__sg_audio_994_02_mei-ling__native.wav)) | 伊敢是咧装修？ ([▶](samples/v2__sg_audio_994_02_mei-ling__bridge.wav)) |
| 🎧 按呢才着，做人子女爱有孝心，莫等到后悔就慢矣。 | 多谢林叔教示，我一定会记咧。 ([▶](samples/v2__sg_audio_986_05_ah-beng__native.wav)) | 多谢阿嬷教示，我知影矣，我会考虑。 ([▶](samples/v2__sg_audio_986_05_ah-beng__bridge.wav)) |
| 🎧 阿婶，这条鱼卖多少钱？ | 这条鱼真新鲜，算你十五块就好。 ([▶](samples/v2__sg_audio_992_01_ah-peng__native.wav)) | 这条鱼算你十五箍就好，我拢是熟客矣。 ([▶](samples/v2__sg_audio_992_01_ah-peng__bridge.wav)) |
| 💬 *What's the best strategy to beat a really hard boss in a video game?* | 汝爱先看Boss的攻击模式，毋通乱乱冲。等伊出招时，赶紧闪，莫予伊打中。 ([▶](samples/v2__en_text_00__native.wav)) | 汝爱先看它的攻击模式，按呢才好准备。 ([▶](samples/v2__en_text_00__bridge.wav)) |
| 💬 *My phone battery dies super fast, what should I do?* | 汝爱检查一下手机的耗电情况，看是啥物 App 在一直耗电。 ([▶](samples/v2__en_text_01__native.wav)) | 汝爱去买新手机，毋通一直忍。 ([▶](samples/v2__en_text_01__bridge.wav)) |
| 💬 *Explain how the internet works, in simple words.* | 好啦，我来共你讲。你知影无？网络就是用无线电波，或者是用网线，将你的手机、电脑连接起来。 ([▶](samples/v2__en_text_02__native.wav)) | 互联网就是一种大网络，大家用电脑连起来，信息就传过来了。 ([▶](samples/v2__en_text_02__bridge.wav)) |
| 💬 *If a dinosaur and a robot got into a fight, who would win and why?* | Ah, that's a good question! If a dinosaur and a robot fight, it depends on what kind of dinosaur and what kind of robot. ([▶](samples/v2__en_text_03__native.wav)) | 按呢就无定论啦，看它们的武器有够犀利。 ([▶](samples/v2__en_text_03__bridge.wav)) |
| 💬 *What's a good birthday gift for a friend who loves coffee?* | You can buy him a nice coffee machine or some premium coffee beans. He'll surely like that. ([▶](samples/v2__en_text_04__native.wav)) | 买一盒好食的咖啡，或者送伊一台咖啡机，伊一定会 suka。 ([▶](samples/v2__en_text_04__bridge.wav)) |
| 💬 *Can you explain what cryptocurrency is?* | Cryptocurrency is a kind of digital money that uses encryption to secure transactions. Unlike regular money, it is not controlled by any government or bank. ([▶](samples/v2__en_text_05__native.wav)) | cryptocurrency 是一种毋需透过银行的电子货币，现在真流行。 ([▶](samples/v2__en_text_05__bridge.wav)) |
| 💬 *Tell me a short funny joke.* | 好啦，我讲一个予你听。有一只蚂蚁去问大象：「你敢有看过隔壁彼个查某人？」大象讲：「无啊，我拢咧看报纸。」蚂蚁讲：「按呢你毋知影伊的脚毛真长，真suka去挖耳窿？」大象惊到报纸拢掉矣！ ([▶](samples/v2__en_text_06__native.wav)) | 阿公，你敢有听讲，隔壁阿伯昨昏去巴刹买菜，买着一只大只的虾？ ([▶](samples/v2__en_text_06__bridge.wav)) |
| 💬 *I'm feeling really stressed about my exams, any advice?* | 考试压力大是正常，毋通想伤多。你平时读书有认真无？ ([▶](samples/v2__en_text_07__native.wav)) | 汝爱早起一点，毋通遐尔懒惰。 ([▶](samples/v2__en_text_07__bridge.wav)) |
| 💬 *What should I pack for a trip to Japan in winter?* | 汝爱带厚一点的衫，日本冬天真冷，特别是去北海道。 ([▶](samples/v2__en_text_08__native.wav)) | 汝爱带厚衫，毋通只带一件衫。 ([▶](samples/v2__en_text_08__bridge.wav)) |
| 💬 *How do I make my own bubble tea at home?* | 汝爱先买好茶包，泡好茶水，等凉了才加糖。 ([▶](samples/v2__en_text_09__native.wav)) | 汝买一包珍珠粉，加水煮到变色，落一点冰糖，按呢就成矣。 ([▶](samples/v2__en_text_09__bridge.wav)) |
