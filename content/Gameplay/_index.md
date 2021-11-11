+++
title = "遊戲玩法相關"
weight = 5
pre = "<b>5. </b>"
+++

[Team Aretuza: 新手玩法教學](https://teamaretuza.com/academy/course?courseId=4)

#### Q. 有咩要注意既細節？

A. 有好多，諗到乜講乜：

**1. 遊戲時，可以撳右下自己卡組睇入面仲有咩卡。**

要留意卡組係 **唔按順序** 展示出黎。

**2. 每行最多放 9 張卡。**

單位／{{<img width=20px height=26.58px src="/LIHKG-Gwent-guide/typeArtifact.png">}}神器／ **先手** {{<img width=22.00px height=20.00px src="/LIHKG-Gwent-guide/typeStrategem.png">}} **戰術牌（Stratagem）** 全部會佔位置。玩鋪場卡組時尤其要注意。

**3. 如果你當回合未出牌，但用咗場上既指令（Order）或領袖技能，咁你就必須打出一張牌。**

所以用指令（Order）／領袖技能／先手戰術牌（Stratagem）之前要諗清楚。

一用咗就冇得 Pass，必須出牌。

**4. 可以主動將手牌放入墓地（唔會觸發棄牌效果）。**

咁做當你出咗牌，可以結束回合。呢招有時有決定性作用。

另外，如果你燒完繩都未出牌，系統就會隨機丟棄你一張手牌。

**5. 平局下雙方各加一小勝。**

所以如果你輸咗 R1，R2 再平局，你就會輸（二比一）。

**6. 特別既卡牌效果介紹**

{{<expand2 title="Shupe's Day Off（店店的大冒險）">}}
{{<img width=auto height=auto src="/LIHKG-Gwent-guide/shupe.jpg">}}
<span style="font-style: italic;">If your starting deck has no duplicates, send Shupe on an adventure.</span>
<br/>
<span style="font-style: italic;">若己方起始牌組沒有重複牌，則派“店店”去冒險。</span>
<br/>
<br/>
實際效果：
<br/>
如果玩家起始卡組（即卡組編輯器內的卡組構成，與使用此卡當下的卡組情況無關）內沒有重複卡，
<br/>
玩家先從 <bold>法師（Mage）／獵人（Hunter）／騎士（Knight）</bold> 三者之中擇一。
<br/>
系統從所選類型的五種效果中隨機選出三個效果。
<br/>
玩家從三個效果中擇一，最後打出店店並觸發所選效果。
<br/>
（註：長按卡片會彈出卡片效果介面，可從中找到效果一覽）
{{<img width=auto height=auto src="/LIHKG-Gwent-guide/shupeDescription.png">}}
{{</expand2>}}

{{<expand2 title="Knickers（褲襠）">}}
{{<img width=auto height=auto src="/LIHKG-Gwent-guide/knickers.jpg">}}
<span style="font-style: italic;">This unit may raid the battlefield to aid you in battle.</span>
<br/>
<span style="font-style: italic;">它可能會沖入戰場，協助你戰鬥。</span>
<br/>
<br/>
實際效果：
<br/>
我方每回合結束時，如果此卡在卡組，則有一定機率從卡組召喚（Summon）至我方場上隨機一列。
<br/><!-- prettier-ignore -->
（未被官方確認的）機率公式：100% - 10% * 我方手牌數。
<br/>
（註：我方 Pass 後此卡仍然可以觸發效果）
{{</expand2>}}

&nbsp;

#### Q. 對面有 9 力以上既怪，點解我用傑洛特唔可以揀佢去殺？

A. 99.999%係因為對面同一行既其他單位有{{<img width=20px height=20.80px src="/LIHKG-Gwent-guide/statusDefender.png">}}衛士（Defender）狀態。

如果敵方某一行有{{<img width=20px height=20.80px src="/LIHKG-Gwent-guide/statusDefender.png">}}衛士單位，咁你任何既 **指定效果** 都唔可以指定佢果一行既其他卡，只能指定佢。

現時每個陣營都有一張衛士，新手要花少少時間認住佢地。

{{<figure src="/LIHKG-Gwent-guide/defender.jpg">}}

用帶 **淨化（Purify）** 效果既卡（如 Geralt: Axii, Pellar），可以 **移除** {{<img width=20px height=20.80px src="/LIHKG-Gwent-guide/statusDefender.png">}}衛士狀態。

留意唔同爐石，**昆特既鎖定（Lock）清唔到衛士狀態，必須用淨化**（或者直接將衛士摧毀）。

**淨化** 會移除單位上既所有 **狀態（Status）**，正面或反面 **狀態** 都會一下清曬。**狀態** 列表如下：

<!-- prettier-ignore -->
| 狀態 |     列表      |
| :--: | :-----------: |
| 正面 | {{<img width=20px height=20.80px src="/LIHKG-Gwent-guide/statusDefender.png">}}[衛士（Defender）](https://teamleviathangaming.com/glossary/defender/)、{{<img width=20px height=20.80px src="/LIHKG-Gwent-guide/statusImmunity.png">}}[免疫（Immunity）](https://teamleviathangaming.com/glossary/immunity/)、{{<img width=20px height=20.80px src="/LIHKG-Gwent-guide/statusResilience.png">}}[堅韌（Resilience）](https://teamleviathangaming.com/glossary/resilience/)、{{<img width=20px height=20.80px src="/LIHKG-Gwent-guide/statusShield.png">}}[護盾（Shield）](https://teamleviathangaming.com/glossary/shield/)、{{<img width=12.1px height=23.80px src="/LIHKG-Gwent-guide/statusVitality.png">}}[活力（Vitality）](https://teamleviathangaming.com/glossary/vitality/)|
| 負面 |{{<img width=20px height=20.80px src="/LIHKG-Gwent-guide/statusPoison.png">}}[中毒（Poison）](https://teamleviathangaming.com/glossary/poison/)、{{<img width=20px height=20.80px src="/LIHKG-Gwent-guide/statusBounty.png">}}[賞金（Bounty）](https://teamleviathangaming.com/glossary/bounty-status/)、{{<img width=20px height=20.80px src="/LIHKG-Gwent-guide/statusLock.png">}}[鎖定（Lock）](https://teamleviathangaming.com/glossary/lock/)、{{<img width=12.1px height=23.80px src="/LIHKG-Gwent-guide/statusBleeding.png">}}[重傷（Bleeding）](https://teamleviathangaming.com/glossary/bleeding-2/)、{{<img width=20px height=20.80px src="/LIHKG-Gwent-guide/statusDoomed.png">}}[佚亡（Doomed）](https://teamleviathangaming.com/glossary/doomed/)、{{<img width=20px height=20.80px src="/LIHKG-Gwent-guide/statusSpying.png">}}[潛伏（Spying）](https://teamleviathangaming.com/glossary/spying/)、{{<img width=20px height=20.80px src="/LIHKG-Gwent-guide/statusRupture.png">}}[破裂（Rupture）](https://teamleviathangaming.com/glossary/rupture/)|

&nbsp;

{{<rawhtml>}}

<h4 id="q-進階玩法咩野係長局短局同埋點解咁重要">Q. {{<class name="AdvGP" text="（進階玩法）">}}咩野係{{<class name="bold" text="長局／短局">}}，同埋點解咁重要？ <span class="anchor" data-clipboard-text="http://localhost:1313/gameplay/#q-進階玩法咩野係長局短局同埋點解咁重要"><i class="fas fa-link fa-lg"></i></span>
</h4>

{{</rawhtml>}}

A. 長短局冇嚴格定義，打得愈多回合就愈長，愈少回合就愈短。

唔少卡組依賴「引擎」（Engine）於長局打點數。「引擎」就係 **企場愈耐收益愈高** 既牌，

例如 Aretuza Adept, Sly Seductress, Svalblod Cultist 等，太多不能盡錄。

如果你副卡組有強力引擎卡，咁你要贏就要打長局：長局可將引擎既價值擴至最大。

長局卡組既一個常見致勝策略係：**贏 R1 ＞ R2 唔出牌直接 Pass ＞ R3 打長局**。

同樣道理，如果你認為對手長局比你強，你可以贏 R1，再 R2 **逼牌（Bleed）**。

然後你可以：

1。直接二比零。做到當然最好，但唔好強求。

2。逼到佢冇牌／得番幾張手牌再 Pass。咁 R3 就會比較短，對方引擎既發揮會受限制。

3。逼出對手關鍵牌再 Pass。對陣某啲依賴強力單卡／Combo 既卡組時通常需要咁做。

逼牌既時候要考慮番你自己副卡組既能力，因為 R3 短局代表你自己既引擎都發揮受限。

**留意 R2 逼牌有蝕卡差既風險**，請自己斟酌。

視乎你同你對手既卡組，**有時逼牌真係必須**，如果唔逼牌基本上冇可能贏。

所以想上 Rank 就一定要掌握逼牌既時機同做法。

[昆特總監 Jason 教你長短局／卡差概念（有中文字幕）](https://youtu.be/djmV-Q2pnyQ)

&nbsp;

{{<rawhtml>}}

<h4 id="q-進階玩法咩野係卡差card-advantageca先手定後手著數d">
Q. {{<class name="AdvGP" text="（進階玩法）">}}咩野係{{<class name="bold" text="卡差（Card Advantage／CA）">}}？先手定後手著數啲？ <span class="anchor" data-clipboard-text="http://localhost:1313/gameplay/#q-進階玩法咩野係卡差card-advantageca先手定後手著數d"><i class="fas fa-link fa-lg"></i></span>
</h4>

{{</rawhtml>}}

A. 請睇以下連結：

[營地： 後手優勢及卡差說明](https://www.iyingdi.cn/share/topic/post_share.html?id=2055311)

[Misterhabbla1 講解卡差概念（有中文字幕）](https://youtu.be/TuG1_W-9MUA?t=409)

先手有時有優勢（例如某啲引擎卡組內戰），但絕大部分情況都係後手佔優。

R2 同 R3 由上一小局獲勝既玩家先手（平局則上一局後手玩家變先手）。

雖然 **卡差** 影響巨大，但要緊記 **卡差不代表全部**，唔同對局下 **卡差** 重要性唔同。

有時你 **寧願蝕卡差都要贏 R1**，以求 R3 有得打長局（R2 直接 Pass）；

又或者 **寧願蝕卡差都要係 R2 逼牌**，以求逼出對手關鍵牌／令 R3 變短局。

&nbsp;

{{<rawhtml>}}

<h4 id="q-進階玩法咩野係最後一手last-say">
Q. {{<class name="AdvGP" text="（進階玩法）">}}咩野係{{<class name="bold" text="最後一手（Last Say）">}}？ <span class="anchor" data-clipboard-text="http://localhost:1313/gameplay/#q-進階玩法咩野係最後一手last-say"><i class="fas fa-link fa-lg"></i></span>
</h4>

{{</rawhtml>}}

A. **最後一手** 就係字面意思：決勝局最後一回合出牌既權利。

正常情況係進入決勝局時 **雙方手牌數相同**，咁 **後手方就有最後一手**。

又或者係進入決勝局時 **雙方手牌數唔同**，咁 **較多手牌一方（不論先後手）就有最後一手**。

（輸一卡贏 R1 + R2 冇蝕卡差 = 有最後一手。又或者後手專利：R1 平卡贏／賺兩卡輸都得。）

**最後一手** 重要係因為佢無法被反制，可以無顧慮地打出高點數卡或最大化破壞對手點數。

高手場唔少勝負純粹係睇邊位玩家有決勝局既 **最後一手**。

同卡差一樣，唔同對局下 **最後一手** 既重要性唔同，要自行判斷值唔值得為佢搶 R1。

&nbsp;

#### Q. 點樣提升自己勝率？

A. 昆特重視既係技術同對 Meta 既認識。

技術黎講，首先你要明白上面講既概念。最基本既就係先手盡力保卡差，後手嘗試搶卡差。

對 Meta 既認識同樣重要，**甚至比技術重要**：你要知道有咩主流卡組，知道主流卡組同你自己果副既強弱點（起碼要知長短局表現）。

活用自己優點，再針對敵方弱點，咁先打得上去。

另外，**[睇高手打牌極有用](../others/)**，可以令你牌技快速進步。

[（返回快速導覽）](../#quicknav)
