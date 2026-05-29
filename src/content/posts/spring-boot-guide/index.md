---
title: "Java Spring Boot 零基础完整学习手册"
published: 2026-05-29
description: "以校园博客论坛系统为案例，从 HelloWorld 到完整后端项目的 Spring Boot 零基础学习手册，涵盖 Java 基础、MyBatis Plus、Spring Security、JWT 认证、项目部署等完整内容。"
tags: [Java, Spring Boot, 后端开发, 教程, MyBatis Plus, JWT, Spring Security]
category: "后端开发"
pinned: true
draft: false
author: "刘畅"
image: "./cover.jpg"
---
# Java Spring Boot 闆跺熀纭€瀹屾暣瀛︿範鎵嬪唽

## 鈥斺€斾互鏍″洯鍗氬璁哄潧绯荤粺涓烘渚?
---

```
鈺斺晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺?鈺?                                                      鈺?鈺?       Java Spring Boot 闆跺熀纭€瀹屾暣瀛︿範鎵嬪唽            鈺?鈺?                                                      鈺?鈺?       鈥斺€斾粠 HelloWorld 鍒板畬鏁村悗绔」鐩殑濂囧涔嬫梾       鈺?鈺?                                                      鈺?鈺?                                                      鈺?鈺?        妗堜緥椤圭洰锛氭牎鍥崥瀹㈣鍧涚郴缁?v1.34              鈺?鈺?        浣滆€咃細鍒樼晠                                    鈺?鈺?        鍙戝竷鏃ユ湡锛?026 骞?4 鏈?                       鈺?鈺?                                                      鈺?鈺氣晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺愨晲鈺?```

---

## 鍏充簬鏈功

杩欐槸涓€鏈?*鐪熸闈㈠悜闆跺熀纭€**鐨?Spring Boot 瀛︿範鎵嬪唽銆傚畠涓嶄細鍋囪浣犲凡缁忔噦 Java锛屼篃涓嶄細璺宠繃浠讳綍鐜妭銆傛垜浠細涓€璧蜂粠鏈€鍩虹鐨?`Hello World` 寮€濮嬶紝涓€姝ヤ竴姝ヨ蛋鍒拌兘鐙珛鐪嬫噦銆佷慨鏀广€佺敋鑷充粠闆舵惌寤轰竴涓畬鏁寸殑鍚庣椤圭洰銆?
**鏈功鐨勭壒鐐癸細**

- 鉁?**瀹屽叏闆跺熀纭€鍙嬪ソ**锛氭瘡涓柊姒傚康閮戒細鐢ㄧ敓娲荤被姣旇В閲婁竴娆?- 鉁?**鐪熷疄椤圭洰椹卞姩**锛氭墍鏈夎瑙ｉ兘鍩轰簬鐪熷疄鍙繍琛岀殑"鏍″洯鍗氬璁哄潧绯荤粺"
- 鉁?**浠ｇ爜鏉ユ簮鐪熷疄**锛氭瘡涓€娈电ず渚嬩唬鐮侀兘鏉ヨ嚜椤圭洰鐨勭湡瀹炴枃浠讹紝鍙互鎵撳紑 IDE 涓€涓€瀵圭収
- 鉁?**瑕嗙洊鍏ㄦ爤鍚庣**锛氫粠 Java 璇硶 鈫?Maven 鈫?Spring Boot 鈫?MyBatis Plus 鈫?Spring Security 鈫?JWT 鈫?椤圭洰閮ㄧ讲
- 鉁?**瓒呰繃 5 涓囧瓧**锛氳冻澶熻缁嗭紝浣嗕笉鍟板棪

**瀛﹀畬鏈功浣犲皢鑾峰緱锛?*

1. 鑳界嫭绔嬭鎳備换浣?Spring Boot 椤圭洰鐨勬簮鐮?2. 鑳界敤 Spring Boot + MyBatis Plus 浠庨浂鎼缓涓€涓?RESTful 鍚庣
3. 鐞嗚В鐢ㄦ埛璁よ瘉銆丣WT銆佸瘑鐮佸姞瀵嗐€乆SS 闃叉姢绛夊畨鍏ㄨ鐐?4. 浼氬鐞嗗父瑙佺殑骞跺彂闂锛堢偣璧為噸澶嶃€侀槄璇婚噺绔炴€佺瓑锛?5. 鑳界嫭绔嬪畬鎴愰」鐩墦鍖呫€侀儴缃层€佷笂绾垮叏娴佺▼

---

## 閫傚悎浜虹兢

- **澶у鐢?/ 鏍℃嫑鐢?*锛氭壘鍚庣寮€鍙戠殑瀹炰範鎴栧伐浣?- **杞瀛︾紪绋?*锛氫粠 0 寮€濮嬫兂鍏ラ棬鍚庣寮€鍙?- **鍓嶇杞悗绔?*锛氫細 JavaScript 浣嗘兂瀛﹀悗绔?- **鍩硅鐝鍛?*锛氭兂瑕佷竴浠界郴缁熷寲鐨勫叆闂ㄨ祫鏂?- **浠ｇ爜鐖卞ソ鑰?*锛氭兂鐪嬫噦鍒汉鐨?GitHub 椤圭洰

鈿狅笍 **涓嶉€傚悎**锛氬凡缁忕簿閫?Spring Boot銆佹兂鐪嬫繁鍏ユ簮鐮佸垎鏋愮殑楂樼骇寮€鍙戣€呫€傛湰涔﹀畾浣嶆槸"鍏ラ棬鍒拌兘涓婃墜"锛屼笉鏄?婧愮爜绮捐"銆?
---

## 瀛︿範寤鸿

### 1. 杈硅杈规暡浠ｇ爜

**杩欐槸鏈€閲嶈鐨勫缓璁?*銆傜湅鍐嶅鏁欑▼涓嶅鑷繁浜叉墜鏁蹭竴閬嶃€傛瘡涓€娈电ず渚嬩唬鐮侀兘璇蜂綘鎵撳紑 IDE锛屼翰鑷暡杩涘幓锛屼翰鑷窇涓€娆°€傜悊瑙ｆ案杩滄潵鑷翰鎵嬪疄璺点€?
### 2. 涓嶈璺宠穬

铏界劧浣犲彲鑳芥€ュ垏鍦版兂鐪?椤圭洰瀹炴垬"锛屼絾璇疯€愬績浠?Java 鍏ラ棬"寮€濮嬨€傛瘡涓€绔犻兘鏄悗闈㈢殑鍩虹銆傝烦杩囧熀纭€锛屽悗闈㈢殑浠ｇ爜浼氳浣犳姄鐙傘€?
### 3. 鍠勭敤 IDE 鐨勮烦杞?
璇诲埌 `SysUserController` 鏃讹紝璇锋墦寮€椤圭洰鐨?`SysUserController.java`锛屾寜浣?`Ctrl` 鐐瑰嚮鍚勭绫诲悕锛岃烦鍒板畾涔夈€傝繖绉?鎺㈢储寮忛槄璇?姣旂湅涔﹀揩鍗佸€嶃€?
### 4. 鍋氱瑪璁?
閬囧埌涓嶇悊瑙ｇ殑姒傚康锛屼笉瑕佺‖鑳岋紝鍏堣涓嬫潵锛屽線鍚庤鍑犵珷鑷劧灏辨噦浜嗐€傝瀹屼竴绔犲啀鍥炲ご鐪嬶紝浼氭湁 "鍘熸潵濡傛" 鐨勫揩鎰熴€?
### 5. 涓嶈瀹虫€曟姤閿?
鎶ラ敊鏄▼搴忓憳鏈€濂界殑鑰佸笀銆傜湅鍒扮孩鑹茬殑 `Exception` 涓嶈鎱屽紶锛岃€岃鍏村鈥斺€旇繖鏄綘瀛︿範鐨勬満浼氥€傚鍒堕敊璇俊鎭埌鎼滅储寮曟搸锛?9% 鐨勯棶棰橀兘鏈夌瓟妗堛€?
### 6. 鍔犲叆绀惧尯

瀛︿範鍚庣寮€鍙戜笉瑕佸鍐涘鎴樸€傚姞鍏ヤ竴浜?Java / Spring Boot 瀛︿範缇わ紝鍜屽悓鏍峰湪瀛︿範鐨勪汉涓€璧疯璁恒€?
---

## 妗堜緥椤圭洰绠€浠?
鏈功浣跨敤鐨勬渚嬮」鐩槸涓€涓?*鐪熷疄鐨勩€佸彲杩愯鐨勬牎鍥崥瀹㈣鍧涚郴缁?*锛?
- **GitHub**锛歨ttps://github.com/Xinghe-0203/Campus_Blog
- **鐗堟湰**锛歷1.34锛堟渶鍚庢洿鏂?2026-04-27锛?- **浠ｇ爜閲?*锛?27 涓?Java 鏂囦欢
- **鏁版嵁琛?*锛?8 寮?- **Controller**锛?3 涓?- **API 鎺ュ彛**锛?7 涓?HTTP 绔偣

**鍖呭惈鐨勫姛鑳芥ā鍧楋細**

| 妯″潡 | 鍔熻兘 |
|------|------|
| 馃懁 鐢ㄦ埛绯荤粺 | 娉ㄥ唽銆佺櫥褰曘€丣WT 璁よ瘉銆佷慨鏀瑰瘑鐮併€佺敤鎴锋悳绱?|
| 馃摑 鏂囩珷绯荤粺 | 鍙戝竷銆佺紪杈戙€佸垹闄ゃ€佽鎯呫€佸垪琛ㄣ€侀珮绾ф悳绱€佽崏绋胯嚜鍔ㄤ繚瀛?|
| 馃挰 浜掑姩绯荤粺 | 璇勮锛堝祵濂楀洖澶嶏級銆佺偣璧炪€佹敹钘?|
| 馃懃 绀句氦绯荤粺 | 鍏虫敞銆佺矇涓濄€佸叧娉ㄦ祦 |
| 馃敂 閫氱煡绯荤粺 | 鐐硅禐閫氱煡銆佽瘎璁洪€氱煡銆佸叧娉ㄩ€氱煡锛堜簨浠堕┍鍔級 |
| 馃寪 鏍″弸鍦?| 鍔ㄦ€佸彂甯冦€佺偣璧炪€佽瘎璁恒€佽浆鍙戙€佸彲瑙佹€ф帶鍒?|
| 馃摲 濯掍綋涓婁紶 | 鍥剧墖/瑙嗛涓婁紶锛屾枃浠跺ぇ灏忛檺鍒?500MB |
| 馃敟 鐑棬瓒嬪娍 | 鐑棬鏂囩珷銆佺儹闂ㄦ爣绛?|
| 馃毃 涓炬姤绯荤粺 | 鐢ㄦ埛涓炬姤銆佺鐞嗗憳澶勭悊 |

**涓轰粈涔堥€夋嫨杩欎釜椤圭洰浣滀负妗堜緥锛?*

1. **鍔熻兘瀹屾暣**锛氳鐩栦簡鐪熷疄涓氬姟绯荤粺鐨勬柟鏂归潰闈紝涓嶆槸鐜╁叿椤圭洰
2. **浠ｇ爜瑙勮寖**锛氶伒寰樋閲?Java 寮€鍙戣鑼冿紝鍒嗗眰娓呮櫚
3. **鎸佺画杩唬**锛氫粠 v1.0 鈫?v1.34 缁忚繃 30 娆¤凯浠ｏ紝鍖呭惈澶ч噺鐪熷疄鐨?Bug 淇
4. **瀹夊叏鍔犲浐**锛氱粡杩囧杞畨鍏ㄥ璁★紝浣撶幇宸ヤ笟绾у疄璺?5. **瀛﹀畬鍗崇敤**锛氬畬鍏ㄥ彲浠ヤ簩娆″紑鍙戞垚姣曚笟璁捐鎴栧晢涓氶」鐩?
---

## 鍏ㄤ功缁撴瀯

鏈功鍒嗕负 **4 澶ч儴鍒嗗叡 19 绔?+ 闄勫綍**锛屽惊搴忔笎杩涳細

### 馃尡 绗竴閮ㄥ垎锛氬叆闂ㄥ熀纭€锛堢害 13000 瀛楋級

> 浠?0 寮€濮嬬殑 Java 涓?Spring Boot 鍚挋

- 鍐欏湪鍓嶉潰锛氳嚧闆跺熀纭€璇昏€?- **绗?1 绔?* Java 璇█鍏ラ棬
- **绗?2 绔?* 寮€鍙戠幆澧冩惌寤?- **绗?3 绔?* Maven 涓庨」鐩粨鏋?- **绗?4 绔?* Spring Boot 绗竴璇?
### 馃尶 绗簩閮ㄥ垎锛氭鏋舵牳蹇冿紙绾?13000 瀛楋級

> 鐞嗚В Spring Boot 椤圭洰"鍐呭姛蹇冩硶"

- **绗?5 绔?* MyBatis Plus 鎸佷箙灞傛鏋?- **绗?6 绔?* 鍒嗗眰鏋舵瀯璇﹁В
- **绗?7 绔?* 缁熶竴鍝嶅簲涓庡紓甯稿鐞?- **绗?8 绔?* Spring Security 鍏ラ棬
- **绗?9 绔?* JWT 璁よ瘉瀹炴垬

### 馃尦 绗笁閮ㄥ垎锛氶」鐩疄鎴橈紙绾?16000 瀛楋級

> 鐪熷疄涓氬姟鍦烘櫙涓嬬殑浠ｇ爜涓庤璁?
- **绗?10 绔?* 鐢ㄦ埛妯″潡瀹炴垬
- **绗?11 绔?* 鏂囩珷妯″潡瀹炴垬
- **绗?12 绔?* 浜掑姩妯″潡锛氳瘎璁?/ 鐐硅禐 / 鏀惰棌
- **绗?13 绔?* 鍏虫敞涓庨€氱煡
- **绗?14 绔?* 鏍″弸鍦堜笌濯掍綋
- **绗?15 绔?* 鐑棬瓒嬪娍 + 涓炬姤绯荤粺

### 馃尣 绗洓閮ㄥ垎锛氳繘闃朵笌閮ㄧ讲锛堢害 10000 瀛楋級

> 璁╀唬鐮佺湡姝?涓婄嚎涓虹帇"

- **绗?16 绔?* 瀹夊叏鍔犲浐瀹炴垬
- **绗?17 绔?* 鎬ц兘浼樺寲鎶€宸?- **绗?18 绔?* 娴嬭瘯涓庤皟璇?- **绗?19 绔?* 閮ㄧ讲涓婄嚎
- **闄勫綍 A** 甯歌闂 FAQ
- **闄勫綍 B** 椤圭洰鏈琛?- **鍚庤** 浣犵殑鎴愰暱涔嬭矾

---

## 濡備綍涓嬭浇鏈」鐩唬鐮?
```bash
# 1. 鍏嬮殕椤圭洰
git clone https://github.com/Xinghe-0203/Campus_Blog.git

# 2. 杩涘叆椤圭洰鐩綍
cd Campus_Blog

# 3. 澶嶅埗鐜鍙橀噺妯℃澘锛堥噸瑕侊紒锛?cp .env.example .env

# 4. 缂栬緫 .env 鏂囦欢锛屽～鍏ヤ綘鐨勬暟鎹簱瀵嗙爜绛?
# 5. 鏋勫缓椤圭洰
mvn clean package

# 6. 杩愯椤圭洰
mvn spring-boot:run
```

璇︾粏鐨勭幆澧冩惌寤恒€両DE 閰嶇疆銆佹暟鎹簱鍒濆鍖栨楠わ紝閮藉湪绗?2 绔犱腑璇︾粏璁茶В銆?
---

## 鑷磋阿

鎰熻阿浣犻€夋嫨杩欐湰涔︺€傚笇鏈涜瀹岃繖鏈功鐨勪綘锛岃兘浠庝竴涓畬鍏ㄧ殑闆跺熀纭€灏忕櫧锛岃湑鍙樻垚涓€涓兘鐙珛鍐欏嚭 Spring Boot 椤圭洰鐨勫悗绔紑鍙戣€呫€?
濡傛灉浣犲湪闃呰涓亣鍒颁换浣曢棶棰橈紝鎴栬€呭彂鐜颁功涓敊璇紝娆㈣繋鍦?GitHub 椤圭洰涓彁 Issue銆?
> **瀛︿範缂栫▼娌℃湁鎹峰緞锛屼絾鏈夋渶閫傚悎浣犵殑璺緞銆?*
>
> 杩欐湰涔︼紝灏辨槸涓洪浂鍩虹鐨勪綘锛屽畾鍒剁殑閭ｆ潯璺緞銆?
璁╂垜浠紑濮嬪惂锛侌煔€

---

</content>

# 銆奐ava Spring Boot 闆跺熀纭€瀹屾暣瀛︿範鎵嬪唽銆?
## 绗竴閮ㄥ垎 鍏ラ棬鍩虹

> 椤圭洰妗堜緥锛氭牎鍥崥瀹㈣鍧涚郴缁燂紙Campus Blog Forum锛?> 閰嶅浠ｇ爜锛歚D:\MyCode\edu_project`
> 閫傚悎浜虹兢锛氶浂鍩虹瀹屽叏娌℃帴瑙﹁繃 Java 鍜屽悗绔紑鍙戠殑灏忕櫧

---

# 鍐欏湪鍓嶉潰

鍡紝鏈嬪弸 馃憢

濡傛灉浣犳鍦ㄦ墦寮€杩欐湰涔︼紝璇存槑浣犲ぇ姒傜巼鏄繖鏍风殑鎯呭喌锛氬惉璇磋繃"Java 鍚庣寮€鍙?杩欎釜璇嶏紝鍙兘鍦ㄥぇ瀛﹀紑杩?Java 璇句絾鏄簯閲岄浘閲岋紝鎴栬€呭畬鍏ㄦ病纰拌繃缂栫▼锛屽彧鏄洜涓烘兂鍋氫竴涓睘浜庤嚜宸辩殑缃戠珯椤圭洰鑰岃蛋鍒拌繖閲屻€傛棤璁轰綘鏄摢涓€绉嶏紝鎭枩浣狅紝浣犳潵瀵瑰湴鏂逛簡銆?
## 杩欐湰涔︽槸缁欒皝鐪嬬殑

杩欐湰涔︽槸鍐欑粰**瀹屽叏闆跺熀纭€**鐨勫悓瀛︾殑銆傛垜鍋囪浣狅細

- 娌″啓杩囦竴琛?Java 浠ｇ爜
- 涓嶇煡閬撲粈涔堟槸 IDE銆佷粈涔堟槸 Maven
- 娌″惉璇磋繃 Spring Boot
- 浣嗘槸浼氬紑鐢佃剳銆佷細鐢ㄦ祻瑙堝櫒銆佷細澶嶅埗绮樿创 馃槃

濡傛灉浣犲凡缁忔槸鏈夌粡楠岀殑寮€鍙戣€咃紝杩欐湰涔︾殑鍓嶅嚑绔犲浣犳潵璇村彲鑳戒細鏄惧緱鍟板棪锛屽彲浠ュ揩閫熺炕杩囧幓锛岀洿鎺ヤ粠鍚庨潰 Spring Boot 鐨勯儴鍒嗗紑濮嬭銆?
## 瀛﹀畬鍚庝綘鑳芥帉鎻′粈涔?
璇诲畬鏁存湰涔︼紙鍖呮嫭鍚庣画閮ㄥ垎锛夛紝骞朵笖**浜叉墜鎶婃瘡涓€涓緥瀛愭暡涓€閬?*涔嬪悗锛屼綘灏嗚兘澶燂細

1. 鐙珛鐪嬫噦涓瓑瑙勬ā鐨?Spring Boot 椤圭洰婧愮爜
2. 鑷繁浠庨浂鎼缓涓€涓?Spring Boot 鍚庣宸ョ▼
3. 缂栧啓 RESTful API锛堜篃灏辨槸鎵嬫満 App銆佺綉椤靛墠绔皟鐢ㄧ殑"鎺ュ彛"锛?4. 鎿嶄綔 MySQL 鏁版嵁搴擄紝鍐欏嚭澧炲垹鏀规煡鍔熻兘
5. 瀹炵幇鐢ㄦ埛鐧诲綍銆佹潈闄愭帶鍒躲€丣WT 璁よ瘉
6. 鐪嬫噦鎴戜滑杩欎釜鐪熷疄鐨?鏍″洯鍗氬璁哄潧绯荤粺"椤圭洰锛屽苟涓旇兘鍦ㄥ畠鐨勫熀纭€涓婄户缁坊鍔犺嚜宸辩殑鍔熻兘

## 瀛︿範璺緞寤鸿

鈿狅笍 **璇峰姟蹇呴伒瀹堣繖鏉″缓璁細杈硅杈规暡浠ｇ爜锛?*

鎴戠煡閬撳緢澶氫汉鍠滄鎶婁功"鐪嬪畬鍐嶈"锛岀湅瀹屼箣鍚庤寰楄嚜宸辨噦浜嗭紝缁撴灉涓€涓婃墜灏辨姄鐬庛€傚缂栫▼**娌℃湁鎹峰緞**锛屼綘蹇呴』鎶婁唬鐮佷翰鎵嬫暡涓€閬嶁€斺€斾笉鏄鍒剁矘璐达紝鏄?*涓€涓瓧绗︿竴涓瓧绗﹀湴鏁?*銆?
涓轰粈涔堬紵鍥犱负浣犵殑鎵嬫寚鍦ㄦ暡閿洏鐨勬椂鍊欙紝浼氱姱鍚勭閿欒锛氭嫾閿欏崟璇嶃€佸繕璁板垎鍙枫€佹嫭鍙蜂笉鍖归厤鈥︹€﹁繖浜涢敊璇氨鏄綘鎴愰暱鐨勫吇鏂欍€傛瘡涓€涓?bug 閮戒細鏁欎綘涓€涓煡璇嗙偣銆?
寤鸿鑺傚锛?
1锔忊儯 姣忓ぉ瀛?1 ~ 2 绔狅紝涓嶈璐
2锔忊儯 姣忎釜渚嬪瓙閮芥暡涓€閬嶅苟璺戣捣鏉?3锔忊儯 鍑洪敊浜嗗厛鑷繁鏌ワ紙鍏堢湅鎶ラ敊淇℃伅锛夛紝瀹炲湪涓嶄細鍐嶉棶 AI 鎴栧悓瀛?4锔忊儯 瀛﹀畬涓€绔犵敤鑷繁鐨勮瘽澶嶈堪涓€閬?
## 鏈」鐩畝浠?
鎴戜滑鐨勬渚嬮」鐩彨 **鏍″洯鍗氬璁哄潧绯荤粺锛圕ampus Blog Forum锛?*銆傚畠鏄竴涓湡瀹炲彲杩愯銆佽兘閮ㄧ讲涓婄嚎鐨勯」鐩紝鍖呭惈浠ヤ笅鍔熻兘锛?
- 鐢ㄦ埛娉ㄥ唽銆佺櫥褰曘€丣WT 璁よ瘉
- 鍙戝笘銆佽瘎璁恒€佸祵濂楀洖澶?- 鐐硅禐銆佹敹钘忋€佸叧娉?- 閫氱煡绯荤粺
- 鏍″弸鍦堬紙绫讳技寰崥锛?- 濯掍綋涓婁紶锛堝浘鐗囥€佽棰戯級
- 鐑害缁熻銆佷妇鎶ョ鐞?- 绛夌瓑鈥︹€?
鏁版嵁搴撲竴鍏?**18 寮犺〃**锛屾妧鏈爤鏄?**Spring Boot 3.0.12 + MyBatis Plus 3.5.5 + Spring Security + JWT + MySQL**锛孞DK 鐢?**21+**銆傛槸涓嶆槸鍚笂鍘诲緢鍘夊锛熷埆鎬曪紝绛変綘璇诲畬杩欐湰涔︼紝鍥炶繃澶寸湅浼氳寰?涔熷氨閭ｄ箞鍥炰簨"銆?
## 瀛︿範蹇冩€?
鏈€鍚庤涓€鍙ユ渶閲嶈鐨勮瘽锛?
> **鎶€鏈笉闅撅紝闅剧殑鏄€愬績銆?*

浣犱細閬囧埌鐜瑁呬笉涓娿€丮aven 涓嬭浇涓嶅姩銆丩ombok 涓嶇敓鏁堛€佹暟鎹簱杩炰笉涓娿€佽帿鍚嶅叾濡欑殑绾㈢嚎鈥︹€﹁繖浜涢兘鏄?*鎵€鏈夌▼搴忓憳鐨勬棩甯?*銆備笉瑕佹€€鐤戣嚜宸辩锛屾病浜哄ぉ鐢熷氨浼氾紝鎵€鏈?澶т浆"閮芥槸浠庣湅鍒扮孩鑹叉姤閿欏氨鎱屽紶寮€濮嬬殑銆?
鏀捐交鏉撅紝鎱㈡參鏉ャ€傚噯澶囧ソ浜嗭紵鎴戜滑寮€濮嬪惂 馃殌

---

# 绗?1 绔?Java 璇█鍏ラ棬

鍦ㄥ姩鎵嬫惌寤洪」鐩箣鍓嶏紝鎴戜滑蹇呴』鍏堣璇?Java 杩欓棬璇█銆傝繖涓€绔犳垜灏介噺鐢ㄥぇ鐧借瘽鍜岀敓娲荤被姣旀潵瑙ｉ噴锛屼笉浼氳浣犵湅鍏紡鍜屽畾涔夈€?
## 1.1 Java 鏄粈涔堛€佽兘鍋氫粈涔?
Java 鏄竴闂?**缂栫▼璇█锛圥rogramming Language锛?*銆傛墍璋撶紪绋嬭瑷€锛屽氨鏄汉绫荤敤鏉?鎸囨尌"鐢佃剳鍋氫簨鐨勪竴绉嶇壒娈婅瑷€銆備腑鏂囨槸鐢ㄦ潵璺熶汉璇磋瘽鐨勶紝Java 鏄敤鏉ヨ窡鐢佃剳璇磋瘽鐨勩€?
馃尠 涓€涓敓娲荤被姣旓細

- 浣犳兂璁╀竴涓鍥芥湅鍙嬪府浣犱拱鏉ザ鑼讹紝浣犲緱鐢ㄤ粬鑳藉惉鎳傜殑璇█锛堟瘮濡傝嫳璇級鍛婅瘔浠栨€庝箞璧般€佽鐐逛粈涔堛€?- 浣犳兂璁╃數鑴戝府浣犲鐞嗘暟鎹€佹樉绀虹綉椤碉紝浣犱篃寰楃敤鐢佃剳鑳藉惉鎳傜殑璇█锛堟瘮濡?Java锛夊憡璇夊畠姝ラ銆?
Java 鐢?Sun 鍏徃鍦?1995 骞村彂甯冿紝鐜板湪褰?Oracle 鎵€鏈夈€傚畠鏈€澶х殑鐗圭偣鏄?**"涓€娆＄紪鍐欙紝鍒板杩愯锛圵rite Once, Run Anywhere锛?** 鈥斺€?浣犲啓鐨勫悓涓€娈?Java 浠ｇ爜锛屽彲浠ュ湪 Windows銆丮ac銆丩inux銆佸畨鍗撴墜鏈轰笂閮借窇璧锋潵銆傝繖鏄€庝箞鍋氬埌鐨勶紵鍥犱负 Java 涓嶆槸鐩存帴缁欑數鑴戠‖浠剁湅鐨勶紝瀹冩槸缁欎竴涓彨 **JVM锛圝ava Virtual Machine锛孞ava 铏氭嫙鏈猴級** 鐨?缈昏瘧瀹?鐪嬬殑锛屾瘡涓搷浣滅郴缁熶笂閮芥湁鑷繁鐗堟湰鐨?JVM銆?
Java 鑳藉仛浠€涔堬紵闈炲父澶氾細

| 搴旂敤鍦烘櫙 | 涓句緥 |
| --- | --- |
| 鍚庣鏈嶅姟鍣?| 娣樺疂銆佷含涓溿€?2306 鍚庣澶ч噺浣跨敤 Java |
| 瀹夊崜 App | 鏃╂湡瀹夊崜搴旂敤涓昏鐢?Java 鍐欙紙鐜板湪 Kotlin 涔熷緢娴佽锛墊
| 澶ф暟鎹?| Hadoop銆丼park銆丗link 閮芥槸 Java/Scala |
| 妗岄潰搴旂敤 | IDEA 鏈韩灏辨槸 Java 鍐欑殑 |
| 鎴戜滑鐨勯」鐩?| 鏍″洯鍗氬璁哄潧鍚庣 鉁?|

鎴戜滑杩欐湰涔﹂噸鐐硅鐨勬槸 **鍚庣鏈嶅姟鍣ㄥ紑鍙?*锛屼篃灏辨槸缁欑綉椤靛拰鎵嬫満 App 鎻愪緵鏁版嵁鐨?骞曞悗鑻遍泟"銆?
## 1.2 绗竴涓?Java 绋嬪簭 HelloWorld

鎸夌収缂栫▼鐣岀殑浼犵粺锛屽浠讳綍鏂拌瑷€绗竴涓▼搴忛兘鍙?"Hello World"锛堜綘濂斤紝涓栫晫锛夈€傛垜浠篃涓嶈兘鍏嶄織锛?
```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

璺戣捣鏉ュ悗灞忓箷浼氭樉绀猴細

```
Hello, World!
```

鐪嬭捣鏉ョ畝鍗曪紝鍏跺疄閲岄潰淇℃伅閲忓緢澶с€傛垜浠竴琛屼竴琛屾媶瑙ｏ細

| 浠ｇ爜 | 鍚箟 |
| --- | --- |
| `public class HelloWorld` | 瀹氫箟涓€涓悕涓?HelloWorld 鐨?绫?锛宲ublic 琛ㄧず"鍏紑鐨? |
| `{ ... }` | 澶ф嫭鍙峰寘璧锋潵鐨勯儴鍒嗘槸杩欎釜绫荤殑鍐呭 |
| `public static void main(String[] args)` | 涓€涓壒娈婄殑鏂规硶锛屽彨 main锛屾槸绋嬪簭鐨?鍏ュ彛" |
| `System.out.println(...)` | 璋冪敤绯荤粺鐨?鎵撳嵃"鍔熻兘锛屾妸鎷彿閲岀殑鍐呭鏄剧ず鍦ㄦ帶鍒跺彴 |
| `"Hello, World!"` | 涓€涓瓧绗︿覆锛堜竴娈垫枃瀛楋級 |
| `;` | 姣忔潯璇彞缁撴潫閮借鍔犲垎鍙凤紝璺熻嫳鏂囧彞鍙峰樊涓嶅 |

鈿狅笍 **鍑犱釜闆跺熀纭€鏈€瀹规槗蹇界暐鐨勭粏鑺傦細**

1. Java **涓ユ牸鍖哄垎澶у皬鍐?*锛歚Main` 鍜?`main` 鏄袱涓畬鍏ㄤ笉鍚岀殑涓滆タ
2. 鏂囦欢鍚嶅繀椤诲彨 `HelloWorld.java`锛屽繀椤诲拰 `public class` 鍚庨潰鐨勫悕瀛?*瀹屽叏涓€鑷?*
3. 姣忔潯璇彞閮藉繀椤讳互 `;` 缁撴潫锛屽皯涓€涓氨浼氱紪璇戝け璐?4. 澶ф嫭鍙?`{}` 蹇呴』閰嶅锛屽皯涓€涓篃浼氬け璐?
涓轰粈涔堝繀椤绘湁 `main` 鏂规硶锛熷洜涓?JVM 鍚姩鏃跺彧璁ゅ畠锛岀被浼间簬涓€鏍嬫ゼ蹇呴』鏈夊ぇ闂ㄥ彛銆傛墍鏈?Java 搴旂敤绋嬪簭閮戒粠 `main` 寮€濮嬫墽琛屻€俙String[] args` 鏄懡浠よ鍙傛暟锛堜竴鑸敤涓嶅埌锛夛紝鍏堜笉鐢ㄧ銆?
`System.out.println` 涓細
- `System` 鏄?Java 鑷甫鐨勪竴涓郴缁熷伐鍏风被
- `out` 鏄畠閲岄潰鐨?杈撳嚭"瀵硅薄
- `println` 鏄?鎵撳嵃涓€琛岋紙print line锛?鐨勬剰鎬濓紝浼氳嚜鍔ㄦ崲琛?
濡傛灉浣犲彧鎯虫墦鍗颁笉鎹㈣锛岀敤 `System.out.print` 灏辫銆?
## 1.3 鍙橀噺涓庢暟鎹被鍨?
**鍙橀噺锛圴ariable锛?* 鏄▼搴忛噷瀛樻暟鎹殑"鐩掑瓙"銆傜洅瀛愪笂璐翠釜鏍囩锛堝彉閲忓悕锛夛紝鐩掑瓙閲屾斁涓滆タ锛堝€硷級銆?
```java
int age = 20;
String name = "鍒樼晠";
boolean isStudent = true;
double price = 19.9;
long bigNumber = 99999999999L;
```

閫愯瑙ｉ噴锛?
- `int age = 20;` 鈥斺€?鎴戝噯澶囦竴涓悕鍙?`age` 鐨勭洅瀛愶紝瑙勫畾鍙兘鏀炬暣鏁帮紙int锛夛紝閲岄潰鏀句簡 20銆?- `String name = "鍒樼晠";` 鈥斺€?涓€涓悕鍙?`name` 鐨勭洅瀛愶紝鏀惧瓧绗︿覆锛屽唴瀹规槸 "鍒樼晠"銆?- `boolean isStudent = true;` 鈥斺€?甯冨皵鐩掑瓙锛屽彧鑳借 `true` 鎴?`false`锛堟槸鎴栧惁锛夈€?- `double price = 19.9;` 鈥斺€?瑁呭皬鏁扮殑鐩掑瓙銆?- `long bigNumber = 99999999999L;` 鈥斺€?瑁呰秴澶ф暣鏁扮殑鐩掑瓙锛屾敞鎰忔湯灏剧殑 `L`锛屽憡璇夌紪璇戝櫒杩欐槸 long 绫诲瀷銆?
Java 鐨勫父鐢ㄥ熀鏈暟鎹被鍨嬩竴瑙堬細

| 绫诲瀷 | 涓枃鍚?| 鍗犵敤瀛楄妭 | 鑼冨洿/绀轰緥 |
| --- | --- | --- | --- |
| `byte` | 瀛楄妭 | 1 | -128 ~ 127 |
| `short` | 鐭暣鏁?| 2 | -32768 ~ 32767 |
| `int` | 鏁存暟 | 4 | 绾?卤21 浜?|
| `long` | 闀挎暣鏁?| 8 | 闈炲父澶э紝闇€鍔?L |
| `float` | 娴偣鏁?| 4 | 灏忔暟锛岄渶鍔?F |
| `double` | 鍙岀簿搴︽诞鐐?| 8 | 榛樿鐨勫皬鏁扮被鍨?|
| `boolean` | 甯冨皵 | 1 | true/false |
| `char` | 鍗曚釜瀛楃 | 2 | 'A'銆?涓? |

鈿狅笍 娉ㄦ剰 `String` 涓嶆槸鍩烘湰绫诲瀷锛屽畠鏄?*绫伙紙Class锛?*锛屾墍浠ラ瀛楁瘝澶у啓銆傛垜浠」鐩噷鍑犱箮鎵€鏈夌殑"鏂囧瓧"閮界敤 String銆?
绫绘瘮涓€涓嬶細

- `int` 鍍忎竴涓皬鍙锋枃浠舵煖锛堝彧鑳芥斁鏁存暟鏂囦欢澶癸級
- `String` 鍍忎竴涓ぇ鍙锋。妗堢洅锛堣兘鏀惧悇绉嶉暱搴︾殑鏂囧瓧璧勬枡锛?- 缁欏彉閲忚祴鍊?= 鎶婁笢瑗垮杩涚洅瀛?- 璇诲彇鍙橀噺 = 鐪嬬洅瀛愰噷鏈変粈涔?
## 1.4 鎺у埗娴侊細if/else銆乫or銆亀hile銆乻witch

绋嬪簭濡傛灉鍙槸浠庝笂寰€涓嬫墽琛岋紝鑳藉仛鐨勪簨鎯呭氨澶皯浜嗐€?*鎺у埗娴侊紙Control Flow锛?* 璁╃▼搴忓彲浠ユ牴鎹潯浠跺垽鏂€佸惊鐜墽琛屻€?
### 1.4.1 if / else锛堝鏋溾€︹€﹀惁鍒欌€︹€︼級

```java
int score = 85;
if (score >= 90) {
    System.out.println("浼樼");
} else if (score >= 60) {
    System.out.println("鍙婃牸");
} else {
    System.out.println("涓嶅強鏍?);
}
```

璇昏捣鏉ヨ窡涓枃鍑犱箮涓€鏍凤細濡傛灉鍒嗘暟 鈮?90锛屾墦鍗颁紭绉€锛涘惁鍒欏鏋?鈮?60锛屾墦鍗板強鏍硷紱鍚﹀垯鎵撳嵃涓嶅強鏍笺€?
### 1.4.2 for 寰幆锛堥噸澶?N 娆★級

```java
for (int i = 1; i <= 5; i++) {
    System.out.println("绗?" + i + " 娆℃墦鍗?);
}
```

`for` 涓夋寮忥細

1. `int i = 1` 鈥斺€?鍒濆鍖栵紝浠?1 寮€濮?2. `i <= 5` 鈥斺€?鏉′欢锛屽彧瑕佹弧瓒冲氨缁х画寰幆
3. `i++` 鈥斺€?姣忚疆缁撴潫鍔?1锛堢瓑鍚屼簬 `i = i + 1`锛?
杈撳嚭锛?
```
绗?1 娆℃墦鍗?绗?2 娆℃墦鍗?绗?3 娆℃墦鍗?绗?4 娆℃墦鍗?绗?5 娆℃墦鍗?```

### 1.4.3 while 寰幆锛堟潯浠舵弧瓒冲氨涓€鐩村惊鐜級

```java
int count = 0;
while (count < 3) {
    System.out.println("褰撳墠 count = " + count);
    count++;
}
```

閫傚悎 **涓嶇煡閬撹寰幆澶氬皯娆?* 鐨勫満鏅紝姣斿"璇诲埌鏂囦欢缁撳熬灏卞仠"銆?
### 1.4.4 switch锛堝鍒嗘敮閫夋嫨锛?
```java
int day = 3;
switch (day) {
    case 1: System.out.println("鍛ㄤ竴"); break;
    case 2: System.out.println("鍛ㄤ簩"); break;
    case 3: System.out.println("鍛ㄤ笁"); break;
    default: System.out.println("鍏朵粬");
}
```

`switch` 閫傚悎鍒嗘敮寰堝鐨勬儏鍐点€傗殸锔?鍒繕浜?`break;`锛屼笉鐒朵細"绌块€?鍒颁笅涓€涓?case銆?
## 1.5 绫诲拰瀵硅薄锛堥噸鐐癸紒锛?
杩欐槸 Java 鐨勬牳蹇冩蹇碉紝涔熸槸闆跺熀纭€鏈€闅剧殑涓€鍏炽€傝鍙嶅璇昏繖涓€鑺傘€?
### 绫绘槸妯″瓙锛屽璞℃槸閾搁€犲嚭鏉ョ殑闆朵欢 馃彮

鎯宠薄涓€涓伐鍘傦細

- **绫伙紙Class锛?* 灏卞儚涓€涓?閾搁€犳ā瀛?銆傚畠瀹氫箟浜嗭細瑕佸仛浠€涔堝舰鐘躲€佹湁鍑犱釜娲炪€佺敤浠€涔堟潗鏂欍€?- **瀵硅薄锛圤bject锛?* 灏卞儚鐢ㄦā瀛愰摳閫犲嚭鏉ョ殑"瀹炵墿闆朵欢"銆備竴涓ā瀛愬彲浠ラ摳閫犳棤鏁颁釜闆朵欢銆?
涓句釜渚嬪瓙锛屾垜浠」鐩噷鏈変釜 `SysUser`锛堢郴缁熺敤鎴凤級绫伙紝瀹冨畾涔変簡"鐢ㄦ埛"闀夸粈涔堟牱銆傜畝鍖栫増锛?
```java
public class SysUser {
    // 瀛楁锛堝睘鎬э級锛氭瘡涓敤鎴烽兘鏈夎繖浜涗俊鎭?    private Long id;
    private String username;
    private String password;
    private Integer age;

    // 鏂规硶锛堣涓猴級锛氱敤鎴疯兘鍋氱殑浜?    public void sayHello() {
        System.out.println("澶у濂斤紝鎴戞槸 " + username);
    }

    // Getter / Setter锛堣鍐欏瓧娈碉級
    public String getUsername() { return username; }
    public void setUsername(String username) { this.username = username; }
}
```

浠ｇ爜瑙ｈ琛細

| 琛屽彿鐗囨 | 浣滅敤 |
| --- | --- |
| `public class SysUser` | 瀹氫箟涓€涓悕涓?SysUser 鐨勭被锛堟ā瀛愶級 |
| `private Long id;` | 妯″瓙閲屾湁涓€涓?id 灞炴€э紝private 琛ㄧず澶栭儴涓嶈兘鐩存帴璁块棶 |
| `private String username;` | 鐢ㄦ埛鍚嶅睘鎬?|
| `public void sayHello()` | 涓€涓涓猴細鎵撴嫑鍛?|
| `getUsername()` / `setUsername()` | 鏆撮湶缁欏閮ㄨ鍐?username 鐨勫叆鍙?|

鎺ョ潃鎴戜滑鐢ㄨ繖涓ā瀛?閾搁€?涓や釜瀵硅薄锛?
```java
public class Test {
    public static void main(String[] args) {
        // new 鍏抽敭瀛?= 鐢ㄦā瀛愰摳閫犱竴涓柊瀵硅薄
        SysUser user1 = new SysUser();
        user1.setUsername("寮犱笁");

        SysUser user2 = new SysUser();
        user2.setUsername("鏉庡洓");

        user1.sayHello();  // 杈撳嚭锛氬ぇ瀹跺ソ锛屾垜鏄?寮犱笁
        user2.sayHello();  // 杈撳嚭锛氬ぇ瀹跺ソ锛屾垜鏄?鏉庡洓
    }
}
```

閫愯瑙ｉ噴锛?
- `new SysUser()` 鈥斺€?鐢?SysUser 杩欎釜妯″瓙閾搁€犱竴涓柊瀵硅薄
- `user1` 鍜?`user2` 鏄袱涓笉鍚岀殑瀵硅薄锛屼簰鐩哥嫭绔?- 鏀?user1 鐨勫悕瀛楋紝涓嶄細褰卞搷 user2

馃幆 **鏍稿績瑕佺偣锛?*

> 绫绘槸"璁捐鍥?锛屽璞℃槸"鎸夎璁″浘鐩栧嚭鏉ョ殑鎴垮瓙"銆傝璁″浘鍙湁涓€浠斤紝鎴垮瓙鍙互鐩栧緢澶氬骇銆?
鎴戜滑椤圭洰閲?`SysUser`銆乣BlogPost`銆乣BlogComment` 绛夋墍鏈?entity锛堝疄浣撶被锛夐兘鏄繖绉嶆ā寮忥紝鍒嗗埆瀵瑰簲鏁版嵁搴撶殑涓€寮犺〃銆備竴琛屾暟鎹?= 涓€涓璞°€?
### private銆乸ublic 鏄粈涔堬紵

瀹冧滑鍙?**璁块棶淇グ绗︼紙Access Modifier锛?*锛?
| 淇グ绗?| 鍚箟 |
| --- | --- |
| `public` | 鍏紑锛岃皝閮借兘鐢?|
| `private` | 绉佹湁锛屽彧鏈夋湰绫诲唴閮ㄨ兘鐢?|
| `protected` | 淇濇姢锛屾湰绫诲拰瀛愮被鑳界敤 |
| 涓嶅啓 | 榛樿锛屽悓涓€涓寘鍐呭彲鐢?|

閫氬父瀛楁鍐?`private`锛屾柟娉曞啓 `public`锛岃繖鏄?灏佽"鐨勬渶浣冲疄璺点€?
## 1.6 鏂规硶锛氬弬鏁般€佽繑鍥炲€笺€侀噸杞?
**鏂规硶锛圡ethod锛?* 灏辨槸涓€娈靛彲浠ラ噸澶嶄娇鐢ㄧ殑浠ｇ爜鍧楋紝绫讳技鏁板閲岀殑鍑芥暟銆?
```java
public int add(int a, int b) {
    return a + b;
}
```

鎷嗚В锛?
| 閮ㄥ垎 | 鍚箟 |
| --- | --- |
| `public` | 璋侀兘鍙互璋冪敤 |
| `int` | 杩斿洖鍊肩被鍨嬶紝杩欓噷杩斿洖涓€涓暣鏁?|
| `add` | 鏂规硶鍚?|
| `(int a, int b)` | 涓や釜鍙傛暟锛歛 鍜?b |
| `return a + b;` | 杩斿洖 a + b 鐨勭粨鏋?|

璋冪敤锛?
```java
int sum = add(3, 5);  // sum = 8
```

### 娌℃湁杩斿洖鍊肩敤 void

```java
public void printHello() {
    System.out.println("Hello");
}
```

`void` 琛ㄧず"娌℃湁涓滆タ瑕佽繑鍥?锛岀被浼?鎴戝府浣犲仛杩欎欢浜嬶紝浣嗕笉缁欎綘涓滆タ"銆?
### 鏂规硶閲嶈浇锛圤verload锛?
鍚屽悕鏂规硶銆佸弬鏁颁笉鍚?= 閲嶈浇銆?
```java
public int add(int a, int b) { return a + b; }
public double add(double a, double b) { return a + b; }
public int add(int a, int b, int c) { return a + b + c; }
```

缂栬瘧鍣ㄤ細鏍规嵁浣犱紶鐨勫弬鏁拌嚜鍔ㄩ€夋嫨鏈€鍖归厤鐨勭増鏈€?
## 1.7 闆嗗悎锛歀ist 鍜?Map

**闆嗗悎锛圕ollection锛?* 灏辨槸瑁呭涓暟鎹殑瀹瑰櫒銆傛渶甯哥敤鐨勪袱绉嶏細

### List 鈥斺€?鏈夊簭鍒楄〃锛堝儚鐏溅杞﹀帰锛屼竴鑺傛尐涓€鑺傦級

```java
import java.util.ArrayList;
import java.util.List;

List<String> users = new ArrayList<>();
users.add("寮犱笁");
users.add("鏉庡洓");
users.add("鐜嬩簲");

System.out.println(users.get(0));  // 寮犱笁
System.out.println(users.size());  // 3
```

`List<String>` 琛ㄧず"瑁?String 鐨勫垪琛?銆俙<String>` 杩欑璇硶鍙?**娉涘瀷锛圙enerics锛?*锛岄檺瀹氬垪琛ㄩ噷鍙兘鏀?String銆?
鎴戜滑椤圭洰閲屾煡璇㈠崥瀹㈡枃绔犲垪琛紝灏变細寰楀埌涓€涓?`List<BlogPost>`銆?
### Map 鈥斺€?閿€煎锛堝儚瀛楀吀锛屾煡"鑻规灉"寰楀埌"apple"锛?
```java
import java.util.HashMap;
import java.util.Map;

Map<String, Object> userInfo = new HashMap<>();
userInfo.put("username", "寮犱笁");
userInfo.put("age", 20);
userInfo.put("isStudent", true);

System.out.println(userInfo.get("username"));  // 寮犱笁
```

`Map<String, Object>` 琛ㄧず"閿槸 String锛屽€兼槸浠绘剰绫诲瀷"鐨勫瓧鍏搞€?
鍚庨潰鍐欐帴鍙ｈ繑鍥炴暟鎹椂锛岀粡甯镐細鐢?Map 涓存椂缁勮涓€浜涘瓧娈点€?
## 1.8 寮傚父澶勭悊 try-catch

绋嬪簭杩愯鏃跺彲鑳戒細鍑洪敊锛屾瘮濡傦細闄や互 0銆佽鍙栦竴涓笉瀛樺湪鐨勬枃浠躲€佺綉缁滄柇寮€銆傝繖浜涙儏鍐靛彨 **寮傚父锛圗xception锛?*銆?
馃尠 绫绘瘮锛氫綘姝ｅ湪鐑у紑姘达紝绐佺劧鍋滅數浜嗐€傚鏋滀笉澶勭悊锛屾暣涓▼搴忎細"宕╂簝閫€鍑?銆傚鐞嗗畠鐨勬柟寮忓氨鏄?`try-catch`锛?
```java
try {
    int result = 10 / 0;  // 杩欒浼氭姏寮傚父
    System.out.println("姘歌繙涓嶄細鎵ц鍒拌繖閲?);
} catch (ArithmeticException e) {
    System.out.println("鍑洪敊浜嗭細" + e.getMessage());
} finally {
    System.out.println("涓嶇鍑轰笉鍑洪敊锛岃繖閲岄兘浼氭墽琛?);
}
```

| 鍧?| 浣滅敤 |
| --- | --- |
| `try` | 鎶婂彲鑳藉嚭閿欑殑浠ｇ爜鏀惧湪杩欓噷 |
| `catch` | 鎶撲綇寮傚父锛屽仛澶勭悊 |
| `finally` | 鏃犺鏄惁寮傚父閮戒細鎵ц锛屽父鐢ㄤ簬鍏抽棴璧勬簮 |

鎴戜滑椤圭洰閲屾湁涓?**鍏ㄥ眬寮傚父澶勭悊鍣?* `GlobalExceptionHandler`锛屾墍鏈?Controller 鎶涘嚭鐨勫紓甯搁兘浼氳瀹冪粺涓€鎹曡幏骞惰繑鍥炲弸濂界殑閿欒淇℃伅銆傝繖鏍锋垜浠?Controller 閲屽彧绠″啓姝ｅ父閫昏緫锛屽嚭閿欑殑浜嬩氦缁欏畠灏辫銆?
## 1.9 娉ㄨВ锛圓nnotation锛夋槸浠€涔?
**娉ㄨВ锛圓nnotation锛?* 鏄竴绉?鏍囩"锛屾斁鍦ㄧ被銆佹柟娉曘€佸瓧娈靛ご涓婏紝鍛婅瘔缂栬瘧鍣ㄦ垨妗嗘灦"鎴戞湁鐗规畩鐢ㄩ€?銆?
鏈€甯歌鐨勫唴缃敞瑙?`@Override`锛?
```java
@Override
public String toString() {
    return "鎴戞槸涓€涓敤鎴峰璞?;
}
```

`@Override` 琛ㄧず"鎴戦噸鍐欎簡鐖剁被鐨勬柟娉?銆傚鏋滀綘鎷奸敊浜嗘柟娉曞悕锛岀紪璇戝櫒浼氭姤閿欐彁閱掍綘銆?
Spring Boot 澶ч噺浣跨敤娉ㄨВ锛岀湅涓€鐪兼垜浠」鐩殑鍚姩绫伙紙鏉ヨ嚜 `EduProjectApplication.java`锛夛細

```java
@SpringBootApplication(exclude = {
    SecurityAutoConfiguration.class,
    UserDetailsServiceAutoConfiguration.class
})
@Import(SecurityConfig.class)
@EnableScheduling
public class EduProjectApplication {
    ...
}
```

杩欓噷灏辨湁 `@SpringBootApplication`銆乣@Import`銆乣@EnableScheduling` 涓変釜娉ㄨВ锛屾瘡涓兘瀵瑰簲涓€绉?鍔熻兘寮€鍏?銆傜 4 绔犱細璇︾粏璁层€?
馃幆 鐜板湪浣犲彧瑕佽浣忎竴鍙ヨ瘽锛?*娉ㄨВ = 妗嗘灦鐢ㄧ殑鏍囩锛屽憡璇夋鏋?鎴戞槸涓壒娈婅鑹?**銆?
## 1.10 鍖呭拰瀵煎叆 import

褰撲唬鐮侀噺澶氫簡锛屽嚑鐧句釜 Java 鏂囦欢鎸ゅ湪涓€璧蜂細涔卞锛屾墍浠?Java 鐢?**鍖咃紙Package锛?* 鏉ュ垎缁勶紝绫讳技鏂囦欢澶广€?
```java
package com.example.edu_project.entity;
```

杩欎竴琛岃"鎴戣繖涓枃浠跺睘浜?`com.example.edu_project.entity` 鍖?銆傚搴斿埌纾佺洏涓婄殑鐩綍灏辨槸锛?
```
src/main/java/com/example/edu_project/entity/
```

瑕佷娇鐢ㄥ埆鐨勫寘閲岀殑绫伙紝寰楀厛 `import`锛?
```java
import java.util.List;
import java.util.ArrayList;
import com.example.edu_project.entity.SysUser;
```

鈿狅笍 鍖呭悕涔犳儻鐢?*鍏ㄥ皬鍐?*锛屽苟涓旈噰鐢?鍙嶅悜鍩熷悕"椋庢牸锛坈om.鍏徃.椤圭洰.妯″潡锛夛紝淇濊瘉鍏ㄧ悆鍞竴銆傛垜浠」鐩墍鏈変唬鐮侀兘鍦?`com.example.edu_project` 杩欎釜鏍瑰寘涓嬨€?
---

瀛﹀畬绗?1 绔狅紝浣犲凡缁忔帉鎻′簡 Java 璇█鐨勫熀鏈鏋躲€傛帴涓嬫潵鎴戜滑瑕佹妸"宸ュ叿"瑁呭埌鐢佃剳涓婏紝璁╀唬鐮佽兘璺戣捣鏉ャ€?
---

# 绗?2 绔?寮€鍙戠幆澧冩惌寤?
宸ユ鍠勫叾浜嬶紝蹇呭厛鍒╁叾鍣ㄣ€傝繖涓€绔犳垜浠竴璧锋妸寮€鍙戠幆澧冭濂姐€傝鎸夐『搴忔搷浣滐紝涓嶈璺虫銆?
## 2.1 瀹夎 JDK 21

**JDK锛圝ava Development Kit锛?* 鏄?Java 寮€鍙戝伐鍏峰寘锛屽寘鍚紪璇戝櫒銆丣VM 绛夈€傛垜浠」鐩姹?JDK 21锛堝湪 `pom.xml` 閲岀湅鍒?`<java.version>21</java.version>`锛夈€?
### 1锔忊儯 涓嬭浇

鎺ㄨ崘鍘?Oracle 瀹樼綉鎴栬€?Adoptium 涓嬭浇锛?
- Oracle: https://www.oracle.com/java/technologies/downloads/
- Adoptium锛堟帹鑽愶紝鍏嶈垂寮€婧愶級: https://adoptium.net/

閫夋嫨 **JDK 21 LTS** 鐗堟湰锛屽搴斾綘鐨勬搷浣滅郴缁燂紙Windows x64 閫?.msi 瀹夎鍖咃級銆?
### 2锔忊儯 瀹夎

Windows 涓嬪弻鍑?`.msi`锛屼竴璺笅涓€姝ュ嵆鍙€傞粯璁や細瑁呭埌 `C:\Program Files\Java\jdk-21\`銆?
### 3锔忊儯 閰嶇疆 JAVA_HOME 鐜鍙橀噺

杩欎竴姝ュ緢鍏抽敭銆侻aven銆両DEA 閮介潬瀹冩壘 JDK銆?
Windows 11 鎿嶄綔姝ラ锛?
1. 鍙抽敭"姝ょ數鑴? 鈫?灞炴€?鈫?楂樼骇绯荤粺璁剧疆 鈫?鐜鍙橀噺
2. 鍦?绯荤粺鍙橀噺"閲屾柊寤猴細
   - 鍙橀噺鍚嶏細`JAVA_HOME`
   - 鍙橀噺鍊硷細`C:\Program Files\Java\jdk-21`锛堜綘鐨勫疄闄呭畨瑁呰矾寰勶級
3. 鎵惧埌 `Path` 鍙橀噺锛岀紪杈戯紝鏂板涓€琛岋細`%JAVA_HOME%\bin`
4. 涓€璺‘瀹氫繚瀛?
### 4锔忊儯 楠岃瘉

鎵撳紑 **鏂扮殑** cmd 鎴?PowerShell锛堝繀椤绘柊鎵撳紑锛屾棫绐楀彛鐨勭幆澧冨彉閲忎笉浼氬埛鏂帮級锛岃緭鍏ワ細

```bash
java -version
javac -version
```

搴旇鐪嬪埌绫讳技锛?
```
java version "21.0.2" 2024-01-16 LTS
javac 21.0.2
```

鈿狅笍 濡傛灉鍑虹幇"涓嶆槸鍐呴儴鎴栧閮ㄥ懡浠?锛岃鏄?Path 娌￠厤瀵癸紝鍥炲幓妫€鏌ャ€?
## 2.2 瀹夎 IntelliJ IDEA

**IDE锛圛ntegrated Development Environment锛岄泦鎴愬紑鍙戠幆澧冿級** 鏄啓浠ｇ爜鐨?瓒呯骇璁颁簨鏈?锛岃嚜甯︽櫤鑳芥彁绀恒€佽嚜鍔ㄨˉ鍏ㄣ€佽皟璇曞櫒绛夈€侸ava 鍚庣寮€鍙戦閫?IntelliJ IDEA銆?
涓嬭浇鍦板潃锛歨ttps://www.jetbrains.com/idea/download/

### 绀惧尯鐗?vs 涓撲笟鐗?
| 鐗堟湰 | 浠锋牸 | 鏄惁鏀寔 Spring | 鎺ㄨ崘 |
| --- | --- | --- | --- |
| Community锛堢ぞ鍖虹増锛?| 鍏嶈垂 | 閮ㄥ垎鏀寔锛屼笉甯?Spring 鎻掍欢 | 瀛︿範鍒濇湡鍙敤 |
| Ultimate锛堜笓涓氱増锛?| 鏀惰垂锛堝鐢熷厤璐癸級 | 瀹屾暣鏀寔 Spring銆佹暟鎹簱闈㈡澘绛?| 鉁?寮虹儓鎺ㄨ崘 |

瀛︾敓鍙互鐢?.edu 閭鍘?[JetBrains 瀛︾敓璁″垝](https://www.jetbrains.com/community/education/) 鐢宠鍏嶈垂鐨勪笓涓氱増銆?
### 鍒濇璁剧疆

1锔忊儯 鍚姩 IDEA锛岃烦杩囨杩庨〉闈?2锔忊儯 閫夋嫨涓婚锛圖arcula 榛戣壊鎶ょ溂锛?3锔忊儯 鍦?Settings 鈫?Build 鈫?Build Tools 鈫?Maven 閲屾鏌?Maven 閰嶇疆锛堝悗闈㈠啀璋冿級
4锔忊儯 鍦?File 鈫?Project Structure 鈫?Project SDK 閲岄€?JDK 21

## 2.3 瀹夎 Lombok 鎻掍欢

**Lombok** 鏄竴涓濂囩殑宸ュ叿锛岃兘鑷姩甯綘鐢熸垚 getter / setter / 鏋勯€犲嚱鏁扮瓑"妯℃澘浠ｇ爜"銆傛垜浠」鐩ぇ閲忎娇鐢ㄥ畠锛坄pom.xml` 閲岃兘鐪嬪埌 `lombok` 1.18.40 渚濊禆锛夈€?
IDEA 鍦ㄦ柊鐗堟湰閲屽凡缁忓唴缃?Lombok 鎻掍欢锛屾棤闇€鎵嬪姩瀹夎銆備絾浣犻渶瑕佺‘淇濆畠鍚敤浜嗭細

1. File 鈫?Settings 鈫?Plugins
2. 鎼滅储 "Lombok"锛岀‘璁ょ姸鎬佹槸 Enabled

## 2.4 鍚敤娉ㄨВ澶勭悊鍣紙鍏抽敭锛侊級

鈿狅笍 **杩欎竴姝ュ鏋滃繕浜嗭紝鏁翠釜椤圭洰浼氱垎绾紝鎵€鏈?`@Data`銆乣@Getter` 閮戒笉鐢熸晥锛?*

鎿嶄綔姝ラ锛?
1锔忊儯 File 鈫?Settings
2锔忊儯 鎼滅储 "Annotation Processors"
3锔忊儯 鎵惧埌 "Build, Execution, Deployment 鈫?Compiler 鈫?Annotation Processors"
4锔忊儯 鍕鹃€?鉁?**Enable annotation processing**
5锔忊儯 鐐?OK 淇濆瓨

杩欎竴姝ュ憡璇?IDEA锛?璇峰湪缂栬瘧鏃惰繍琛?Lombok 鐨勬敞瑙ｅ鐞嗗櫒锛岃嚜鍔ㄥ府鎴戠敓鎴愪唬鐮併€?

## 2.5 瀹夎骞堕厤缃?Maven

IDEA 鑷甫浜?Maven锛屽彲浠ュ厛鐢ㄧ潃銆傚鏋滀綘鎯宠嚜宸辫锛?
1. 涓嬭浇 Maven锛歨ttps://maven.apache.org/download.cgi
2. 瑙ｅ帇鍒?`D:\apache-maven-3.9.x`
3. 閰嶇疆鐜鍙橀噺 `MAVEN_HOME` = `D:\apache-maven-3.9.x`
4. 鍦?Path 閲屾坊鍔?`%MAVEN_HOME%\bin`
5. 楠岃瘉锛歚mvn -version`

### 閰嶇疆鍥藉唴闀滃儚锛堟瀬閲嶈锛?
Maven 榛樿浠庡浗澶栨湇鍔″櫒涓嬭浇渚濊禆锛岄€熷害鏋佹參銆傛垜浠繀椤婚厤缃樋閲屼簯闀滃儚銆?
鎵撳紑 `C:\Users\浣犵殑鐢ㄦ埛鍚峔.m2\settings.xml`锛堟病鏈夊氨鑷繁寤轰竴涓級锛屽姞鍏ワ細

```xml
<settings>
  <mirrors>
    <mirror>
      <id>aliyunmaven</id>
      <mirrorOf>*</mirrorOf>
      <name>闃块噷浜戝叕鍏变粨搴?/name>
      <url>https://maven.aliyun.com/repository/public</url>
    </mirror>
  </mirrors>
</settings>
```

鐒跺悗鍦?IDEA 鐨?Settings 鈫?Maven 閲屾妸 "User settings file" 鎸囧悜杩欎釜 `settings.xml`锛屼笅杞介€熷害浼氫粠 KB/s 鎻愬崌鍒?MB/s銆?
## 2.6 瀹夎 MySQL 8 + 鍒涘缓鏁版嵁搴?
鎴戜滑椤圭洰鐢ㄧ殑鏄?**MySQL 8.x**銆?
### 1锔忊儯 涓嬭浇瀹夎

鍘?https://dev.mysql.com/downloads/installer/ 涓?MySQL Installer for Windows锛岄€?Community 鐗堬紝鎸夊紩瀵间竴姝ユ瑁呫€?
瀹夎鏃朵細璁╀綘璁?root 瀵嗙爜锛?*鍔″繀璁颁綇杩欎釜瀵嗙爜**銆?
### 2锔忊儯 楠岃瘉

鎵撳紑鍛戒护琛岋細

```bash
mysql -u root -p
```

杈撳叆瀵嗙爜鍚庤兘杩涘叆 `mysql>` 鎻愮ず绗﹀氨璇存槑鎴愬姛浜嗐€?
### 3锔忊儯 鍒涘缓椤圭洰鏁版嵁搴?
浠庢垜浠殑 `.env.example` 鏂囦欢鐪嬪埌锛岄」鐩暟鎹簱鍚嶅簲璇ュ彨 `campus_blog`锛?
```sql
CREATE DATABASE campus_blog DEFAULT CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci;
CREATE USER 'campus_blog'@'%' IDENTIFIED BY 'your_password_here';
GRANT ALL PRIVILEGES ON campus_blog.* TO 'campus_blog'@'%';
FLUSH PRIVILEGES;
```

閫愯瑙ｉ噴锛?
| 璇彞 | 浣滅敤 |
| --- | --- |
| `CREATE DATABASE campus_blog ...` | 鍒涘缓涓€涓悕鍙?campus_blog 鐨勬暟鎹簱锛屽瓧绗﹂泦 utf8mb4锛堟敮鎸?emoji锛?|
| `CREATE USER 'campus_blog' ...` | 鍒涘缓涓€涓笓鐢ㄨ处鍙凤紝閬垮厤鐩存帴鐢?root |
| `GRANT ALL PRIVILEGES ...` | 鎶婅繖涓暟鎹簱鐨勬墍鏈夋潈闄愮粰杩欎釜璐﹀彿 |
| `FLUSH PRIVILEGES` | 鍒锋柊鏉冮檺浣跨敓鏁?|

## 2.7 瀹夎鏁版嵁搴撳彲瑙嗗寲宸ュ叿

鍏夌敤鍛戒护琛屾搷浣?MySQL 澶疮锛屾垜浠瑁呬釜鍙鍖栧伐鍏凤細

| 宸ュ叿 | 浠锋牸 | 鎺ㄨ崘 |
| --- | --- | --- |
| Navicat | 鏀惰垂 | 猸愨瓙猸愨瓙猸?|
| DataGrip锛圝etBrains锛?| 鏀惰垂锛堝鐢熷厤璐癸級 | 猸愨瓙猸愨瓙猸?|
| DBeaver | 鍏嶈垂寮€婧?| 猸愨瓙猸愨瓙 |
| IDEA 鑷甫 Database 闈㈡澘锛堜笓涓氱増锛?| 鍐呯疆 | 猸愨瓙猸愨瓙猸?鎺ㄨ崘锛?|

濡傛灉浣犵敤 IDEA 涓撲笟鐗堬紝鐩存帴鐢ㄥ彸渚х殑 "Database" 闈㈡澘锛?
1. 鐐?+ 鈫?Data Source 鈫?MySQL
2. 濉?Host銆丳ort (3306)銆乁ser銆丳assword銆丏atabase (campus_blog)
3. 鐐?Test Connection
4. 绗竴娆′細璁╀綘涓嬭浇 driver锛岀偣 Download

鎴愬姛鍚庝綘鑳藉湪闈㈡澘閲岀湅鍒版墍鏈夎〃銆佸瓧娈碉紝鑳界洿鎺ュ啓 SQL 鏌ヨ銆?
## 2.8 楠岃瘉鏁村鐜

鎴戜滑鐢ㄤ竴涓渶灏忛」鐩妸娴佺▼璺戦€氥€傛墦寮€ IDEA锛?
1锔忊儯 New Project 鈫?閫?Maven锛孞DK 閫?21
2锔忊儯 GroupId: `com.test`, ArtifactId: `hello-test`
3锔忊儯 鍒涘缓鍚庣瓑 Maven 涓嬭浇瀹屼緷璧?4锔忊儯 鍦?`src/main/java` 涓嬫柊寤?`com.test.HelloApp` 绫伙細

```java
package com.test;

public class HelloApp {
    public static void main(String[] args) {
        System.out.println("鐜瑁呭ソ鍟︼紒馃帀");
    }
}
```

5锔忊儯 鍙抽敭 鈫?Run 'HelloApp.main()'
6锔忊儯 鐪嬪埌搴曢儴鎺у埗鍙拌緭鍑?"鐜瑁呭ソ鍟︼紒馃帀" 灏辨垚鍔熶簡

## 2.9 甯歌鐜闂鎺掓煡

闆跺熀纭€鏈€瀹规槗韪╃殑鍧戯細

| 闂 | 鍘熷洜 | 瑙ｅ喅鏂规硶 |
| --- | --- | --- |
| `java -version` 鎵句笉鍒板懡浠?| JAVA_HOME 鎴?Path 娌￠厤瀵?| 閲嶆柊妫€鏌ョ幆澧冨彉閲忥紝**閲嶆柊鎵撳紑** cmd |
| IDEA 鏄剧ず "Cannot resolve symbol" | Maven 娌′笅杞藉畬渚濊禆 | 鍙抽敭 pom.xml 鈫?Maven 鈫?Reload Project |
| `@Data` 绛?Lombok 娉ㄨВ鐖嗙孩 | 娉ㄨВ澶勭悊鍣ㄦ病鍚敤 | 瑙?2.4 鑺?|
| Maven 涓嬭浇鐗瑰埆鎱?| 娌￠厤闃块噷浜戦暅鍍?| 瑙?2.5 鑺?|
| 杩炰笉涓?MySQL | 瀵嗙爜閿?/ 绔彛琚崰 / 闃茬伀澧?| 妫€鏌?.env 閲岀殑瀵嗙爜銆佺鍙ｏ紱鐢ㄥ彲瑙嗗寲宸ュ叿鍏堟祴杩為€?|
| 椤圭洰鍚姩鎶?"绔彛宸插崰鐢? | 8825 绔彛琚埆鐨勭▼搴忓崰浜?| 鍦?.env 閲屾敼 SERVER_PORT 鎴栨潃鎺夊崰绔彛鐨勮繘绋?|
| 鍚姩鍚庤 "鎵句笉鍒?DB_HOST" | 娌″缓 .env 鏂囦欢 | `cp .env.example .env`锛屽啀淇敼鍊?|

---

鐜瑁呭ソ浜嗭紝鎭枩浣犺繄杩囨渶鐥涜嫤鐨勪竴鍏?馃挭 鎺ヤ笅鏉ユ垜浠璇?Maven 鍜岄」鐩粨鏋勩€?
---

# 绗?3 绔?Maven 涓庨」鐩粨鏋?
## 3.1 Maven 鏄粈涔?
**Maven** 鏄竴涓?**椤圭洰鏋勫缓鍜屼緷璧栫鐞嗗伐鍏?*銆傝繖鍙ヨ瘽缈昏瘧鎴愪汉璇濓細

- **渚濊禆绠＄悊**锛氫綘鎯崇敤鍒汉鍐欏ソ鐨勫簱锛堟瘮濡?Spring Boot銆丮ySQL 椹卞姩锛夛紝涓嶇敤鑷繁鍘荤綉涓婃壘 jar 鍖咃紝鍙鍦?pom.xml 閲屽啓涓€琛岄厤缃紝Maven 鑷姩甯綘涓嬭浇銆?- **椤圭洰鏋勫缓**锛氱紪璇戙€佹墦鍖呫€佽繍琛屾祴璇曪紝涓€琛屽懡浠ゆ悶瀹氥€?
馃尠 绫绘瘮锛?
| 浣犺璇嗙殑 | 绫讳技鐨勫伐鍏?|
| --- | --- |
| 瀹夊崜寮€鍙?| Gradle |
| 鍓嶇寮€鍙?| npm / yarn / pnpm |
| Python 寮€鍙?| pip / poetry |
| Java 寮€鍙?| **Maven** / Gradle |

瀹冧滑閮藉湪鍋氬悓涓€浠朵簨锛氱鐞嗛」鐩敤鍒扮殑"绉湪鍧?銆?
## 3.2 pom.xml 鏂囦欢缁撴瀯璇﹁В

`pom.xml` 鏄?Maven 椤圭洰鐨?韬唤璇?锛孭OM = Project Object Model锛堥」鐩璞℃ā鍨嬶級銆傛垜浠湅涓€涓嬫垜浠」鐩殑瀹為檯 pom.xml锛堣妭閫夛級锛?
```xml
<project xmlns="http://maven.apache.org/POM/4.0.0" ...>
    <modelVersion>4.0.0</modelVersion>

    <parent>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-parent</artifactId>
        <version>3.0.12</version>
        <relativePath/>
    </parent>

    <groupId>com.example</groupId>
    <artifactId>edu_project</artifactId>
    <version>0.0.1-SNAPSHOT</version>
    <name>edu_project</name>
    <description>鏍″洯鍗氬璁哄潧绯荤粺 - 鍚庣</description>

    <properties>
        <java.version>21</java.version>
        <mybatis-plus.version>3.5.5</mybatis-plus.version>
        ...
    </properties>

    <dependencies>
        ...
    </dependencies>
</project>
```

楠ㄦ灦瑙ｈ锛?
| 鏍囩 | 鍚箟 |
| --- | --- |
| `<modelVersion>` | POM 鐨勭増鏈紝鍥哄畾 4.0.0 |
| `<parent>` | 鐖跺伐绋嬶紝缁ф壙鍏朵緷璧栫鐞?|
| `<groupId>` | 缁勭粐 ID锛岀被浼煎叕鍙稿煙鍚嶅弽鍐?|
| `<artifactId>` | 椤圭洰 ID锛坅rtifact = 宸ヤ欢锛?|
| `<version>` | 椤圭洰鐗堟湰鍙?|
| `<properties>` | 灞炴€ч厤缃紝鍙涓嬮潰寮曠敤 |
| `<dependencies>` | 椤圭洰渚濊禆鍒楄〃 |
| `<build>` | 鏋勫缓鐩稿叧閰嶇疆锛堟彃浠讹級 |

## 3.3 渚濊禆绠＄悊锛歡roupId / artifactId / version

姣忎釜 Java 搴撻兘鐢ㄤ笁涓潗鏍囧敮涓€鏍囪瘑锛屽彨 **GAV锛圙roupId-ArtifactId-Version锛?*锛?
```xml
<dependency>
    <groupId>com.baomidou</groupId>
    <artifactId>mybatis-plus-boot-starter</artifactId>
    <version>3.5.5</version>
</dependency>
```

杩欎笁琛岃锛?鎴戣 baomidou 鍏徃寮€鍙戠殑銆佸悕涓?mybatis-plus-boot-starter 鐨勩€?.5.5 鐗堟湰鐨勫簱銆?

Maven 鎷垮埌杩欎釜鍧愭爣鍚庯紝浼氬幓浠撳簱锛堥樋閲屼簯闀滃儚锛夋壘瀵瑰簲鐨?jar 鍖咃紝涓嬭浇鍒颁綘鐢佃剳鐨?`~/.m2/repository/` 鐩綍閲屻€?
馃尠 绫绘瘮锛欸AV 灏卞儚蹇€掑湴鍧€锛?
- groupId = 鍩庡競
- artifactId = 琛楅亾+闂ㄧ墝鍙?- version = 鍏蜂綋妤煎眰

## 3.4 鐖跺伐绋?spring-boot-starter-parent

```xml
<parent>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-parent</artifactId>
    <version>3.0.12</version>
</parent>
```

杩欎竴娈佃〃绀烘垜浠户鎵夸簡 Spring Boot 鐨勭埗宸ョ▼銆傜户鎵跨殑濂藉鏄細

1. **鐗堟湰缁熶竴**锛氱埗宸ョ▼宸茬粡瑙勫畾濂戒簡鍑犵櫨涓父鐢ㄥ簱鐨勭増鏈紝鎴戜滑鍐欎緷璧栨椂鍙互**鐪佺暐 version**锛岀洿鎺ョ敤鐖跺伐绋嬬殑鐗堟湰銆?2. **閰嶇疆缁熶竴**锛氱紪鐮併€丣DK 鐗堟湰銆佹彃浠剁増鏈兘宸茬粡榛樿濂戒簡銆?
绫绘瘮涓€涓嬶細鐖跺伐绋嬪儚"涓€浠藉ぇ绀煎寘濂楅"锛岄噷闈㈡墍鏈変笢瑗块兘宸茬粡鎼厤濂姐€備綘鍙浠庡椁愰噷"鎸戜綘鎯宠鐨?锛屼笉鐢ㄨ嚜宸变竴涓釜璋冨懗銆?
## 3.5 starter 鍚姩鍣?
Spring Boot 鏈変竴涓秴妫掔殑鍙戞槑鍙?**starter锛堝惎鍔ㄥ櫒锛?*銆?
鐪嬫垜浠」鐩噷鐨勶細

```xml
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-web</artifactId>
</dependency>
```

杩欎釜 `spring-boot-starter-web` 瀹為檯涓婃槸涓?**"鍏ㄥ妗?**锛?
- Spring MVC
- Tomcat锛堝唴缃?Web 鏈嶅姟鍣級
- Jackson锛圝SON 澶勭悊锛?- 鍑犲崄涓父鐢?Web 渚濊禆

鍙紩涓€涓?starter锛屽氨鎶婂仛 Web 寮€鍙戠殑鎵€鏈変笢瑗块兘澶囬綈浜嗭紝澶埥浜嗐€?
鎴戜滑椤圭洰鐢ㄥ埌鐨勪富瑕?starter锛?
| starter | 浣滅敤 |
| --- | --- |
| spring-boot-starter-web | Web 寮€鍙戯紙MVC銆乀omcat锛?|
| spring-boot-starter-security | 瀹夊叏璁よ瘉 |
| spring-boot-starter-validation | 鍙傛暟鏍￠獙 |
| spring-boot-starter-test | 鍗曞厓娴嬭瘯 |
| mybatis-plus-boot-starter | MyBatis Plus 鏁版嵁搴?ORM |
| knife4j-openapi3-jakarta-spring-boot-starter | API 鏂囨。 UI |

## 3.6 鏍囧噯鐨?Maven 椤圭洰鐩綍缁撴瀯

```
edu_project/
鈹溾攢鈹€ pom.xml                  鈫?Maven 閰嶇疆
鈹溾攢鈹€ src/
鈹?  鈹溾攢鈹€ main/
鈹?  鈹?  鈹溾攢鈹€ java/            鈫?Java 婧愪唬鐮?鈹?  鈹?  鈹?  鈹斺攢鈹€ com/example/edu_project/
鈹?  鈹?  鈹斺攢鈹€ resources/       鈫?閰嶇疆鏂囦欢銆侀潤鎬佽祫婧?鈹?  鈹?      鈹溾攢鈹€ application.yml
鈹?  鈹?      鈹斺攢鈹€ mapper/      鈫?MyBatis XML
鈹?  鈹斺攢鈹€ test/
鈹?      鈹斺攢鈹€ java/            鈫?娴嬭瘯浠ｇ爜
鈹斺攢鈹€ target/                  鈫?缂栬瘧杈撳嚭锛堣嚜鍔ㄧ敓鎴愶紝涓嶈鎵嬪姩鏀癸級
```

鐗㈣ 3 澶у尯鍩燂細

| 璺緞 | 鐢ㄩ€?|
| --- | --- |
| `src/main/java` | 涓氬姟浠ｇ爜 |
| `src/main/resources` | 閰嶇疆鏂囦欢锛坹ml銆亁ml銆侀潤鎬佽祫婧愶級|
| `src/test/java` | 鍗曞厓娴嬭瘯浠ｇ爜 |

## 3.7 瑙ｈ鏈」鐩殑鐩綍缁撴瀯

鎵撳紑 `D:\MyCode\edu_project\src\main\java\com\example\edu_project\` 浣犱細鐪嬪埌锛?
```
edu_project/
鈹溾攢鈹€ controller/   鈫?鎺у埗鍣ㄥ眰锛堟帴鏀?HTTP 璇锋眰锛?鈹溾攢鈹€ service/      鈫?涓氬姟閫昏緫灞?鈹?  鈹斺攢鈹€ impl/
鈹溾攢鈹€ mapper/       鈫?鏁版嵁搴撹闂眰
鈹溾攢鈹€ entity/       鈫?瀹炰綋绫伙紙瀵瑰簲鏁版嵁搴撹〃锛?鈹溾攢鈹€ dto/          鈫?Data Transfer Object锛堟帴鏀跺墠绔紶鏉ョ殑鏁版嵁锛?鈹溾攢鈹€ vo/           鈫?View Object锛堣繑鍥炵粰鍓嶇鐨勬暟鎹級
鈹溾攢鈹€ config/       鈫?閰嶇疆绫?鈹溾攢鈹€ common/       鈫?鍏叡绫伙紙Result銆佸紓甯哥瓑锛?鈹溾攢鈹€ filter/       鈫?杩囨护鍣?鈹溾攢鈹€ utils/        鈫?宸ュ叿绫?鈹斺攢鈹€ EduProjectApplication.java  鈫?鍚姩鍏ュ彛
```

杩欐槸缁忓吀鐨?**鍒嗗眰鏋舵瀯锛圠ayered Architecture锛?*銆傝姹傛祦鍚戯細

```
娴忚鍣?鈫?Controller 鈫?Service 鈫?Mapper 鈫?MySQL
```

鍚勫眰鑱岃矗涓€鍙ヨ瘽鎬荤粨锛?
| 灞?| 鑱岃矗 | 渚嬪瓙 |
| --- | --- | --- |
| Controller | 鎺?HTTP 璇锋眰銆佽繑鍥炲搷搴?| 鐢ㄦ埛璁块棶 /api/posts |
| Service | 鍐欎笟鍔￠€昏緫 | "鍙戝笘鏃剁Н鍒?+5" |
| Mapper | 璇诲啓鏁版嵁搴?| SELECT * FROM blog_post |
| Entity | 琛ㄧ粨鏋勫搴旂殑 Java 绫?| BlogPost.java |
| DTO | 鍓嶇璇锋眰鍙傛暟 | LoginDTO锛堢敤鎴峰悕+瀵嗙爜锛墊
| VO | 缁欏墠绔殑鏁版嵁 | UserVO锛堜笉鍚瘑鐮侊級|

## 3.8 甯哥敤 Maven 鍛戒护

鍦ㄩ」鐩牴鐩綍鎵撳紑缁堢锛屽彲浠ョ敤杩欎簺鍛戒护锛?
| 鍛戒护 | 浣滅敤 |
| --- | --- |
| `mvn clean` | 娓呯悊 target 鐩綍 |
| `mvn compile` | 缂栬瘧浠ｇ爜 |
| `mvn test` | 杩愯鍗曞厓娴嬭瘯 |
| `mvn package` | 鎵撳寘鎴?jar |
| `mvn clean package` | 鍏堟竻鐞嗗啀鎵撳寘锛堟渶甯哥敤锛墊
| `mvn install` | 鎵撳寘骞舵斁杩涙湰鍦颁粨搴?|
| `mvn spring-boot:run` | 鐩存帴鍚姩 Spring Boot 搴旂敤 |

鎴戜滑椤圭洰瀹為檯涓婄嚎鏃堕€氬父鏄細

```bash
mvn clean package -DskipTests
java -jar target/edu_project-0.0.1-SNAPSHOT.jar
```

绗竴琛屾墦鎴?jar锛堣烦杩囨祴璇曡妭鐪佹椂闂达級锛岀浜岃鐢?java 鍚姩銆?
---

璁插畬浜?Maven锛屼綘搴旇瀵?椤圭洰"鏈変簡鏁翠綋鎰熴€傛渶鍚庝竴绔犳垜浠寮忚璇?Spring Boot銆?
---

# 绗?4 绔?Spring Boot 绗竴璇?
## 4.1 Spring 妗嗘灦瀹舵棌浠嬬粛

鎴戜滑缁忓父鍚埌鐨勫嚑涓悕瀛楋紝鍏崇郴鏄繖鏍风殑锛?
```
Spring Framework 锛堝湴鍩猴級
   鈹斺攢 Spring Boot 锛堣剼鎵嬫灦锛岃鎼ゼ鍙樺揩锛?        鈹斺攢 Spring Cloud 锛堝井鏈嶅姟闆嗙兢鏂规锛?```

| 鍚嶅瓧 | 涓€鍙ヨ瘽浠嬬粛 |
| --- | --- |
| Spring Framework | 鑰佺墝 IoC + AOP 妗嗘灦锛?.0 鍙戝竷浜?2004 骞?|
| Spring Boot | 绠€鍖?Spring 閰嶇疆鐨?鎳掍汉濂楅"锛?014 骞村彂甯冿紝鐜板湪鏈€甯哥敤 |
| Spring Cloud | 鍦?Spring Boot 鍩虹涓婏紝鎻愪緵鍒嗗竷寮忕郴缁熻В鍐虫柟妗?|

鎴戜滑杩欐湰涔﹀鐨勬槸 **Spring Boot**锛屽洜涓哄畠宸茬粡澶熺敤骞朵笖鏈€鍙楁杩庛€?
## 4.2 Spring Boot 鐨?绾﹀畾澶т簬閰嶇疆"鐞嗗康

鑰?Spring 鏃朵唬锛岃鍋氫竴涓?Web 椤圭洰浣犲緱鍐欏嚑鐧捐 XML 閰嶇疆锛氬摢涓枃浠跺す鏀句唬鐮併€佺敤浠€涔堟暟鎹簱杩炴帴姹犮€丣SON 鎬庝箞搴忓垪鍖栤€︹€﹂潪甯哥棝鑻︺€?
Spring Boot 鎻愬嚭浜?**"绾﹀畾澶т簬閰嶇疆锛圕onvention over Configuration锛?**锛?
> 鎴戜滑宸茬粡甯綘鎯冲ソ浜?99% 鍦烘櫙鐨勬渶浣冲疄璺碉紝浣?*鍟ラ兘涓嶅啓灏辫兘鐢?*锛涘彧鏈夌壒娈婇渶姹傛椂鍐嶈鐩栭粯璁ゅ€笺€?
涓句釜渚嬪瓙锛氫綘寮曚簡 `spring-boot-starter-web`锛孲pring Boot 鑷姩锛?
- 鍚姩涓€涓?Tomcat 鏈嶅姟鍣紙绔彛 8080锛?- 閰嶇疆 JSON 搴忓垪鍖?- 閰嶇疆闈欐€佽祫婧愮洰褰?- 閰嶇疆閿欒椤甸潰

浣犲彧瑕佸啓 Controller 灏辫浜嗭紝鐩告瘮鑰?Spring 鑺傜渷浜?90% 鐨勯厤缃伐浣溿€?
## 4.3 鍚姩绫?EduProjectApplication 璇﹁В

鎵撳紑 `D:\MyCode\edu_project\src\main\java\com\example\edu_project\EduProjectApplication.java`锛?
```java
package com.example.edu_project;

import com.example.edu_project.config.DotenvConfig;
import org.slf4j.Logger;
import org.slf4j.LoggerFactory;
import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;
import org.springframework.boot.autoconfigure.security.servlet.SecurityAutoConfiguration;
import org.springframework.boot.autoconfigure.security.servlet.UserDetailsServiceAutoConfiguration;
import org.springframework.context.annotation.Import;
import org.springframework.scheduling.annotation.EnableScheduling;
import com.example.edu_project.config.SecurityConfig;

@SpringBootApplication(exclude = {
    SecurityAutoConfiguration.class,
    UserDetailsServiceAutoConfiguration.class
})
@Import(SecurityConfig.class)
@EnableScheduling
public class EduProjectApplication {

    private static final Logger log = LoggerFactory.getLogger(EduProjectApplication.class);

    public static void main(String[] args) {
        DotenvConfig.load();
        log.info("========================================");
        SpringApplication.run(EduProjectApplication.class, args);
        log.info("   鏍″洯鍗氬璁哄潧绯荤粺鍚姩鎴愬姛锛?);
        log.info("   API鏂囨。鍦板潃锛歨ttp://localhost:8825/api/doc.html");
        log.info("========================================");
    }
}
```

閫愭瑙ｈ锛?
### `@SpringBootApplication`

杩欐槸 Spring Boot 鐨?*鏍稿績娉ㄨВ**锛屽畠瀹為檯涓婃槸 3 涓敞瑙ｇ殑缁勫悎锛?
| 瀛愭敞瑙?| 浣滅敤 |
| --- | --- |
| `@SpringBootConfiguration` | 鏍囪杩欐槸涓€涓厤缃被 |
| `@EnableAutoConfiguration` | 鍚敤鑷姩閰嶇疆锛堟渶绁炲鐨勯儴鍒嗭紒锛墊
| `@ComponentScan` | 鑷姩鎵弿鏈寘鍙婂瓙鍖呬笅鎵€鏈夋爣鏈?@Controller銆丂Service 绛夋敞瑙ｇ殑绫?|

**鑷姩閰嶇疆** 鐨勬剰鎬濇槸锛歋pring Boot 浼氭煡鐪嬩綘寮曚簡鍝簺 starter锛岃嚜鍔ㄥ府浣犻厤濂界浉鍏冲姛鑳姐€傛瘮濡傚彂鐜颁綘寮曚簡 mysql-connector-j锛屽氨鑷姩鍑嗗濂芥暟鎹簮閰嶇疆銆?
### `exclude = {...}`

鎺掗櫎涓や釜榛樿鐨?Spring Security 鑷姩閰嶇疆绫伙紝鍥犱负鎴戜滑椤圭洰鑷畾涔変簡 `SecurityConfig`锛屼笉鎯宠榛樿閰嶇疆骞叉壈銆?
### `@Import(SecurityConfig.class)`

鎵嬪姩瀵煎叆鎴戜滑鑷繁鐨勫畨鍏ㄩ厤缃被銆?
### `@EnableScheduling`

鍚敤瀹氭椂浠诲姟銆傛垜浠」鐩噷鏈?`JwtSchedulerConfig`锛屽畾鏈熸竻鐞?JWT 榛戝悕鍗曘€?
### `main` 鏂规硶

```java
DotenvConfig.load();
SpringApplication.run(EduProjectApplication.class, args);
```

绗竴琛岋細鍏堝姞杞?`.env` 鏂囦欢閲岀殑鐜鍙橀噺锛堟暟鎹簱瀵嗙爜銆丣WT 瀵嗛挜绛夛級锛岃繖鏄」鐩嚜宸卞啓鐨勫伐鍏枫€?
绗簩琛岋細鍚姩 Spring Boot锛孲pring 浼氭壂鎻忔墍鏈夌粍浠躲€佽繛鎺ユ暟鎹簱銆佸惎鍔?Tomcat銆?
鍚姩鎴愬姛鍚庢棩蹇椾細鎵撳嵃 API 鏂囨。鍦板潃銆?
## 4.4 application.yml 閰嶇疆鏂囦欢瑙ｈ

`src/main/resources/application.yml` 鏄?Spring Boot 涓婚厤缃枃浠躲€傛垜浠殑瀹為檯閰嶇疆锛堣妭閫夛級锛?
```yaml
spring:
  application:
    name: campus-blog-forum

  datasource:
    driver-class-name: com.mysql.cj.jdbc.Driver
    url: jdbc:mysql://${DB_HOST}:${DB_PORT}/${DB_NAME}?useUnicode=true&characterEncoding=utf-8&serverTimezone=Asia/Shanghai&useSSL=false
    username: ${DB_USERNAME}
    password: ${DB_PASSWORD}
    hikari:
      minimum-idle: 5
      maximum-pool-size: 20
      pool-name: CampusBlogHikariCP

mybatis-plus:
  mapper-locations: classpath*:/mapper/**/*.xml
  global-config:
    db-config:
      id-type: auto
      logic-delete-field: isDeleted
      logic-delete-value: 1
      logic-not-delete-value: 0

server:
  port: ${SERVER_PORT:8825}
  servlet:
    context-path: /api

jwt:
  secret: ${JWT_SECRET}
  expiration: ${JWT_EXPIRATION}
  refresh-expiration: ${JWT_REFRESH_EXPIRATION}
```

鍏抽敭鐐硅〃鏍硷細

| 閰嶇疆 | 鍚箟 |
| --- | --- |
| `spring.application.name` | 搴旂敤鍚嶇О |
| `spring.datasource.url` | 鏁版嵁搴撹繛鎺ュ湴鍧€ |
| `${DB_HOST}` | 寮曠敤鐜鍙橀噺锛堟潵鑷?.env 鏂囦欢锛?|
| `${SERVER_PORT:8825}` | 榛樿绔彛 8825锛屽彲琚幆澧冨彉閲忚鐩?|
| `server.servlet.context-path: /api` | 鎵€鏈夋帴鍙ｅ墠缂€鍔?/api |
| `mybatis-plus.global-config.db-config.logic-delete-field` | 閫昏緫鍒犻櫎瀛楁鍚?|
| `jwt.secret` | JWT 绛惧悕瀵嗛挜 |

鈿狅笍 娉ㄦ剰 YAML 鏍煎紡锛?
- 鐢?**绌烘牸** 缂╄繘锛岀粷瀵逛笉鑳界敤 Tab锛?- 鍐掑彿鍚庨潰瑕佹湁 **涓€涓┖鏍?*
- 鍚屼竴灞傜骇鐨勫瓧娈电缉杩涜涓€鑷?
### 涓轰粈涔堢敤鐜鍙橀噺锛?
鐩存帴鎶婃暟鎹簱瀵嗙爜鍐欏湪 yml 閲屾帹鍒?GitHub锛熼偅绛変簬鎶婂闂ㄩ挜鍖欐寕鍦ㄥぇ闂ㄤ笂锛佹垜浠敤 `${DB_PASSWORD}` 鍗犱綅绗︼紝鐪熷疄鍊兼斁鍦ㄦ湰鍦?`.env` 鏂囦欢閲岋紙宸插姞杩?`.gitignore`锛夈€?
`.env.example` 灏辨槸妯℃澘锛岃鍒汉 `cp .env.example .env` 鍚庡～鑷繁鐨勫€硷細

```bash
DB_HOST=IP
DB_PORT=3306
DB_NAME=campus_blog
DB_USERNAME=campus_blog
DB_PASSWORD=your_database_password_here
JWT_SECRET=your_jwt_secret_key_here_minimum_32_characters
JWT_EXPIRATION=86400000
JWT_REFRESH_EXPIRATION=604800000
SERVER_PORT=8825
```

鈿狅笍 JWT_SECRET 蹇呴』 **鑷冲皯 32 浣?*锛屽惁鍒?JJWT 浼氭嫆缁濈鍚嶃€?
## 4.5 绗竴涓?RestController 绀轰緥

璁╂垜浠啓涓€涓畝鍗曟帴鍙ｆ劅鍙?Spring Boot 鐨勯瓍鍔涳細

```java
package com.example.edu_project.controller;

import org.springframework.web.bind.annotation.GetMapping;
import org.springframework.web.bind.annotation.RequestParam;
import org.springframework.web.bind.annotation.RestController;

@RestController
public class HelloController {

    @GetMapping("/hello")
    public String hello(@RequestParam(defaultValue = "World") String name) {
        return "Hello, " + name + "! 娆㈣繋鏉ュ埌鏍″洯鍗氬璁哄潧 馃帀";
    }
}
```

浠ｇ爜瑙ｆ瀽锛?
| 娉ㄨВ/璇硶 | 浣滅敤 |
| --- | --- |
| `@RestController` | 鏍囪杩欐槸涓?REST 鎺у埗鍣紝鎵€鏈夋柟娉曡繑鍥炵殑鍐呭浼氱洿鎺ュ啓鍒?HTTP 鍝嶅簲浣擄紙JSON/瀛楃涓诧級|
| `@GetMapping("/hello")` | 鎶?HTTP GET 璇锋眰 `/hello` 鏄犲皠鍒拌繖涓柟娉?|
| `@RequestParam` | 浠?URL 涓彇鍙傛暟锛屾瘮濡?`?name=寮犱笁` |
| `defaultValue = "World"` | 娌′紶 name 鏃堕粯璁ょ敤 "World" |

鍚姩椤圭洰鍚庯紝娴忚鍣ㄨ闂細

```
http://localhost:8825/api/hello
http://localhost:8825/api/hello?name=鍒樼晠
```

娉ㄦ剰璺緞鏄?`/api/hello` 鑰屼笉鏄?`/hello`锛屽洜涓烘垜浠湪 yml 閲岃浜?`context-path: /api`銆?
## 4.6 椤圭洰杩愯锛歮vn spring-boot:run vs java -jar

涓ょ杩愯鏂瑰紡瀵规瘮锛?
| 鏂瑰紡 | 鍛戒护 | 閫傚悎鍦烘櫙 |
| --- | --- | --- |
| 寮€鍙戞湡杩愯 | `mvn spring-boot:run` 鎴?IDEA 鐩存帴 Run | 杈规敼浠ｇ爜杈硅窇 |
| 鎵撳寘鍚庤繍琛?| `mvn clean package` 鈫?`java -jar target/edu_project-0.0.1-SNAPSHOT.jar` | 閮ㄧ讲涓婄嚎 |

鎵撳寘鍚庣殑 jar 鏂囦欢鍙?**fat jar锛堣儢 jar锛?*锛岄噷闈㈠凡缁忔妸 Tomcat 閮芥墦杩涘幓浜嗭紝閮ㄧ讲鍒颁换浣曡浜?Java 21 鐨勬満鍣ㄤ笂閮借兘璺戯細

```bash
java -jar edu_project-0.0.1-SNAPSHOT.jar
```

鉁?杩欏氨鏄?Spring Boot 鏈€鐖界殑鐗规€э細**涓嶉渶瑕佸崟鐙 Tomcat**锛?
## 4.7 璁块棶鍦板潃 & Knife4j 鏂囨。

鍚姩鎴愬姛鍚庯紝浣犺兘璁块棶浠ヤ笅鍦板潃锛?
| 鍦板潃 | 鐢ㄩ€?|
| --- | --- |
| http://localhost:8825/api | 鎺ュ彛鏍瑰湴鍧€ |
| http://localhost:8825/api/doc.html | **Knife4j 鎺ュ彛鏂囨。锛堥噸鐐癸紒锛?* |
| http://localhost:8825/api/v3/api-docs | OpenAPI JSON 鍘熷鏁版嵁 |

### Knife4j 鏄粈涔?
Knife4j 鏄熀浜?Swagger 鐨勫寮虹増 API 鏂囨。宸ュ叿銆傛墦寮€ doc.html 浣犱細鐪嬪埌涓€涓秴婕備寒鐨勭綉椤碉細

- 宸︿晶鏄寜妯″潡鍒嗙粍鐨勬帴鍙ｅ垪琛紙鐢ㄦ埛銆佹枃绔犮€佽瘎璁衡€︼級
- 涓棿鏄帴鍙ｈ鎯咃細URL銆佸弬鏁般€佸搷搴?- 鍙充晶鍙互**鐩存帴鍦ㄧ嚎娴嬭瘯鎺ュ彛**锛屼笉闇€瑕?Postman

鈿狅笍 榛樿绠＄悊鍛樿处鍙锋槸 `admin` / `admin123`锛屽彲浠ョ櫥褰曞悗璇曠敤鎵€鏈夐渶瑕侀壌鏉冪殑鎺ュ彛銆?
### 椤圭洰缁撴瀯鍐嶅洖椤?
鑷虫浣犲簲璇ュ椤圭洰鏈夊畬鏁寸殑鐢婚潰鎰熶簡锛?
```
娴忚鍣ㄨ闂?http://localhost:8825/api/posts
   鈫?Tomcat 鎺ユ敹璇锋眰
   鈫?Spring 璺敱鍒?PostController
   鈫?PostController 璋?PostService
   鈫?PostService 璋?PostMapper
   鈫?MyBatis Plus 鐢熸垚 SQL锛岃闂?MySQL
   鈫?鏌ュ埌鏁版嵁 鈫?涓€璺繑鍥?鈫?搴忓垪鍖栨垚 JSON
   鈫?鍓嶇鎷垮埌缁撴灉鏄剧ず
```

杩欏氨鏄竴涓吀鍨嬬殑 Spring Boot RESTful 搴旂敤鐨勮姹傛祦绋嬨€?
---

## 绗竴閮ㄥ垎灏忕粨

馃帀 鎭枩浣犺瀹屼簡绗竴閮ㄥ垎锛佽鎴戜滑鍥為【涓€涓嬶細

1锔忊儯 **绗?1 绔?* 瀛︿簡 Java 璇█鍩虹锛氬彉閲忋€佹帶鍒舵祦銆佺被涓庡璞°€侀泦鍚堛€佸紓甯搞€佹敞瑙ｃ€佸寘
2锔忊儯 **绗?2 绔?* 瑁呭ソ浜嗗紑鍙戠幆澧冿細JDK 21銆両DEA銆丩ombok銆丮aven銆丮ySQL
3锔忊儯 **绗?3 绔?* 璁よ瘑浜?Maven 鍜屾垜浠」鐩殑鐩綍缁撴瀯
4锔忊儯 **绗?4 绔?* 绗竴娆℃帴瑙?Spring Boot锛氬惎鍔ㄧ被銆亂ml 閰嶇疆銆佸啓浜嗕竴涓?hello 鎺ュ彛

鍒拌繖閲屼綘搴旇鑳斤細

- 鐪嬫噦 Java 鍩烘湰璇硶
- 鎶婇」鐩窇璧锋潵
- 鍐欏嚭鏈€绠€鍗曠殑 GET 鎺ュ彛
- 鐪嬫噦椤圭洰鐨勬暣浣撴灦鏋?
鎺ヤ笅鏉ュ湪绗簩閮ㄥ垎锛屾垜浠細娣卞叆 Controller銆丼ervice銆丮apper 鐨勫啓娉曪紝寮€濮嬬湡姝ｅ姩鎵嬪紑鍙?鐢ㄦ埛娉ㄥ唽鐧诲綍"杩欐牱鐨勫疄闄呭姛鑳姐€?
璇蜂紤鎭竴涓嬶紝鍠濇澂姘达紝鍋氬嚑涓繁鍛煎惛锛岀劧鍚庢垜浠户缁?馃挭

> 璁颁綇寮€鍙戣崳鑰荤涓€鏉★細**浠ョ瀻娓呮帴鍙ｄ负鑰伙紝浠ヨ鐪熸煡璇负鑽ｃ€?*
> 鍐欎唬鐮佷笉鏄湪鐐妧锛屾槸鍦ㄨ鐪熻В鍐抽棶棰樸€傛參灏辨槸蹇€?
涓嬩竴閮ㄥ垎瑙侊紒

# 銆奐ava Spring Boot 闆跺熀纭€瀹屾暣瀛︿範鎵嬪唽銆?
## 绗簩閮ㄥ垎 妗嗘灦鏍稿績

> 妗堜緥椤圭洰锛氭牎鍥崥瀹㈣鍧涚郴缁燂紙Campus Blog锛?> 閫傚悎浜虹兢锛氬畬鍏ㄦ病鏈?Java Web 缁忛獙鐨勫垵瀛﹁€?> 鍐欎綔鍘熷垯锛氭瘡涓蹇甸兘鏈夋瘮鍠汇€佹瘡娈典唬鐮侀兘鏉ヨ嚜鐪熷疄椤圭洰

---

# 绗?5 绔?MyBatis Plus 鎸佷箙灞傛鏋?
## 5.1 ORM 鎬濇兂锛氱被鈫旇〃锛屽璞♀啍琛?
鍒氬紑濮嬫帴瑙?Java Web 鐨勬湅鍙嬶紝鏈€瀹规槗鍗′綇鐨勫湴鏂瑰氨鏄?鏁版嵁搴?SQL"鍜?Java 浠ｇ爜"涔嬮棿鐨勯缚娌熴€傛暟鎹簱閲屾湁涓€寮犺〃锛屾瘮濡?`sys_user`锛屽畠鏈?`id`銆乣username`銆乣password` 杩欎簺鍒椼€侸ava 绋嬪簭閲屾湁涓€涓被锛屾瘮濡?`SysUser`锛屽畠鏈?`id`銆乣username`銆乣password` 杩欎簺瀛楁銆傚畠浠湅璧锋潵鏄竴鍥炰簨锛屼絾搴曞眰瀹屽叏涓嶅悓锛氫竴涓槸鍏崇郴鍨嬫暟鎹簱鐨勪簩缁磋〃锛屼竴涓槸 JVM 鍐呭瓨閲岀殑瀵硅薄銆?
ORM锛圤bject-Relational Mapping锛屽璞″叧绯绘槧灏勶級灏辨槸鎶婅繖涓や釜涓栫晫杩炶捣鏉ョ殑"缈昏瘧瀹?銆傚畠鐨勬牳蹇冩€濇兂鍙互鐢ㄤ竴涓瘮鍠绘潵鐞嗚В锛?
> 鎶婃暟鎹簱琛ㄦ兂璞℃垚涓€涓?Excel 琛ㄦ牸銆?> 琛ㄧ殑"琛ㄥご"锛堝垪鍚嶏級= Java 绫婚噷鐨?瀛楁鍚?銆?> 琛ㄧ殑"姣忎竴琛?= Java 閲岀殑"涓€涓璞?銆?> 浣犲湪 Java 閲?`new SysUser()`锛屽氨濂芥瘮鍦?Excel 閲屾柊澧炰竴琛岋紱浣犵粰瀵硅薄鐨勫瓧娈佃祴鍊硷紝灏卞ソ姣斿線鍗曞厓鏍奸噷濉暟鎹紱鏈€鍚庝綘淇濆瓨瀵硅薄鍒版暟鎹簱锛屽氨濂芥瘮鎶婅繖涓€琛屽啓鍒?Excel 閲屻€?
鏈変簡 ORM锛屼綘灏变笉鐢ㄤ竴鐩存墜鍐?`INSERT INTO sys_user (username, password) VALUES (?, ?)` 杩欑 SQL 浜嗐€傛鏋朵細鏇夸綘鎷?SQL銆佹墽琛屻€佹妸缁撴灉闆嗘槧灏勫洖 Java 瀵硅薄銆?
ORM 鐨勪笁缁勫搴斿叧绯讳竴瀹氳鐗㈣锛?
| 鏁版嵁搴撲笘鐣?| Java 涓栫晫 |
|------------|-----------|
| 琛紙table锛?| 绫伙紙class锛?|
| 琛岋紙row锛?| 瀵硅薄锛坥bject锛?|
| 鍒楋紙column锛?| 瀛楁锛坒ield锛?|

## 5.2 MyBatis 涓?MyBatis Plus 鐨勫尯鍒?
MyBatis 鏄浗鍐呮渶娴佽鐨?ORM 妗嗘灦涔嬩竴锛岀壒鐐规槸"鍗婅嚜鍔?锛氫綘鍐?SQL锛屽畠甯綘鏄犲皠缁撴灉銆備絾鍗充究鏄畝鍗曠殑 CRUD锛堝鍒犳敼鏌ワ級锛屼篃寰楀啓涓€鍫?XML 鎴栨敞瑙?SQL锛岄噸澶嶄笖鏋嚗銆?
MyBatis Plus锛堢畝绉?MP锛夋槸鍦?MyBatis 涔嬩笂鍋氱殑"澧炲己宸ュ叿"锛岀壒鐐规槸"鍏ㄨ嚜鍔?+ 鍙墿灞?锛?
- 绠€鍗曠殑 CRUD锛堟寜 ID 鏌ャ€佹柊澧炪€佹洿鏂般€佸垹闄ゃ€佸垎椤碉級锛氬畬鍏ㄤ笉鐢ㄥ啓 SQL锛屾鏋惰嚜鍔ㄧ敓鎴愩€?- 澶嶆潅鐨勪笟鍔?SQL锛氫綘鐓ф牱鍙互鐢?MyBatis 鐨?`@Select`銆乆ML 鍐欒嚜瀹氫箟 SQL锛屼袱绉嶆柟寮忔棤缂濆叡瀛樸€?
褰㈣薄姣斿柣锛歁yBatis 鍍忎竴鍙版墜鍔ㄦ尅姹借溅锛屾墍鏈夋尅浣嶉兘寰楄嚜宸辨崲锛汳yBatis Plus 鍒欏儚鑷姩鎸★紝鏅€氳矾鍐佃嚜鍔ㄦ搷浣滐紝閬囧埌灞辫矾浣犲彲浠ュ垏鎵嬪姩妯″紡銆?
鏈」鐩殑 `pom.xml` 閲屽紩鍏ョ殑灏辨槸 MyBatis Plus 3.5.5锛屾暣涓」鐩嚑涔庢墍鏈夌畝鍗?CRUD 閮芥病鏈夊啓涓€琛?SQL锛屽叏闈犳鏋剁敓鎴愩€?
## 5.3 瀹炰綋绫荤殑鍏抽敭娉ㄨВ锛堝熀浜庣湡瀹炰唬鐮侊級

瀹炰綋绫伙紙Entity锛夋槸 ORM 閲?琛?鐨?Java 鍖栬韩銆傛垜浠互鏈」鐩殑 `SysUser.java` 涓轰緥锛堣矾寰勶細`src/main/java/com/example/edu_project/entity/SysUser.java`锛夛細

```java
@Data
@TableName("sys_user")
public class SysUser implements Serializable {

    @TableId(type = IdType.AUTO)
    private Long id;

    private String username;

    @JsonIgnore
    private String password;

    private String nickname;
    private String avatar;
    private String email;
    private String role;
    private Integer status;

    @TableField(fill = FieldFill.INSERT)
    private Integer loginFailCount;

    private LocalDateTime lockUntil;

    @TableField(fill = FieldFill.INSERT)
    private LocalDateTime createTime;

    @TableField(fill = FieldFill.INSERT_UPDATE)
    private LocalDateTime updateTime;

    @TableLogic
    private Integer isDeleted;
}
```

杩欓噷鍑虹幇鐨勬敞瑙ｏ紝鏄綘浠婂悗姣忓啓涓€涓疄浣撶被閮戒細鐢ㄥ埌鐨?鍥涘ぇ閲戝垰"锛?
### `@TableName("sys_user")`

鍛婅瘔 MyBatis Plus锛?杩欎釜 Java 绫诲搴旀暟鎹簱閲岀殑 `sys_user` 琛?銆傚鏋滀綘鎶婅〃鍚嶅啓鎴愯泧褰紙灏忓啓涓嬪垝绾匡級锛岀被鍚嶅啓鎴愬笗鏂崱锛堝ぇ鍐欓┘宄帮級锛孧P 涔熻兘榛樿鎺ㄦ柇锛坄SysUser` 鈫?`sys_user`锛夛紝浣嗘樉寮忓啓鍑烘潵鏇存竻鏅般€佹洿瀹夊叏銆?
### `@TableId(type = IdType.AUTO)`

澹版槑杩欎釜瀛楁鏄暟鎹簱鐨勪富閿紝骞舵寚瀹氫富閿瓥鐣ワ細

- `IdType.AUTO`锛氫氦缁欐暟鎹簱鑷锛圡ySQL 鐨?`AUTO_INCREMENT`锛夈€?- `IdType.ASSIGN_ID`锛歁P 鐢ㄩ洩鑺辩畻娉曠敓鎴愬叏灞€鍞竴 ID锛堝垎甯冨紡鍦烘櫙锛夈€?- `IdType.INPUT`锛氱敤鎴疯嚜宸变紶鍏ャ€?
鏈」鐩?`SysUser` 鐢ㄧ殑鏄?`AUTO`锛岀畝鍗曠洿鎺ワ紝渚濊禆 MySQL 鐨勮嚜澧炶兘鍔涖€?
### `@TableField`

鎺у埗瀛楁鐨勭粏鑺傝涓恒€傛渶甯哥敤鐨勪袱涓敤娉曪細

1. **鎸囧畾鍒楀悕**锛氬綋 Java 瀛楁鍚嶅拰鏁版嵁搴撳垪鍚嶄笉涓€鑷存椂锛堟瘮濡?`userName` 瀵瑰簲 `user_name`锛夛紝鍙互鍐?`@TableField("user_name")`銆侻P 榛樿浼氭妸椹煎嘲杞笅鍒掔嚎锛屾墍浠ュぇ閮ㄥ垎鏃跺€欎笉鐢ㄥ啓銆?2. **鑷姩濉厖**锛歚@TableField(fill = FieldFill.INSERT)` 琛ㄧず鎻掑叆鏃舵鏋惰嚜鍔ㄥ～鍊硷紱`FieldFill.INSERT_UPDATE` 琛ㄧず鎻掑叆鍜屾洿鏂版椂閮借嚜鍔ㄥ～鍊笺€傝繖璺?5.5 鑺傜殑 `MyMetaObjectHandler` 閰嶅悎宸ヤ綔銆?
### `@TableLogic`

閫昏緫鍒犻櫎鏍囪銆傛湰椤圭洰閲?`isDeleted` 瀛楁鍔犱簡杩欎釜娉ㄨВ鍚庯紝璋冪敤 `mapper.deleteById(1L)` 鏃讹紝MP 涓嶄細鐪熺殑鎵ц `DELETE`锛岃€屾槸浼氭墽琛?`UPDATE sys_user SET is_deleted = 1 WHERE id = 1`銆備粠姝や互鍚庢墍鏈夋煡璇細鑷姩鍔犱笂 `WHERE is_deleted = 0`锛岃"鍒犻櫎"鐨勬暟鎹涓氬姟灞傞潰闅愬舰锛屼絾瀹為檯浠嶇劧瀛樺湪浜庢暟鎹簱銆?
鈿狅笍 杩欐槸浼佷笟绾у紑鍙戠殑鏍囬厤銆傜墿鐞嗗垹闄ょ殑鏁版嵁鎵句笉鍥炴潵锛岄€昏緫鍒犻櫎闅忔椂鍙互鎭㈠銆傛湰椤圭洰鏈€杩戜竴娆″畨鍏ㄥ崌绾э紙v1.28锛夊氨鏄妸鎵€鏈夌墿鐞嗗垹闄ゆ敼鎴愪簡閫昏緫鍒犻櫎銆?
### `@JsonIgnore`

铏界劧杩欐槸 Jackson 鐨勬敞瑙ｏ紙涓嶆槸 MP 鐨勶級锛屼絾寰堝叧閿€俙SysUser` 鐨?`password` 瀛楁鍔犱簡 `@JsonIgnore`锛屾剰鎬濇槸"搴忓垪鍖栦负 JSON 鏃惰烦杩囪繖涓瓧娈?銆傝繖鏍峰嵆浣夸綘涓嶅皬蹇冩妸 `SysUser` 鐩存帴杩斿洖缁欏墠绔紝瀵嗘枃瀵嗙爜涔熶笉浼氭硠闇层€傚畨鍏ㄧ涓€銆?
### `@Data`锛圠ombok锛?
Lombok 鐨?`@Data` 鑷姩鐢熸垚 Getter銆丼etter銆乣toString`銆乣equals`銆乣hashCode`銆傚鏋滄病鏈夊畠锛屼竴涓湁 14 涓瓧娈电殑 `SysUser` 绫昏鍐欏嚑鐧捐鏍锋澘浠ｇ爜銆?
鎴戜滑鍐嶅揩閫熺湅涓€涓?`BlogPost.java`锛岀粨鏋勯潪甯哥被浼硷細

```java
@Data
@TableName("blog_post")
public class BlogPost implements Serializable {
    @TableId(type = IdType.AUTO)
    private Long id;
    private Long userId;
    private String title;
    private String content;
    private Integer viewCount;
    private Integer likeCount;
    @TableField(fill = FieldFill.INSERT)
    private LocalDateTime createTime;
    @TableField(fill = FieldFill.INSERT_UPDATE)
    private LocalDateTime updateTime;
    @TableLogic
    private Integer isDeleted;
}
```

娉ㄦ剰鍒?`viewCount`銆乣likeCount` 绛夐兘鏄櫘閫氬瓧娈碉紝瀵瑰簲鏁版嵁搴撶殑 `view_count`銆乣like_count`銆侻P 榛樿浼氭妸椹煎嘲杞笅鍒掔嚎鍖归厤銆?
## 5.4 BaseMapper 鍐呯疆鏂规硶

鍐欏ソ瀹炰綋绫诲悗锛屼笅涓€姝ュ氨鏄?Mapper 鎺ュ彛銆傜湅鏈」鐩殑 `SysUserMapper.java`锛?
```java
@Mapper
public interface SysUserMapper extends BaseMapper<SysUser> {
    // 鑷畾涔?SQL 鏂规硶...
}
```

`@Mapper` 鍛婅瘔 MyBatis 杩欐槸涓€涓?Mapper 鎺ュ彛锛岄渶瑕佽鎵弿锛沗extends BaseMapper<SysUser>` 涓€鍙ヨ瘽灏辫浣?鐧藉珫"浜嗘墍鏈?CRUD 鏂规硶銆侭aseMapper 閲屽埌搴曟湁鍝簺鏂规硶锛熷父鐢ㄧ殑鏈夛細

| 鏂规硶 | 浣滅敤 |
|------|------|
| `insert(T entity)` | 鏂板涓€鏉¤褰?|
| `deleteById(Serializable id)` | 鎸変富閿垹闄わ紙瀹為檯鏄€昏緫鍒犻櫎锛?|
| `updateById(T entity)` | 鎸変富閿洿鏂?|
| `selectById(Serializable id)` | 鎸変富閿煡璇?|
| `selectList(Wrapper<T>)` | 鎸夋潯浠舵煡璇㈠鏉?|
| `selectOne(Wrapper<T>)` | 鎸夋潯浠舵煡璇竴鏉?|
| `selectCount(Wrapper<T>)` | 鎸夋潯浠剁粺璁¤鏁?|
| `selectPage(IPage<T>, Wrapper<T>)` | 鍒嗛〉鏌ヨ |

鈿狅笍 鐪嬫竻妤氾細浣犲彧鏄啓浜嗕竴涓户鎵?`BaseMapper` 鐨?*绌烘帴鍙?*锛屽氨鎷ユ湁浜嗕笂闈㈡墍鏈夋柟娉曪紒杩欏氨鏄?MP 璁╀汉鐖变笉閲婃墜鐨勫湴鏂广€?
## 5.5 鑷姩濉厖鏈哄埗

鏂板鍜屾洿鏂版暟鎹椂锛屾瘡娆￠兘瑕佹墜鍔?`setCreateTime(LocalDateTime.now())`銆乣setUpdateTime(LocalDateTime.now())` 鍚楋紵澶疮銆侻P 鎻愪緵浜?鑷姩濉厖"鏈哄埗锛屾湰椤圭洰閲岄€氳繃 `MyMetaObjectHandler.java` 瀹炵幇锛?
```java
@Slf4j
@Component
public class MyMetaObjectHandler implements MetaObjectHandler {

    @Override
    public void insertFill(MetaObject metaObject) {
        log.info("寮€濮嬫彃鍏ュ～鍏?..");
        this.strictInsertFill(metaObject, "createTime", LocalDateTime::now, LocalDateTime.class);
        this.strictInsertFill(metaObject, "updateTime", LocalDateTime::now, LocalDateTime.class);
    }

    @Override
    public void updateFill(MetaObject metaObject) {
        log.info("寮€濮嬫洿鏂板～鍏?..");
        this.strictUpdateFill(metaObject, "updateTime", LocalDateTime::now, LocalDateTime.class);
    }
}
```

瀹冪殑宸ヤ綔鍘熺悊锛?
1. 浠讳綍瀹炰綋绫荤殑瀛楁鍔犱笂 `@TableField(fill = FieldFill.INSERT)`锛屾柊澧炴椂妗嗘灦浼氳Е鍙?`insertFill` 鏂规硶銆?2. 浠讳綍瀛楁鍔犱笂 `@TableField(fill = FieldFill.INSERT_UPDATE)`锛屾柊澧炲拰鏇存柊鏃堕兘浼氳Е鍙?`updateFill` 鏂规硶銆?3. `strictInsertFill` 鏄?涓ユ牸妯″紡"锛屽彧鍦ㄥ瓧娈典负 `null` 鏃舵墠濉紝宸茬粡鏈夊€煎垯涓嶈鐩栥€?4. `LocalDateTime::now` 鏄?Java 鐨勬柟娉曞紩鐢紝绛変环浜?`() -> LocalDateTime.now()`銆?
鏁堟灉灏辨槸锛氫綘 service 灞傚啓 `userService.save(user)` 鏃舵牴鏈笉鐢ㄧ鏃堕棿锛孧P 浼氳嚜鍔ㄧ粰 `createTime` 鍜?`updateTime` 濉炲€笺€?
## 5.6 閫昏緫鍒犻櫎锛歚@TableLogic` + `isDeleted`

鍓嶉潰宸茬粡鎻愯繃锛岃繖閲屽啀娣卞叆涓€鐐广€傛湰椤圭洰鎵€鏈変笟鍔¤〃閮芥湁 `isDeleted` 瀛楁锛坄0=姝ｅ父锛?=宸插垹闄锛夛紝鍔犱簡 `@TableLogic`銆傚畠鐨勫ソ澶勶細

- 璇垹鍙仮澶嶏細鎶?`is_deleted` 鏀瑰洖 `0` 鍗冲彲銆?- 鍘嗗彶鍙拷婧細鍒犻櫎鐨勬暟鎹粛鍦ㄨ〃閲岋紝鍙敤浜庡璁°€?- 杞垹 + 鍏宠仈琛ㄤ繚鎶わ細閬垮厤澶栭敭绾ц仈鍒犻櫎甯︽潵鐨勪笉鍙帶褰卞搷銆?
`application.yml` 閲岄€氬父浼氭湁鍏ㄥ眬閰嶇疆锛?
```yaml
mybatis-plus:
  global-config:
    db-config:
      logic-delete-field: isDeleted   # 鍏ㄥ眬閫昏緫鍒犻櫎瀛楁
      logic-delete-value: 1           # 宸插垹闄ゅ€?      logic-not-delete-value: 0       # 鏈垹闄ゅ€?```

杩欐牱鍚庣画灏辩畻涓嶅湪姣忎釜瀹炰綋绫讳笂鍐?`@TableLogic`锛屽彧瑕佸瓧娈靛悕鍙?`isDeleted`锛屼篃浼氳嚜鍔ㄧ敓鏁堛€?
## 5.7 鍒嗛〉鎻掍欢锛堝熀浜?`MybatisPlusConfig.java`锛?
MP 榛樿娌″紑鍚垎椤碉紝闇€瑕佹墜鍔ㄦ敞鍐屼竴涓垎椤垫嫤鎴櫒銆傛湰椤圭洰鐨勯厤缃被锛?
```java
@Configuration
@MapperScan("com.example.edu_project.mapper")
public class MybatisPlusConfig {

    @Bean
    public MybatisPlusInterceptor mybatisPlusInterceptor() {
        MybatisPlusInterceptor interceptor = new MybatisPlusInterceptor();
        interceptor.addInnerInterceptor(new PaginationInnerInterceptor(DbType.MYSQL));
        return interceptor;
    }
}
```

涓や釜鍏抽敭鐐癸細

1. `@MapperScan("com.example.edu_project.mapper")`锛氬憡璇?Spring 鎵弿杩欎釜鍖呬笅鎵€鏈?Mapper 鎺ュ彛锛岃嚜鍔ㄧ敓鎴愪唬鐞嗗疄鐜般€?2. `PaginationInnerInterceptor(DbType.MYSQL)`锛氫负 MySQL 娉ㄥ叆鍒嗛〉 SQL 鏀瑰啓鑳藉姏銆?
鍚敤鍚庝綘灏辫兘杩欐牱鍐欙細

```java
Page<SysUser> page = new Page<>(1, 10); // 绗?1 椤碉紝姣忛〉 10 鏉?IPage<SysUser> result = userMapper.selectPage(page, wrapper);
result.getRecords();    // 褰撳墠椤垫暟鎹?result.getTotal();      // 鎬昏褰曟暟
result.getPages();      // 鎬婚〉鏁?```

搴曞眰 SQL 妗嗘灦浼氳嚜鍔ㄧ粰浣犳嫾鎴愶細`SELECT ... FROM sys_user ... LIMIT 0, 10`锛屽苟棰濆鎵ц `SELECT count(*) ...` 姹傛€绘暟銆?
鏈」鐩?`SysUserServiceImpl.searchUsers` 鏂规硶灏辨槸杩欐牱鐢ㄧ殑锛?
```java
Page<SysUser> page = new Page<>(request.getPage(), request.getPageSize());
LambdaQueryWrapper<SysUser> wrapper = new LambdaQueryWrapper<>();
if (request.getKeyword() != null && !request.getKeyword().trim().isEmpty()) {
    String keyword = request.getKeyword().trim();
    wrapper.and(w -> w.like(SysUser::getUsername, keyword)
            .or()
            .like(SysUser::getNickname, keyword));
}
wrapper.orderByDesc(SysUser::getCreateTime);
IPage<SysUser> userPage = this.page(page, wrapper);
```

## 5.8 LambdaQueryWrapper 鏉′欢鏋勯€犲櫒

`Wrapper` 鏄?MP 鐢ㄦ潵鏋勯€?WHERE 鏉′欢鐨勫伐鍏凤紝鐩稿綋浜?鐢?Java 鍐?SQL 鐨?WHERE 閮ㄥ垎"銆傛渶鎺ㄨ崘鐨勭増鏈槸 `LambdaQueryWrapper`锛屽洜涓哄畠鐢ㄦ柟娉曞紩鐢?`SysUser::getUsername` 浠ｆ浛瀛楃涓?`"username"`锛岀紪璇戞湡鑳芥鏌ュ瓧娈靛悕鎷煎啓閿欒銆?
甯歌 API锛?
| 鏂规硶 | 绛変环 SQL |
|------|----------|
| `eq(SysUser::getUsername, "鍒樼晠")` | `username = '鍒樼晠'` |
| `ne(...)` | `<>` |
| `gt / ge / lt / le` | `> / >= / < / <=` |
| `like(...)` | `LIKE '%xxx%'` |
| `in(...)` | `IN (...)` |
| `between(...)` | `BETWEEN a AND b` |
| `orderByDesc(...)` | `ORDER BY xxx DESC` |
| `and(w -> ...)` | `AND (...)` 宓屽鏉′欢 |

鍦ㄦ湰椤圭洰鐧诲綍鎺ュ彛閲屽氨鏈夊吀鍨嬬敤娉曪細

```java
LambdaQueryWrapper<SysUser> wrapper = new LambdaQueryWrapper<>();
wrapper.eq(SysUser::getUsername, request.getUsername());
SysUser user = this.getOne(wrapper);
```

## 5.9 鑷畾涔?SQL锛歚@Update` 娉ㄨВ鎴?XML

绠€鍗?CRUD 鐢?BaseMapper 灏卞浜嗭紝浣嗘湁浜涘満鏅渶瑕?鍘熷瓙鎿嶄綔"锛屾瘮濡傦細

- 璁℃暟鍣ㄨ嚜澧烇細`UPDATE sys_user SET follower_count = follower_count + 1 WHERE id = ?`
- 澶嶆潅鏉′欢鏇存柊

鏈」鐩殑 `SysUserMapper` 灏辨湁澶ч噺杩欐牱鐨勬敞瑙?SQL锛?
```java
@Update("UPDATE sys_user SET login_fail_count = login_fail_count + 1, " +
        "lock_until = CASE WHEN login_fail_count + 1 >= #{maxFailCount} " +
        "THEN DATE_ADD(NOW(), INTERVAL #{lockMinutes} MINUTE) ELSE lock_until END " +
        "WHERE id = #{userId} AND (lock_until IS NULL OR lock_until <= NOW())")
int incrementLoginFailCount(@Param("userId") Long userId,
                             @Param("maxFailCount") int maxFailCount,
                             @Param("lockMinutes") int lockMinutes);

@Update("UPDATE sys_user SET follower_count = follower_count + 1 WHERE id = #{userId}")
int incrementFollowerCount(@Param("userId") Long userId);
```

`#{xxx}` 鏄?MyBatis 鐨勫崰浣嶇锛屼細鑷姩 PreparedStatement 鍖栵紝闃叉 SQL 娉ㄥ叆銆俙@Param` 缁欏弬鏁板懡鍚嶄互渚?SQL 閲屽紩鐢ㄣ€?
鈿狅笍 杩欎簺鑷 SQL 鍦ㄦ暟鎹簱灞傚氨淇濊瘉浜嗗師瀛愭€э紝涓嶄細鍑虹幇"100 涓汉鍚屾椂鐐硅禐锛岀粨鏋滆鏁板櫒鍙?+1"鐨勫苟鍙?Bug銆傝繖鏄?*鏁版嵁搴撳眰鐨勫苟鍙戝畨鍏?*锛屾瘮 Java 灞傜殑閿佹洿鍙潬銆?
### 涓€鍙ヨ瘽鎬荤粨
> MyBatis Plus 鎶?瀵硅薄"鍜?琛?鑷姩缁戝畾锛岀畝鍗?CRUD 涓€琛?SQL 涓嶇敤鍐欙紝澶嶆潅 SQL 鍙堣兘闅忔椂鎵嬪啓锛屾槸 Java Web 寮€鍙戠殑鏍囬厤銆?
---

# 绗?6 绔?鍒嗗眰鏋舵瀯璇﹁В

## 6.1 涓轰粈涔堣鍒嗗眰锛堥キ搴楁瘮鍠伙級

鎯宠薄浣犲幓楗簵鍚冮キ锛?
- **鏈嶅姟鍛橈紙Controller锛?*锛氭帴浣犵殑鑿滃崟璁㈠崟锛屽憡璇夊帹鎴胯鍋氫粈涔堬紝鏈€鍚庢妸鑿滅缁欎綘銆備粬涓嶄細鍋氳彍锛屽彧璐熻矗娌熼€氥€?- **鍘ㄥ笀锛圫ervice锛?*锛氱湡姝ｇ倰鑿滅殑浜恒€備粬浼氭牴鎹彍鍗曞喅瀹氬厛鍒囪彍杩樻槸鍏堝紑鐏紝鎶?鍋氳彍"鐨勫鏉傞€昏緫灏佽璧锋潵銆?- **閲囪喘鍛橈紙Mapper锛?*锛氬幓浠撳簱鍙栧師鏂欍€佹妸鍘熸枡甯﹀洖鍘ㄦ埧銆備粬涓嶅叧蹇冩€庝箞鐑归オ锛屽彧绠?浠庢暟鎹簱鎷挎暟鎹?銆?- **椋熸潗锛圗ntity锛?*锛氭憜鍦ㄤ粨搴撻噷鐨勭墰鑲夈€侀潚鑿滐紝瀵瑰簲鏁版嵁搴撹〃閲岀殑涓€琛屻€?
濡傛灉璁╀竴涓汉鍚屾椂骞茶繖涓変欢浜嬶紝浼氫贡濂楋細鏈嶅姟鍛樹竴杈硅鍗曚竴杈瑰垏鑿滀竴杈规惉钄彍銆傛墍浠ヤ紒涓氱骇椤圭洰閮藉己鍒跺垎灞傦紝姣忎竴灞傚彧鍋氳嚜宸辩殑浜嬶紝渚夸簬缁存姢銆佷究浜庢祴璇曘€佷究浜庡洟闃熷崗浣溿€?
Spring Boot 椤圭洰鐨勬爣鍑嗗垎灞傦細

```
娴忚鍣?/ 鍓嶇
    鈫?HTTP
Controller锛堟帶鍒跺櫒锛? 鈫?鎺ヨ姹傘€佽繑鍝嶅簲
    鈫?Java 璋冪敤
Service锛堜笟鍔″眰锛?    鈫?涓氬姟瑙勫垯銆佷簨鍔?    鈫?Java 璋冪敤
Mapper锛堟寔涔呭眰锛?     鈫?SQL銆佷笌鏁版嵁搴撲氦浜?    鈫?JDBC
MySQL
```

## 6.2 Controller 灞傦紙鍩轰簬鐪熷疄 `SysUserController.java`锛?
Controller 鏄?鎺ュ緟澶у巺"銆傜湅鐪嬫湰椤圭洰鐨勬敞鍐屾帴鍙ｉ暱浠€涔堟牱锛?
```java
@Tag(name = "鐢ㄦ埛绠＄悊", description = "鐢ㄦ埛鐩稿叧鎺ュ彛")
@RestController
@RequestMapping("/user")
public class SysUserController {

    @Autowired
    private SysUserService sysUserService;

    @Operation(summary = "鐢ㄦ埛娉ㄥ唽")
    @PostMapping("/register")
    public Result<UserRegisterResponse> register(@Valid @RequestBody UserRegisterRequest request) {
        UserRegisterResponse response = sysUserService.register(request);
        return Result.success(response);
    }
}
```

閫愯瑙ｈ锛?
- `@RestController`锛氱瓑浜?`@Controller + @ResponseBody`锛屾剰鎬濇槸杩欎釜绫荤殑鎵€鏈夋柟娉曠洿鎺ヨ繑鍥?JSON锛屼笉璧拌鍥炬ā鏉裤€?- `@RequestMapping("/user")`锛氳繖涓被涓嬬殑鎵€鏈夋帴鍙ｉ兘浠?`/user` 寮€澶淬€?- `@PostMapping("/register")`锛氬畬鏁磋矾寰勫氨鏄?`POST /user/register`銆?- `@RequestBody`锛氭妸璇锋眰浣撶殑 JSON 鍙嶅簭鍒楀寲涓?`UserRegisterRequest` 瀵硅薄銆?- `@Valid`锛氳Е鍙戝弬鏁版牎楠岋紙璇﹁ 7.5 鑺傦級銆?- `@Autowired`锛氭妸 `SysUserService` 杩欎釜 Bean 鑷姩娉ㄥ叆杩涙潵锛堣瑙?6.6 鑺傦級銆?- `Result.success(response)`锛氭妸涓氬姟缁撴灉鍖呮垚缁熶竴鍝嶅簲鏍煎紡锛堣瑙佺 7 绔狅級銆?
鈿狅笍 鎺у埗鍣ㄩ噷涓嶈鍐欎笟鍔￠€昏緫锛屽彧鍋氫笁浠朵簨锛?*鎺ュ弬 鈫?璋?service 鈫?杩旂粨鏋?*銆?
## 6.3 Service 灞傦紙鎺ュ彛 + 瀹炵幇绫伙級

Service 灞傛槸"鍘ㄦ埧"锛屾槸涓氬姟瑙勫垯鐨勬牳蹇冦€傛湰椤圭洰鐢?**鎺ュ彛 + 瀹炵幇绫?* 鐨勬柟寮忓垎绂伙細

鎺ュ彛 `SysUserService.java`锛?
```java
public interface SysUserService extends IService<SysUser> {
    UserRegisterResponse register(UserRegisterRequest request);
    UserLoginResponse login(UserLoginRequest request);
    SysUser getUserById(Long id);
    void changePassword(Long userId, String oldPassword, String newPassword);
    IPage<UserVO> searchUsers(UserSearchRequest request);
}
```

瀹炵幇绫?`SysUserServiceImpl.java`锛?
```java
@Slf4j
@Service
public class SysUserServiceImpl extends ServiceImpl<SysUserMapper, SysUser>
        implements SysUserService {

    @Override
    @Transactional(rollbackFor = Exception.class)
    public UserRegisterResponse register(UserRegisterRequest request) {
        // ... 涓€鍫嗕笟鍔￠€昏緫
    }
}
```

涓轰粈涔堣"鎺ュ彛 + 瀹炵幇"锛?
1. **瑙ｈ€?*锛欳ontroller 渚濊禆鎺ュ彛鑰屼笉鏄叿浣撳疄鐜帮紝灏嗘潵鎯虫崲瀹炵幇锛堟瘮濡傚鎺ュ叾浠栨暟鎹簮锛夊彧闇€鏂板啓涓€涓疄鐜扮被銆?2. **AOP 鍙嬪ソ**锛歋pring 鐨勪簨鍔°€佹棩蹇椼€佺紦瀛樹唬鐞嗛渶瑕佹帴鍙ｆ墠鑳界敤 JDK 鍔ㄦ€佷唬鐞嗐€?3. **鏄撴祴璇?*锛氬啓鍗曞厓娴嬭瘯鏃跺彲浠ユ柟渚垮湴 Mock 鎺ュ彛銆?
娉ㄦ剰鍑犱釜鍏抽敭鐐癸細

- `extends ServiceImpl<SysUserMapper, SysUser>`锛歁P 鎻愪緵鐨勯€氱敤 Service 瀹炵幇锛岃浣犲湪 service 閲岀洿鎺ョ敤 `this.save()`銆乣this.getById()` 绛夋柟娉曪紝鍏嶅幓鍐?`userMapper.insert()` 鐨勯夯鐑︺€?- `@Service`锛氬憡璇?Spring "鎴戞槸涓€涓?service Bean锛岃绠＄悊鎴?銆?- `@Transactional(rollbackFor = Exception.class)`锛氭墍鏈夊啓鎿嶄綔閮藉姞浜嬪姟锛岄亣鍒板紓甯歌嚜鍔ㄥ洖婊氾紝淇濊瘉鏁版嵁涓€鑷存€с€?- `@Transactional(readOnly = true)`锛氬彧璇讳簨鍔″彲浠ヨ鏁版嵁搴撳仛浼樺寲锛堟瘮濡傚彧璇诲壇鏈矾鐢憋級锛屾湰椤圭洰 `getUserById`銆乣searchUsers` 閮藉姞浜嗐€?
## 6.4 Mapper 灞?
Mapper 灞傛槸"閲囪喘鍛?锛屽彧鍋氫竴浠朵簨锛?*鍜屾暟鎹簱璇磋瘽**銆傜湅鏈」鐩殑 `SysUserMapper`锛?
```java
@Mapper
public interface SysUserMapper extends BaseMapper<SysUser> {
    @Update("UPDATE sys_user SET login_fail_count = login_fail_count + 1, ... ")
    int incrementLoginFailCount(@Param("userId") Long userId,
                                 @Param("maxFailCount") int maxFailCount,
                                 @Param("lockMinutes") int lockMinutes);
}
```

瀹冨氨鏄竴涓帴鍙ｏ紝娌℃湁鏂规硶浣撱€傜畝鍗?CRUD 鐢?BaseMapper 鎻愪緵锛屽鏉?SQL 鐢ㄦ敞瑙ｆ垨 XML銆傛鏋跺惎鍔ㄦ椂浼氱敤鍔ㄦ€佷唬鐞嗙敓鎴愬疄鐜扮被銆?
鈿狅笍 Service 灞傚彲浠ヨ皟 Mapper锛屼絾 Controller 灞傜姝㈢洿鎺ヨ皟 Mapper锛佸惁鍒欏氨鐮村潖浜嗗垎灞傛灦鏋勩€?
## 6.5 Entity / DTO / VO 鍖哄埆

杩欎笁涓笢瑗跨湅璧锋潵閮芥槸"瑁呮暟鎹殑鐩掑瓙"锛屼絾鐢ㄩ€斿畬鍏ㄤ笉鍚屻€傛湰椤圭洰閲岄潪甯告竻鏅帮細

| 绫诲瀷 | 鍏ㄧО | 鐢ㄩ€?| 渚嬪瓙 |
|------|------|------|------|
| Entity | 瀹炰綋绫?| 瀵瑰簲鏁版嵁搴撹〃锛岀粰 Mapper 鐢?| `SysUser` |
| DTO | Data Transfer Object | 鎺ユ敹鍓嶇璇锋眰鍙傛暟 | `UserRegisterRequest` |
| VO | View Object | 缁欏墠绔繑鍥炵殑灞曠ず瀵硅薄 | `UserVO`銆乣UserLoginResponse` |

涓轰粈涔堣鍒嗭紵鐪嬩竴涓緥瀛愩€?
鏁版嵁搴撹〃 `sys_user` 鏈?`password`銆乣isDeleted`銆乣lockUntil` 杩欎簺鏁忔劅/鏃犲叧瀛楁銆?
- 娉ㄥ唽鏃讹紝鍓嶇鍙浼?`username`銆乣password`銆乣nickname`銆乣email`锛屾墍浠ユ湰椤圭洰瀹氫箟浜?`UserRegisterRequest`锛?  ```java
  @Data
  public class UserRegisterRequest {
      @NotBlank(message = "鐢ㄦ埛鍚嶄笉鑳戒负绌?)
      @Size(min = 3, max = 20)
      private String username;
      @NotBlank @Size(min = 8, max = 50)
      private String password;
      @Size(max = 30)
      private String nickname;
      @Email
      private String email;
  }
  ```
  杩欏氨鏄?**DTO**锛屽彧鏈夊墠绔細浼犵殑瀛楁銆?
- 鏌ヨ鐢ㄦ埛鏃讹紝缁欏墠绔繑鍥炵殑瀵硅薄涓嶈兘鍖呭惈 `password`銆乣isDeleted`锛屾墍浠ュ彟瀹氫箟浜?`UserVO`锛屽彧鏀惧彲鍏紑鐨勫瓧娈碉紙id銆乽sername銆乶ickname銆乤vatar 绛夛級銆?
濡傛灉鐩存帴鎶?`SysUser` 瀹炰綋绫昏繑鍥炵粰鍓嶇锛?1. 瀵嗙爜浼氭硠闇诧紙铏界劧 `@JsonIgnore` 鑳芥尅涓€涓嬶級銆?2. 鏁版嵁搴撳瓧娈典竴鍙橈紝鍓嶇濂戠害灏辫窡鐫€宕┿€?3. 娌℃硶绮剧粏鎺у埗鏉冮檺锛堟瘮濡傛湰椤圭洰閲?鍙湁鏈汉鎴栫鐞嗗憳鑳界湅鍒?email銆乺ole"锛夈€?
鈿狅笍 涓€鏉￠搧寰嬶細**Controller 鍏ュ弬鐢?DTO锛屽嚭鍙傜敤 VO锛孍ntity 鍙湪 service / mapper 鍐呴儴娴佽浆**銆?
## 6.6 IoC / DI 閫熼€?
Spring 鏈€鏍稿績鐨勬蹇垫槸 **IoC锛堟帶鍒跺弽杞級** 鍜?**DI锛堜緷璧栨敞鍏ワ級**銆傚惉璧锋潵鐜勪箮锛屽叾瀹炰竴涓瘮鍠诲氨鎳傦細

> 鑰佸紡鍋氭硶锛氫綘鎯冲枬姘达紝鑷繁璧板埌楗按鏈烘帴姘达紙鑷繁 new 瀵硅薄锛夈€?> Spring 鍋氭硶锛氫綘涓炬墜鍠?鎴戣姘?锛屾湇鍔″憳鑷姩閫佽繃鏉ワ紙瀹瑰櫒鑷姩娉ㄥ叆锛夈€?
鎺у埗鍙嶈浆 = 鎶?鍒涘缓瀵硅薄"鐨勬潈鍔涗粠浣犳墜閲屽弽杞粰 Spring 瀹瑰櫒銆?渚濊禆娉ㄥ叆 = 瀹瑰櫒鎶婁綘闇€瑕佺殑瀵硅薄濉炵粰浣犮€?
鏈」鐩噷鍒板鍙锛?
```java
@Service
public class SysUserServiceImpl ... {
    @Autowired
    private JwtUtils jwtUtils;
    @Autowired
    private BCryptPasswordEncoder passwordEncoder;
}
```

`@Autowired` 鍛婅瘔 Spring锛?璇锋妸宸茬粡鍒涘缓濂界殑 `JwtUtils` Bean 濉炵粰鎴?銆係pring 鍚姩鏃朵細鎵弿鎵€鏈?`@Component / @Service / @Controller / @Repository / @Configuration`锛屾妸瀹冧滑閮芥敞鍐岃繘瀹瑰櫒锛岀劧鍚庢寜闇€娉ㄥ叆銆?
甯歌 Bean 娉ㄨВ锛?
| 娉ㄨВ | 鐢ㄩ€?|
|------|------|
| `@Component` | 閫氱敤 Bean |
| `@Service` | 涓氬姟灞?Bean |
| `@Repository` | 鎸佷箙灞?Bean锛圡P 鐢?`@Mapper`锛?|
| `@Controller` / `@RestController` | 鎺у埗鍣?Bean |
| `@Configuration` | 閰嶇疆绫?|
| `@Bean` | 鍦ㄩ厤缃被鐨勬柟娉曚笂澹版槑涓€涓?Bean |

鈿狅笍 鎺ㄨ崘鐢?*鏋勯€犲櫒娉ㄥ叆**鑰屼笉鏄瓧娈垫敞鍏ワ紙鏇村埄浜庢祴璇曞拰涓嶅彲鍙樻€э級锛屼絾灏忓瀷椤圭洰鐢?`@Autowired` 瀛楁娉ㄥ叆涔熷緢甯歌銆?
## 6.7 椤圭洰瀹為檯璋冪敤閾撅細娉ㄥ唽鎺ュ彛

鏈€鍚庢垜浠蛋涓€閬?娉ㄥ唽鎺ュ彛"鐨勫畬鏁磋皟鐢ㄩ摼锛屾妸鎵€鏈夊眰涓茶捣鏉ワ細

```
鍓嶇
  鈫?POST /api/user/register  body: {username, password, nickname, email}
SysUserController.register(...)
  鈫?@Valid 瑙﹀彂鍙傛暟鏍￠獙
  鈫?璋冪敤
SysUserService.register(request)
  鈫?瀹炵幇鏄?SysUserServiceImpl.register(...)
    1. 鏍￠獙瀵嗙爜澶嶆潅搴︼紙鑷冲皯 8 浣嶃€佸惈 3 绫诲瓧绗︼級
    2. LambdaQueryWrapper 妫€鏌?username 鏄惁宸插瓨鍦?    3. LambdaQueryWrapper 妫€鏌?email 鏄惁宸插瓨鍦?    4. BCryptPasswordEncoder.encode(password) 鍔犲瘑瀵嗙爜
    5. this.save(user) 鈫?璋冪敤 BaseMapper.insert
       鈫?SysUserMapper锛圔aseMapper锛?    INSERT INTO sys_user (...) VALUES (...)
       鈫?MySQL
       鈫?杩斿洖鏂板 id
鍥炲埌 service锛歭og.info("鐢ㄦ埛娉ㄥ唽鎴愬姛")
鍥炲埌 controller锛歊esult.success(new UserRegisterResponse(id, username))
       鈫?搴忓垪鍖栦负 JSON
鍓嶇鏀跺埌锛歿"code":200,"message":"鎿嶄綔鎴愬姛","data":{"id":1,"username":"..."}}
```

鏁存潯閾捐矾闈炲父娓呮櫚锛屾瘡涓€灞傝亴璐ｅ崟涓€锛岃繖灏辨槸鍒嗗眰鐨勫姏閲忋€?
### 涓€鍙ヨ瘽鎬荤粨
> Controller 鎺ヨ姹傘€丼ervice 鍐欎笟鍔°€丮apper 璺?SQL锛孍ntity / DTO / VO 鍚勫徃鍏惰亴锛岄潬 IoC 瀹瑰櫒鎶婂畠浠矘璧锋潵銆?
---

# 绗?7 绔?缁熶竴鍝嶅簲涓庡紓甯稿鐞?
## 7.1 涓轰粈涔堣缁熶竴鍝嶅簲

璁炬兂涓€涓嬶細鐧诲綍鎺ュ彛杩斿洖 `{"token": "xxx"}`锛屾敞鍐屾帴鍙ｈ繑鍥?`{"id": 1, "ok": true}`锛屾煡璇㈡帴鍙ｈ繑鍥?`[{...}, {...}]`銆傚墠绔瘡鎺ヤ竴涓帴鍙ｉ兘寰楃寽鎴愬姛澶辫触濡備綍鍒ゆ柇銆侀敊璇俊鎭湪鍝€傛贩涔辨棤姣斻€?
鎵€浠ヤ紒涓氱骇椤圭洰閮借瀹氾細**鎵€鏈夋帴鍙ｉ兘杩斿洖鍚屼竴涓灞傜粨鏋?*锛岄噷闈㈡湁锛?
- `code`锛氫笟鍔＄姸鎬佺爜锛?00 鎴愬姛銆?00 澶辫触銆?01 鏈櫥褰曘€?03 鏃犳潈闄?..锛?- `message`锛氬彲璇荤殑鎻愮ず
- `data`锛氫笟鍔℃暟鎹紙鍙兘涓?null锛?- `timestamp`锛氭椂闂存埑锛堜究浜庢帓鏌ワ級

杩欐牱鍓嶇鍙渶瑕佸啓涓€濂楀叏灞€鎷︽埅鍣細`if (res.code === 200) ...else 寮归敊璇痐銆傛湰椤圭洰閲屽氨杩欎箞骞层€?
## 7.2 Result 绫昏瑙ｏ紙鍩轰簬鐪熷疄 `Result.java`锛?
```java
@Data
public class Result<T> implements Serializable {
    private Integer code;
    private String message;
    private T data;
    private long timestamp;

    private Result() {
        this.timestamp = System.currentTimeMillis();
    }

    public static <T> Result<T> success() { ... }
    public static <T> Result<T> success(T data) {
        Result<T> result = new Result<>();
        result.setCode(200);
        result.setMessage("鎿嶄綔鎴愬姛");
        result.setData(data);
        return result;
    }
    public static <T> Result<T> success(String message, T data) { ... }
    public static <T> Result<T> error() { ... }
    public static <T> Result<T> error(String message) { ... }
    public static <T> Result<T> error(Integer code, String message) { ... }
}
```

鍑犱釜鍊煎緱璁茬殑璁捐鐐癸細

1. **娉涘瀷 `<T>`**锛歚Result<UserVO>`銆乣Result<IPage<BlogPost>>`銆乣Result<Void>`锛岃浠讳綍涓氬姟鏁版嵁閮借兘瑁呰繘 `data`锛屼笖绫诲瀷瀹夊叏銆?2. **绉佹湁鏋勯€犳柟娉?+ 闈欐€佸伐鍘?*锛氶伩鍏嶅閮ㄧ洿鎺?`new Result()`锛屽己鍒惰蛋 `Result.success()` / `Result.error()`锛屽懡鍚嶆洿璇箟鍖栥€?3. **timestamp 鑷姩璧嬪€?*锛氭瀯閫犳柟娉曢噷 `this.timestamp = System.currentTimeMillis()`锛屼笉鐢ㄦ瘡娆℃墜鍔ㄨ缃€?4. **澶氫釜閲嶈浇**锛氫綘鍙互 `success()`銆乣success(data)`銆乣success(msg, data)`銆乣error()`銆乣error(msg)`銆乣error(code, msg)`锛屾寜闇€閫夌敤銆?
搴忓垪鍖栦负 JSON 鐨勬牱瀛愶細

```json
{
  "code": 200,
  "message": "鎿嶄綔鎴愬姛",
  "data": { "id": 1, "username": "liuchang" },
  "timestamp": 1719999999999
}
```

## 7.3 BusinessException锛堝熀浜庣湡瀹炰唬鐮侊級

涓氬姟寮傚父涓撻棬鐢ㄦ潵琛ㄨ揪"涓氬姟瑙勫垯涓嶅厑璁?锛屾瘮濡?鐢ㄦ埛鍚嶅凡瀛樺湪"銆?瀵嗙爜閿欒"銆?鏃犳潈鎿嶄綔"銆傛湰椤圭洰鐨勫畾涔夛細

```java
@Getter
public class BusinessException extends RuntimeException {
    private final Integer code;

    public BusinessException(String message) {
        super(message);
        this.code = 500;
    }

    public BusinessException(Integer code, String message) {
        super(message);
        this.code = code;
    }
}
```

缁ф壙 `RuntimeException`锛堣繍琛屾椂寮傚父锛夌殑濂藉鏄細鏂规硶绛惧悕涓婁笉鐢?`throws`锛岃皟鐢ㄦ柟涓嶇敤寮哄埗 try-catch锛屾竻鐖姐€?
`@Getter` 鏄?Lombok 娉ㄨВ锛岃嚜鍔ㄧ敓鎴?`getCode()`銆俙message` 鐢辩埗绫荤鐞嗭紝閫氳繃 `getMessage()` 鍙栥€?
浣跨敤鏂瑰紡閬嶅竷鍏ㄩ」鐩細

```java
if (user == null) {
    throw new BusinessException(401, "鐢ㄦ埛鍚嶆垨瀵嗙爜閿欒");
}
if (user.getStatus() == 0) {
    throw new BusinessException(403, "璐﹀彿宸茶绂佺敤");
}
if (categories < 3) {
    throw new BusinessException(400, "瀵嗙爜蹇呴』鍖呭惈澶у皬鍐欏瓧姣嶃€佹暟瀛楁垨鐗规畩瀛楃涓殑鑷冲皯3绉?);
}
```

鈿狅笍 **姘歌繙涓嶈鍦?service / controller 閲屽啓 `try { ... } catch { return Result.error(...) }` 鏉ュ鐞嗕笟鍔￠敊璇?*銆傜粺涓€鎶?`BusinessException`锛岃鍏ㄥ眬寮傚父澶勭悊鍣ㄥ幓杞崲銆?
## 7.4 GlobalExceptionHandler锛坄@RestControllerAdvice`锛?
寮傚父鎶涘嚭鍚庤璋佹帴浣忥紵绛旓細`GlobalExceptionHandler`銆傝繖鏄竴涓叏灞€鎷︽埅鍣紝涓撻棬鎹曡幏鎵€鏈夋帶鍒跺櫒鎶涘嚭鐨勫紓甯革紝杞垚缁熶竴鐨?`Result` 杩斿洖銆?
```java
@Slf4j
@RestControllerAdvice
public class GlobalExceptionHandler {

    @ExceptionHandler(BusinessException.class)
    public Result<Void> handleBusinessException(BusinessException e) {
        log.warn("涓氬姟寮傚父锛歔{}]", e.getClass().getSimpleName());
        return Result.error(e.getCode(), e.getMessage());
    }

    @ExceptionHandler(MethodArgumentNotValidException.class)
    public Result<Void> handleValidationException(MethodArgumentNotValidException e) {
        String message = e.getBindingResult().getFieldError() != null
                ? e.getBindingResult().getFieldError().getDefaultMessage()
                : "鍙傛暟鏍￠獙澶辫触";
        log.warn("鍙傛暟鏍￠獙寮傚父锛歿}", message);
        return Result.error(400, message);
    }

    @ExceptionHandler(DuplicateKeyException.class)
    public Result<Void> handleDuplicateKeyException(DuplicateKeyException e) {
        return Result.error(409, "鏁版嵁宸插瓨鍦紝鎿嶄綔鍐茬獊");
    }

    @ExceptionHandler(AccessDeniedException.class)
    public Result<Void> handleAccessDeniedException(AccessDeniedException e) {
        return Result.error(403, "鏉冮檺涓嶈冻锛屾嫆缁濊闂?);
    }

    @ExceptionHandler(AuthenticationException.class)
    public Result<Void> handleAuthenticationException(AuthenticationException e) {
        return Result.error(401, "璁よ瘉澶辫触锛岃鍏堢櫥褰?);
    }

    @ExceptionHandler(Throwable.class)
    public Result<Void> handleThrowable(Throwable e) {
        log.error("绯荤粺寮傚父: {}", e.getMessage(), e);
        return Result.error(500, "绯荤粺鍐呴儴閿欒锛岃绋嶅悗閲嶈瘯");
    }
}
```

鍏抽敭娉ㄨВ锛?
- `@RestControllerAdvice`锛氱瓑浜?`@ControllerAdvice + @ResponseBody`锛屽鎵€鏈?`@RestController` 鐢熸晥锛屼笖杩斿洖 JSON銆?- `@ExceptionHandler(XxxException.class)`锛氬０鏄庤繖涓柟娉曞鐞嗗摢绉嶅紓甯搞€係pring 浼氭寜"鏈€鍏蜂綋浼樺厛"鐨勫師鍒欏尮閰嶃€?
鏈」鐩鐞嗙殑寮傚父绫诲瀷寰堝叏锛?
| 寮傚父 | 鍚箟 | 杩斿洖 code |
|------|------|-----------|
| `BusinessException` | 涓氬姟寮傚父 | 500 / 鑷畾涔?|
| `MethodArgumentNotValidException` | `@Valid` 鍙傛暟鏍￠獙澶辫触 | 400 |
| `BindException` | 琛ㄥ崟缁戝畾鏍￠獙澶辫触 | 400 |
| `ConstraintViolationException` | JPA 椋庢牸鐨勬牎楠屽け璐?| 400 |
| `MissingServletRequestParameterException` | 缂哄皯蹇呭～鍙傛暟 | 400 |
| `HttpMessageNotReadableException` | 璇锋眰浣撴牸寮忛敊璇?| 400 |
| `NoHandlerFoundException` | 404 璧勬簮涓嶅瓨鍦?| 404 |
| `DuplicateKeyException` | 鏁版嵁搴撳敮涓€绾︽潫鍐茬獊 | 409 |
| `AccessDeniedException` | Spring Security 閴存潈澶辫触 | 403 |
| `AuthenticationException` | Spring Security 璁よ瘉澶辫触 | 401 |
| `MaxUploadSizeExceededException` | 鏂囦欢涓婁紶瓒呴檺 | 400 |
| `Throwable`锛堝厹搴曪級 | 浠讳綍鏈崟鑾风殑寮傚父 | 500 |

鈿狅笍 娉ㄦ剰 `Throwable` 鍏滃簳澶勭悊鏃跺彧 `log.error` 鑰?*涓嶆妸鍫嗘爤娉勯湶缁欏墠绔?*锛岄伩鍏嶆毚闇插唴閮ㄧ粨鏋勶紙杩欐槸 v1.34 瀹夊叏澧炲己鐨勭粏鑺備箣涓€锛夈€?
## 7.5 鍙傛暟鏍￠獙娉ㄨВ

鍙傛暟鏍￠獙鏄?Web 搴旂敤鐨?绗竴閬撻槻绾?銆傛湰椤圭洰鐢?Bean Validation锛圝SR-303锛夎鑼冿細

```java
public class UserRegisterRequest {
    @NotBlank(message = "鐢ㄦ埛鍚嶄笉鑳戒负绌?)
    @Size(min = 3, max = 20, message = "鐢ㄦ埛鍚嶉暱搴﹀繀椤诲湪3-20涓瓧绗︿箣闂?)
    private String username;

    @NotBlank(message = "瀵嗙爜涓嶈兘涓虹┖")
    @Size(min = 8, max = 50, message = "瀵嗙爜闀垮害蹇呴』鍦?-50涓瓧绗︿箣闂?)
    private String password;

    @Size(max = 30, message = "鏄电О闀垮害涓嶈兘瓒呰繃30涓瓧绗?)
    private String nickname;

    @Email(message = "閭鏍煎紡涓嶆纭?)
    private String email;
}
```

甯哥敤娉ㄨВ锛?
| 娉ㄨВ | 鍚箟 |
|------|------|
| `@NotNull` | 涓嶈兘涓?null |
| `@NotEmpty` | 涓嶈兘涓?null 涓?size > 0锛堢敤浜?String / Collection锛?|
| `@NotBlank` | 瀛楃涓蹭笉鑳戒负 null / 绌轰覆 / 鍏ㄧ┖鏍?|
| `@Size(min=, max=)` | 闀垮害闄愬埗 |
| `@Min` / `@Max` | 鏁板€兼渶灏?/ 鏈€澶?|
| `@Email` | 閭鏍煎紡 |
| `@Pattern(regexp=...)` | 姝ｅ垯鍖归厤 |

瑕佽鏍￠獙鐢熸晥锛?*蹇呴』**鍦?controller 鏂规硶鐨勫弬鏁板墠鍔?`@Valid`锛?
```java
@PostMapping("/register")
public Result<UserRegisterResponse> register(@Valid @RequestBody UserRegisterRequest request) {
    return Result.success(sysUserService.register(request));
}
```

鏍￠獙澶辫触浼氭姏 `MethodArgumentNotValidException`锛岃 `GlobalExceptionHandler` 杞垚锛?
```json
{ "code": 400, "message": "鐢ㄦ埛鍚嶉暱搴﹀繀椤诲湪3-20涓瓧绗︿箣闂?, "data": null }
```

GET 璇锋眰鐨勬煡璇㈠弬鏁帮紙濡?`UserSearchRequest`锛変篃瑕佸姞 `@Valid`锛?
```java
@GetMapping("/search")
public Result<IPage<UserVO>> searchUsers(@Valid UserSearchRequest request) {
    return Result.success(sysUserService.searchUsers(request));
}
```

## 7.6 瀹屾暣璇锋眰澶勭悊娴佺▼鍥?
鎴戜滑鎶?7.1 ~ 7.5 涓茶捣鏉ワ細

```
鍓嶇鍙戣捣 POST /user/register
   鈫?DispatcherServlet锛圫pring MVC 鍏ュ彛锛?   鈫?璺敱鍒?SysUserController.register
   鈫?@RequestBody 瑙ｆ瀽 JSON 鈫?UserRegisterRequest
   鈫?@Valid 瑙﹀彂 Bean Validation
   鈹?    鈹溾攢鈹€ 鏍￠獙澶辫触 鈫?鎶?MethodArgumentNotValidException
   鈹?    鈹?             鈫?GlobalExceptionHandler 鎺ヤ綇
   鈹?    鈹?             鈫?Result.error(400, "...") 鈫?杩斿洖 JSON
   鈹?    鈹斺攢鈹€ 鏍￠獙閫氳繃 鈫?杩涘叆 service
   鈫?SysUserService.register
   鈹?    鈹溾攢鈹€ 涓氬姟瑙勫垯涓嶉€氳繃 鈫?throw new BusinessException(400, "...")
   鈹?    鈹?             鈫?GlobalExceptionHandler 鎺ヤ綇
   鈹?    鈹?             鈫?Result.error(400, "...") 鈫?杩斿洖 JSON
   鈹?    鈹斺攢鈹€ 閫氳繃 鈫?return UserRegisterResponse
   鈫?Controller: return Result.success(response)
   鈫?Spring 搴忓垪鍖栦负 JSON 杩斿洖鍓嶇
```

鏃犺鎴愬姛澶辫触锛屽墠绔€绘槸鏀跺埌 `{ code, message, data, timestamp }` 杩欑缁撴瀯銆?
### 涓€鍙ヨ瘽鎬荤粨
> `Result` 缁熶竴杩斿洖鏍煎紡锛宍BusinessException` 浼橀泤鎶涗笟鍔￠敊璇紝`GlobalExceptionHandler` 鍏ㄥ眬鍏滃簳锛屼笁浠跺璁╂帴鍙ｅ張骞插噣鍙堜竴鑷淬€?
---

# 绗?8 绔?Spring Security 鍏ラ棬

## 8.1 璁よ瘉 vs 鎺堟潈

瀛?Spring Security 涔嬪墠锛屽厛鍒嗘竻涓や釜璇嶏細

- **璁よ瘉锛圓uthentication锛?*锛氫綘鏄皝锛熸瘮濡傜櫥褰曞氨鏄璇侊細浣犳彁浜ょ敤鎴峰悕瀵嗙爜锛岀郴缁熻瘑鍒?鍝︼紝浣犳槸鐢ㄦ埛 ID 1 鐨勫垬鐣?銆?- **鎺堟潈锛圓uthorization锛?*锛氫綘鑳藉仛浠€涔堬紵姣斿鏅€氱敤鎴蜂笉鑳借闂?`/admin/**`锛岀鐞嗗憳鍙互锛涜繖灏辨槸鎺堟潈銆?
浜岃€呯粡甯镐竴璧峰嚭鐜帮紝浣嗘蹇典笂蹇呴』鍒嗗紑銆係pring Security 鏄?Java 涓栫晫澶勭悊杩欎袱浠朵簨鐨勪簨瀹炴爣鍑嗐€?
## 8.2 SecurityConfig 閰嶇疆绫昏瑙ｏ紙鍩轰簬鐪熷疄 `SecurityConfig.java`锛?
鏈」鐩殑鏍稿績閰嶇疆鍦?`SecurityConfig.java`锛?
```java
@Configuration
@EnableWebSecurity
public class SecurityConfig {

    @Autowired
    private JwtAuthenticationFilter jwtAuthenticationFilter;

    @Value("${cors.allowed-origins:http://localhost:8080,http://127.0.0.1:8080}")
    private String allowedOrigins;

    @Bean
    public BCryptPasswordEncoder passwordEncoder() {
        return new BCryptPasswordEncoder(12);
    }

    @Bean
    public CorsConfigurationSource corsConfigurationSource() { ... }

    @Bean
    public SecurityFilterChain securityFilterChain(HttpSecurity http) throws Exception {
        http
            .csrf(csrf -> csrf.disable())
            .cors(cors -> cors.configurationSource(corsConfigurationSource()))
            .sessionManagement(session -> session.sessionCreationPolicy(SessionCreationPolicy.STATELESS))
            .authorizeHttpRequests(authorize -> authorize
                .requestMatchers(HttpMethod.OPTIONS, "/**").permitAll()
                .requestMatchers("/user/register", "/user/login", "/user/refresh").permitAll()
                .requestMatchers("/doc.html", "/swagger-ui/**", "/v3/api-docs/**", "/swagger-resources/**", "/webjars/**").permitAll()
                .requestMatchers("/admin/**").hasRole("admin")
                .requestMatchers(HttpMethod.GET, "/post/**").permitAll()
                .requestMatchers(HttpMethod.GET, "/comment/post/**").permitAll()
                .requestMatchers(HttpMethod.GET, "/like/check/**", "/collect/check/**").permitAll()
                .requestMatchers(HttpMethod.GET, "/tag/**").permitAll()
                .requestMatchers(HttpMethod.GET, "/follow/check/**").permitAll()
                .requestMatchers("/follow/**").authenticated()
                .requestMatchers(HttpMethod.POST, "/post/**").authenticated()
                .requestMatchers(HttpMethod.PUT, "/post/**").authenticated()
                .requestMatchers(HttpMethod.DELETE, "/post/**").authenticated()
                .anyRequest().authenticated()
            )
            .addFilterBefore(jwtAuthenticationFilter, UsernamePasswordAuthenticationFilter.class);
        return http.build();
    }
}
```

閫愰」瑙ｈ锛?
### `@EnableWebSecurity`
鍚敤 Spring Security 鐨?Web 瀹夊叏鏀寔銆?
### `csrf(csrf -> csrf.disable())`
鍏抽棴 CSRF锛堣法绔欒姹備吉閫狅級闃叉姢銆?*涓轰粈涔堝叧锛?* 鍥犱负鎴戜滑鐢ㄧ殑鏄?JWT 鏃犵姸鎬佽璇侊紝涓嶄緷璧?Cookie/Session锛孋SRF 鏀诲嚮鐨勮浇浣擄紙鑷姩鍙戦€佺殑 Cookie锛変笉瀛樺湪锛屾墍浠ュ彲浠ュ叧闂€備絾濡傛灉浣犵敤 Session 璁よ瘉锛?*缁濅笉鑳藉叧 CSRF**銆?
### `cors(...)`
寮€鍚法鍩熸敮鎸併€傛湰椤圭洰閫氳繃 `@Value("${cors.allowed-origins:...}")` 浠庨厤缃鍙栧厑璁哥殑鏉ユ簮锛屼緥濡?`http://localhost:8080`銆傚墠鍚庣鍒嗙寮€鍙戞椂锛堝墠绔窇鍦?8080銆佸悗绔窇鍦?8825锛夛紝蹇呴』姝ｇ‘閰嶇疆 CORS锛屽惁鍒欐祻瑙堝櫒浼氭嫤鎴姹傘€?
### `sessionCreationPolicy(STATELESS)`
涓嶅垱寤?HTTP Session銆傛棤鐘舵€佹剰鍛崇潃姣忎釜璇锋眰閮藉緱鑷繁甯﹁韩浠藉嚟璇侊紙涔熷氨鏄?JWT锛夈€?
### `authorizeHttpRequests(...)`
鏈€閲嶈鐨勯儴鍒嗭細**URL 閴存潈瑙勫垯**銆傝鍒欐寜浠庝笂鍒颁笅椤哄簭鍖归厤锛屽厛鍖归厤鐨勫厛鐢熸晥锛?
| 瑙勫垯 | 鍚箟 |
|------|------|
| `OPTIONS /**` permitAll | 璺ㄥ煙棰勬璇锋眰涓€寰嬫斁琛?|
| `/user/register, /user/login, /user/refresh` permitAll | 娉ㄥ唽銆佺櫥褰曘€佸埛鏂?token 涓嶉渶瑕佺櫥褰?|
| Swagger 鐩稿叧璺緞 permitAll | API 鏂囨。瀵瑰叕缃戝紑鏀?|
| `/admin/**` hasRole("admin") | 绠＄悊鍛樿矾寰勫繀椤?admin 瑙掕壊 |
| `GET /post/**` permitAll | 鏂囩珷鍒楄〃/璇︽儏鍖垮悕鍙湅 |
| `POST/PUT/DELETE /post/**` authenticated | 鍙戝竷/淇敼/鍒犻櫎鏂囩珷蹇呴』鐧诲綍 |
| `anyRequest().authenticated()` | 鍏朵粬鎵€鏈夎姹傞兘瑕佺櫥褰?|

### `addFilterBefore(jwtAuthenticationFilter, UsernamePasswordAuthenticationFilter.class)`
鎶婅嚜瀹氫箟鐨?JWT 杩囨护鍣ㄦ彃鍒?Spring Security 鐨勮繃婊ら摼涓紙璇﹁绗?9 绔狅級銆備綅缃緢鍏抽敭锛氭斁鍦?`UsernamePasswordAuthenticationFilter` 涔嬪墠锛屽厛鐢?JWT 瀹屾垚璁よ瘉銆?
## 8.3 BCrypt 瀵嗙爜鍔犲瘑锛堝己搴?12锛?
```java
@Bean
public BCryptPasswordEncoder passwordEncoder() {
    return new BCryptPasswordEncoder(12);
}
```

- **BCrypt** 鏄綋鍓嶄笟鐣屾帹鑽愮殑瀵嗙爜鍝堝笇绠楁硶銆傚畠鏈変袱涓壒寰侊細
  1. **鍔犵洂锛坰alt锛?*锛氭瘡娆″搱甯岄兘鍔犻殢鏈虹洂鍊硷紝鐩稿悓瀵嗙爜姣忔鍝堝笇缁撴灉涓嶅悓锛岄槻姝㈠僵铏硅〃鏀诲嚮銆?  2. **鎱㈠搱甯?*锛氭晠鎰忚璁″緱鎱紝浣挎毚鍔涚牬瑙ｄ唬浠锋瀬楂樸€?- **寮哄害锛坈ost factor锛? 12** 琛ㄧず杩涜 2^12 = 4096 杞搱甯屻€傚€艰秺澶ц秺瀹夊叏浣嗚秺鑰楁椂銆傛湰椤圭洰閫?12锛屾棦瀹夊叏鍙堣兘鍦ㄦ櫘閫氭湇鍔″櫒涓婂嚑鍗佹绉掑唴瀹屾垚楠岃瘉銆?
浣跨敤鏂瑰紡锛?
```java
// 娉ㄥ唽鏃跺姞瀵?user.setPassword(passwordEncoder.encode(request.getPassword()));

// 鐧诲綍鏃舵牎楠?if (!passwordEncoder.matches(request.getPassword(), user.getPassword())) {
    throw new BusinessException(401, "鐢ㄦ埛鍚嶆垨瀵嗙爜閿欒");
}
```

鈿狅笍 **缁濆涓嶈兘**鐢?MD5銆丼HA1銆丼HA256 鐩存帴瀛樺瘑鐮侊紒瀹冧滑閫熷害澶揩锛屽凡缁忚鐮磋В鍒颁笉瀹夊叏鐨勭▼搴︺€?
## 8.4 CSRF / CORS 绠€浠?
### CSRF锛圕ross-Site Request Forgery锛岃法绔欒姹備吉閫狅級
鏀诲嚮鑰呰瀵间綘璁块棶涓€涓吉瑁呯殑缃戠珯锛岃缃戠珯鍋峰伔鍚戜綘宸茬櫥褰曠殑閾惰绯荤粺鍙戣姹傦紙鍒╃敤娴忚鍣ㄨ嚜鍔ㄥ甫 Cookie锛夈€傞槻寰￠潬 CSRF Token銆?鏈」鐩敤 JWT 鏃犵姸鎬併€佷笉闈?Cookie锛屾墍浠ュ彲浠ユ斁蹇?`csrf().disable()`銆?
### CORS锛圕ross-Origin Resource Sharing锛岃法婧愯祫婧愬叡浜級
娴忚鍣ㄧ殑鍚屾簮绛栫暐锛氳剼鏈笉鑳借闂笌褰撳墠椤甸潰"鍗忚+鍩熷悕+绔彛"涓嶅悓鐨勮祫婧愩€傚墠鍚庣鍒嗙鏃讹紝鍓嶇 `http://localhost:8080` 鎯宠闂悗绔?`http://localhost:8825`锛岀鍙ｄ笉鍚屽氨璺ㄦ簮浜嗐€侰ORS 灏辨槸鍚庣閫氳繃鍝嶅簲澶村憡璇夋祻瑙堝櫒锛?鎴戝厑璁歌繖涓潵婧?銆?
鏈」鐩殑 CORS 閰嶇疆锛堣妭閫夛級锛?
```java
configuration.addAllowedOriginPattern(trimmed); // 鍏佽鐨勬潵婧?configuration.addAllowedHeader("*");
configuration.addAllowedMethod("*");
configuration.setAllowCredentials(true);        // 鍏佽甯﹀嚟璇侊紙Cookie / Authorization锛?configuration.setMaxAge(3600L);
```

鈿狅笍 瀹夊叏鎻愮ず锛?*缁濅笉瑕?`addAllowedOrigin("*")` + `setAllowCredentials(true)` 鍚屾椂瀛樺湪**锛岄偅鏄潪甯镐弗閲嶇殑瀹夊叏婕忔礊銆傛湰椤圭洰浠庣幆澧冨彉閲忚鍙栨槑纭殑鐧藉悕鍗曘€?
## 8.5 涓€娆＄櫥褰曡姹傚畬鏁存祦绋?
璧颁竴閬?`POST /user/login`锛?
```
1. 鍓嶇鎻愪氦 {"username":"liuchang","password":"Abc12345"}
2. Spring Security 杩囨护閾惧紑濮嬶細
   - JwtAuthenticationFilter 妫€鏌?Authorization header锛堟病鏈夛紝璺宠繃锛?   - 璺緞 "/user/login" 鍖归厤 permitAll锛屼笉闇€瑕佽璇侊紝鏀捐
3. 杩涘叆 SysUserController.login(...)
4. SysUserServiceImpl.login(...)
   - 鐢?LambdaQueryWrapper 鎸?username 鏌?user
   - 妫€鏌ラ攣瀹氱姸鎬併€佽处鍙风姸鎬?   - passwordEncoder.matches(鏄庢枃, 鏁版嵁搴撳瘑鏂? 瀵规瘮
     - 澶辫触 鈫?handleLoginFailAtomic(userId) 鍘熷瓙+1锛屽彲鑳介攣瀹?       throw new BusinessException(401, "鐢ㄦ埛鍚嶆垨瀵嗙爜閿欒")
     - 鎴愬姛 鈫?閲嶇疆澶辫触璁℃暟锛岀敓鎴?token
5. jwtUtils.generateToken(userId, username, role)  鈫?鏅€?token
   jwtUtils.generateRefreshToken(...)              鈫?鍒锋柊 token
6. 杩斿洖 UserLoginResponse(id, username, nickname, avatar, token, refreshToken)
7. Result.success(response) 鈫?JSON 缁欏墠绔?8. 鍓嶇鎶?token 瀛?localStorage锛屽悗缁姹傚甫鍦?header锛?   Authorization: Bearer eyJhbGciOiJIUzI1NiJ9...
```

### 涓€鍙ヨ瘽鎬荤粨
> Spring Security 鎶?鍝簺璺緞闇€瑕佺櫥褰曘€佸摢浜涜鑹叉墠鑳借闂€佸瘑鐮佹€庝箞鍔犲瘑銆佽法鍩熸€庝箞閰嶇疆"鍏ㄦ墦鍖呭ソ锛屾湰椤圭洰鐢ㄥ畠 + JWT 瀹炵幇浜嗘棤鐘舵€佺殑瀹夊叏闃叉姢銆?
---

# 绗?9 绔?JWT 璁よ瘉瀹炴垬

## 9.1 JWT 鏄粈涔?
**JWT锛圝SON Web Token锛?* 鏄竴绉?鑷寘鍚殑銆佸彲楠岃瘉鐨?浠ょ墝鏍煎紡銆傚畠瑙ｅ喅浜嗕竴涓棶棰橈細**濡備綍鍦ㄦ棤鐘舵€佺殑 HTTP 涓婅瘑鍒敤鎴疯韩浠?*銆?
浼犵粺 Session 鏂规锛氭湇鍔″櫒瀛?sessionId 鈫?user 鐨勬槧灏勶紝鍓嶇鐨?Cookie 甯?sessionId 鏉ャ€?JWT 鏂规锛氭湇鍔″櫒绛惧彂涓€涓姞瀵嗗瓧绗︿覆锛坱oken锛夛紝閲岄潰宸茬粡鍖呭惈浜嗙敤鎴?id銆佽鑹茬瓑淇℃伅锛屽墠绔瘡娆¤姹傚甫鍦?`Authorization` 澶撮噷銆?
JWT 鐨勭壒鐐癸細

- **鏃犵姸鎬?*锛氭湇鍔″櫒涓嶅瓨 session锛屽瀹炰緥閮ㄧ讲鏃朵笉鐢ㄥ悓姝ャ€?- **鑷寘鍚?*锛歵oken 瑙ｇ爜鍚庤兘鐩存帴璇诲埌 userId銆乺ole銆?- **鍙獙璇?*锛氭湇鍔″櫒鐢ㄥ瘑閽ョ鍚嶏紝浠讳綍绡℃敼浼氬鑷寸鍚嶉獙璇佸け璐ャ€?
鈿狅笍 JWT 鏈韩**涓嶅姞瀵?*锛屽彧绛惧悕锛乸ayload 鏄?Base64 缂栫爜鐨勶紝璋佹嬁鍒伴兘鑳借В鐮侊紝鎵€浠?*缁濅笉瑕佸湪 payload 閲屾斁瀵嗙爜銆侀摱琛屽崱鍙风瓑鏁忔劅淇℃伅**銆?
## 9.2 JWT 涓夋缁撴瀯

涓€涓吀鍨嬬殑 JWT 瀛楃涓查暱杩欐牱锛?
```
eyJhbGciOiJIUzI1NiJ9.eyJ1c2VySWQiOjEsInVzZXJuYW1lIjoibGl1Y2hhbmciLCJyb2xlIjoidXNlciIsInN1YiI6ImxpdWNoYW5nIn0.5xj6q0...
```

琚袱涓?."鍒嗘垚涓夋锛?
| 娈?| 鍚嶅瓧 | 鍐呭 |
|----|------|------|
| 绗?1 娈?| Header锛堝ご閮級 | 绠楁硶 + 绫诲瀷锛屽 `{"alg":"HS256","typ":"JWT"}` |
| 绗?2 娈?| Payload锛堣浇鑽凤級 | 涓氬姟鏁版嵁锛屽 `{"userId":1,"username":"liuchang","role":"user","exp":1719999999}` |
| 绗?3 娈?| Signature锛堢鍚嶏級 | 鐢ㄦ湇鍔″櫒瀵嗛挜瀵瑰墠涓ゆ鍋?HMAC-SHA256 绛惧悕 |

绛惧悕鍏紡锛歚HMACSHA256(base64(header) + "." + base64(payload), secret)`銆?
浠讳綍浜烘兂绡℃敼 payload锛堟瘮濡傛妸 `role` 鏀规垚 `admin`锛夛紝閮芥病鍔炴硶閲嶆柊绠楀嚭姝ｇ‘鐨勭鍚嶏紙鍥犱负娌℃湁 secret锛夛紝鏈嶅姟鍣ㄤ竴楠岀灏卞け璐ャ€?
## 9.3 JwtUtils 宸ュ叿绫昏瑙ｏ紙鍩轰簬鐪熷疄浠ｇ爜锛?
鏈」鐩殑 `JwtUtils.java` 灏佽浜嗘墍鏈?JWT 鎿嶄綔銆傛寫鏍稿績鏂规硶璁诧細

### 閰嶇疆娉ㄥ叆

```java
@Value("${jwt.secret}")
private String secret;

@Value("${jwt.expiration}")
private Long expiration;

@Value("${jwt.refresh-expiration}")
private Long refreshExpiration;
```

浠庨厤缃枃浠讹紙鏈€缁堟潵鑷?`.env`锛夎鍙栧瘑閽ュ拰杩囨湡鏃堕棿銆?*瀵嗛挜蹇呴』鑷冲皯 32 浣?*锛屽惁鍒?HmacSHA256 浼氭嫆缁濄€?
### 鐢熸垚 Token

```java
public String generateToken(Long userId, String username, String role) {
    Map<String, Object> claims = new HashMap<>();
    claims.put("userId", userId);
    claims.put("username", username);
    claims.put("role", role);
    return createToken(claims, username, expiration);
}

private String createToken(Map<String, Object> claims, String subject, Long expirationMs) {
    SecretKey key = Keys.hmacShaKeyFor(secret.getBytes(StandardCharsets.UTF_8));
    return Jwts.builder()
            .claims(claims)
            .subject(subject)
            .issuedAt(new Date())
            .expiration(new Date(System.currentTimeMillis() + expirationMs))
            .signWith(key)
            .compact();
}
```

`claims` 灏辨槸 payload 閲岀殑鑷畾涔夊瓧娈碉紱`subject` 鏄爣鍑嗗瓧娈碉紙涓€鑸～鐢ㄦ埛鍚嶏級锛沗issuedAt` 绛惧彂鏃堕棿锛沗expiration` 杩囨湡鏃堕棿銆俙signWith(key)` 鐢?HMAC-SHA256 绛惧悕銆傛渶鍚?`.compact()` 鎷兼垚瀛楃涓层€?
### 瑙ｆ瀽涓庢牎楠?
```java
public Claims parseToken(String token) {
    SecretKey key = Keys.hmacShaKeyFor(secret.getBytes(StandardCharsets.UTF_8));
    return Jwts.parser()
            .verifyWith(key)
            .build()
            .parseSignedClaims(token)
            .getPayload();
}

public boolean isTokenExpired(String token) {
    try {
        Claims claims = parseToken(token);
        return claims.getExpiration().before(new Date());
    } catch (io.jsonwebtoken.ExpiredJwtException e) {
        return true;
    } catch (...) { ... }
}

public Long getUserIdFromToken(String token) {
    Claims claims = parseToken(token);
    return claims.get("userId", Long.class);
}
```

`parseSignedClaims` 鍐呴儴浼?*鑷姩楠岀**锛岀鍚嶉敊灏辨姏寮傚父銆傛墍浠?`parseToken` 鍙涓嶆姏寮傚父锛屽氨璇存槑 token 鏄湡鐨勩€佹湭琚鏀广€?
### 浠庤姹備腑鎻愬彇 Token

```java
public String extractTokenFromRequest(HttpServletRequest request) {
    String bearerToken = request.getHeader("Authorization");
    if (StringUtils.hasText(bearerToken) && bearerToken.startsWith("Bearer ")) {
        return bearerToken.substring("Bearer ".length());
    }
    return null;
}
```

绾﹀畾锛氬墠绔妸 token 鏀惧湪 `Authorization: Bearer <token>` 澶撮噷銆?
## 9.4 JwtAuthenticationFilter 鎷︽埅鍣紙OncePerRequestFilter锛?
姣忎釜璇锋眰閮介渶瑕佽瘑鍒?浣犳槸璋?锛岃繖涓伐浣滅敱 `JwtAuthenticationFilter` 瀹屾垚锛?
```java
@Component
public class JwtAuthenticationFilter extends OncePerRequestFilter {

    @Autowired
    private JwtUtils jwtUtils;

    @Override
    protected void doFilterInternal(HttpServletRequest request,
                                    HttpServletResponse response,
                                    FilterChain filterChain) throws ServletException, IOException {
        try {
            String token = jwtUtils.extractTokenFromRequest(request);

            if (StringUtils.hasText(token)) {
                try {
                    if (!jwtUtils.isTokenExpired(token) && !jwtUtils.isTokenRevoked(token)) {
                        Long userId = jwtUtils.getUserIdFromToken(token);
                        String username = jwtUtils.getUsernameFromToken(token);
                        String role = jwtUtils.getRoleFromToken(token);

                        UserContext userContext = new UserContext(userId, role);

                        List<GrantedAuthority> authorities = Collections.singletonList(
                                new SimpleGrantedAuthority(role != null ? "ROLE_" + role : "ROLE_USER")
                        );
                        UsernamePasswordAuthenticationToken authentication =
                                new UsernamePasswordAuthenticationToken(userContext, null, authorities);
                        authentication.setDetails(new WebAuthenticationDetailsSource().buildDetails(request));

                        SecurityContextHolder.getContext().setAuthentication(authentication);
                    }
                } catch (Exception e) {
                    logger.warn("JWT Authentication failed: " + e.getMessage());
                }
            }
        } catch (Exception e) {
            logger.warn("JWT Authentication failed");
        }
        filterChain.doFilter(request, response);
    }
}
```

瑕佺偣锛?
1. 缁ф壙 `OncePerRequestFilter`锛氫繚璇佸悓涓€涓姹傚彧璧颁竴娆★紙閬垮厤琚娆¤繃婊わ級銆?2. 浠庤姹傚ご瑙ｆ瀽 token 鈫?鏍￠獙杩囨湡 鈫?鏍￠獙榛戝悕鍗?鈫?瑙ｆ瀽 userId/role銆?3. 鎶婄敤鎴疯韩浠藉杩?`SecurityContextHolder`锛氫箣鍚庝笟鍔′唬鐮佷换浣曞湴鏂归兘鍙互閫氳繃 `SecurityUtils.getCurrentUserId()` 鎷垮埌褰撳墠鐢ㄦ埛銆?4. token 鏃犳晥涓嶆姏寮傚父锛屽彧鏄笉璁剧疆璁よ瘉淇℃伅锛岃鍚庣画 Spring Security 鍐冲畾鏄惁鎷掔粷锛?01锛夈€?5. 蹇呴』 `filterChain.doFilter(request, response)` 璁╄姹傜户缁線涓嬭蛋銆?
鈿狅笍 涓€瀹氳鍏堥獙绛惧啀鏌ラ粦鍚嶅崟锛屽惁鍒欐敾鍑昏€呭彲浠ョ敤浼€?token 鎾戠垎榛戝悕鍗曘€?
閰嶅 `SecurityUtils.java` 鎻愪緵浜嗕究鎹锋柟娉曪細

```java
public static Long getCurrentUserId() { ... }       // 寮哄埗瑕佹眰鐧诲綍
public static Long getCurrentUserIdOrNull() { ... } // 鍙┖锛屽尶鍚嶈闂篃鑳界敤
public static boolean isCurrentUserAdmin() { ... }
```

涓氬姟浠ｇ爜锛堝 `SysUserController.getById`锛夊氨杩欐牱鐢細

```java
Long currentUserId = SecurityUtils.getCurrentUserIdOrNull();
boolean isOwner = currentUserId != null && currentUserId.equals(id);
boolean isAdmin = SecurityUtils.isCurrentUserAdmin();
if (isOwner || isAdmin) {
    userVO.setEmail(user.getEmail());
    userVO.setRole(user.getRole());
}
```

## 9.5 Token 鍒锋柊鏈哄埗锛坅ccess + refresh锛?
JWT 鏈変釜涓ら毦锛?
- 杩囨湡鏃堕棿闀?鈫?涓€鏃︽硠闇插嵄瀹冲ぇ銆?- 杩囨湡鏃堕棿鐭?鈫?鐢ㄦ埛棰戠箒瑕侀噸鐧诲綍锛屼綋楠屽樊銆?
涓氱晫閫氱敤鏂规锛?*鍙?token**銆?
- **AccessToken**锛堢煭鏈燂紝姣斿 2 灏忔椂锛夛細姣忔涓氬姟璇锋眰甯﹀畠銆?- **RefreshToken**锛堥暱鏈燂紝姣斿 7 澶╋級锛氬彧鐢ㄤ簬鎹㈡柊鐨?AccessToken銆?
鏈」鐩櫥褰曞悗鍚屾椂杩斿洖涓や釜 token锛?
```java
String token = jwtUtils.generateToken(user.getId(), user.getUsername(), user.getRole());
String refreshToken = jwtUtils.generateRefreshToken(user.getId(), user.getUsername(), user.getRole());
```

鍒锋柊鎺ュ彛 `POST /user/refresh` 鐨勯€昏緫锛堣妭閫夎嚜 `SysUserController.refreshToken`锛夛細

```java
String refreshToken = authHeader.substring(7);

if (!jwtUtils.isRefreshToken(refreshToken)) {
    throw new BusinessException(401, "鏃犳晥鐨勫埛鏂癟oken");
}
if (jwtUtils.isTokenExpired(refreshToken) || jwtUtils.isTokenRevoked(refreshToken)) {
    throw new BusinessException(401, "鍒锋柊Token宸茶繃鏈熸垨宸叉挙閿€");
}

Long userId = jwtUtils.getUserIdFromToken(refreshToken);
// 鏍￠獙鐢ㄦ埛褰撳墠鐘舵€?SysUser currentUser = sysUserService.getUserById(userId);
if (currentUser == null || currentUser.getStatus() == 0 || locked) {
    throw new BusinessException(403, "...");
}

// 鎾ら攢鏃х殑 refresh token锛坮efresh token rotation锛?jwtUtils.revokeToken(refreshToken);

String newToken = jwtUtils.generateToken(userId, username, role);
String newRefreshToken = jwtUtils.generateRefreshToken(userId, username, role);
```

鈿狅笍 **Refresh Token Rotation锛堝埛鏂颁护鐗岃疆鎹級** 鏄潪甯搁噸瑕佺殑瀹夊叏瀹炶返锛氭瘡娆″埛鏂伴兘鎶婃棫 refresh token 鍔犲叆榛戝悕鍗曪紝鏂扮鍙戜竴涓€傝繖鏍峰嵆渚胯€?refresh token 琚伔璧帮紝鏀诲嚮鑰呬篃鍙兘鐢ㄤ竴娆★紝涓斾細琚悎娉曠敤鎴疯Е鍙戠殑杞崲"韪㈡帀"銆?
## 9.6 Token 榛戝悕鍗?
JWT 涓€鏃︾鍙戝氨鏃犳硶涓诲姩璁╁畠澶辨晥锛堥櫎闈炶繃鏈燂級銆備絾鐢ㄦ埛涓诲姩鐧诲嚭銆佷慨鏀瑰瘑鐮併€佽韪笅绾挎椂锛屽繀椤昏兘鎾ら攢 token銆傛湰椤圭洰鐢?榛戝悕鍗?瀹炵幇锛?
```java
private final Set<String> tokenBlacklist = ConcurrentHashMap.newKeySet();

public void revokeToken(String token) {
    if (token == null) return;
    try {
        parseToken(token); // 鍏堥獙绛?        if (!isTokenExpired(token)) {
            tokenBlacklist.add(token);
        }
    } catch (Exception e) {
        // 鏃犳晥 token 涓嶅姞鍏?    }
}

public boolean isTokenRevoked(String token) {
    return tokenBlacklist.contains(token);
}

public void cleanExpiredTokens() {
    tokenBlacklist.removeIf(token -> {
        try { return isTokenExpired(token); }
        catch (Exception e) { return true; }
    });
}
```

娉ㄦ剰锛?
1. `ConcurrentHashMap.newKeySet()` 鎻愪緵绾跨▼瀹夊叏鐨?Set銆?2. `revokeToken` **蹇呴』鍏堥獙绛?*锛氶伩鍏嶆敾鍑昏€呯敤浼€?token 鎾戠垎鍐呭瓨銆?3. `cleanExpiredTokens()` 鐢?`JwtSchedulerConfig` 瀹氭椂璋冨害锛岄伩鍏嶉粦鍚嶅崟鏃犻檺鑶ㄨ儉銆?4. 鈿狅笍 褰撳墠鏄唴瀛樻柟妗堬紝鍙敮鎸佸崟瀹炰緥銆傜敓浜х幆澧冨瀹炰緥閮ㄧ讲鏃讹紝搴旀崲鎴?**Redis SET + TTL**锛屾湰椤圭洰婧愮爜娉ㄩ噴閲屼篃鏄庣‘鍐欎簡杩欑偣 TODO銆?
## 9.7 瀹夊叏娉ㄦ剰浜嬮」锛堝姟蹇呰浣忥級

鏈€鍚庢€荤粨涓€涓?JWT 瀹炴垬蹇呴』閬靛畧鐨勫畨鍏ㄥ噯鍒欙細

1. **瀵嗛挜锛坰ecret锛夎嚦灏?32 浣嶄笖蹇呴』淇濆瘑**銆傛湰椤圭洰閫氳繃 `.env` 鏂囦欢绠＄悊锛宍.gitignore` 蹇界暐锛?*姘歌繙涓嶈鎻愪氦鍒?Git**銆?2. **蹇呴』鏍￠獙绛惧悕**锛氳嚜鍔ㄧ敱 `parseSignedClaims` 瀹屾垚锛屼笉瑕佽嚜宸卞啓"鍙?base64 瑙ｇ爜涓嶉獙绛?鐨勪唬鐮併€?3. **payload 涓嶈兘瀛樻晱鎰熶俊鎭?*锛氬瘑鐮併€侀摱琛屽崱銆佽韩浠借瘉绛夌粷瀵逛笉鏀俱€?4. **璁剧疆鍚堢悊鐨勮繃鏈熸椂闂?*锛歛ccess 1~2 灏忔椂銆乺efresh 7~30 澶┿€?5. **蹇呴』鏈夋挙閿€鏈哄埗**锛氶粦鍚嶅崟 / Redis / 鏁版嵁搴?token 琛ㄣ€?6. **鐢?HTTPS 浼犺緭**锛欻TTP 涓?token 鍦ㄧ綉缁滀笂瑁稿锛屼細琚腑闂翠汉鎴幏銆?7. **鎷掔粷寮辩畻娉?*锛氫笉瑕佺敤 `alg: none`銆佷笉瑕佺敤 RS256 鏃舵妸鍏挜褰撳绉板瘑閽ワ紙鍘嗗彶涓婅憲鍚嶆紡娲烇級銆?8. **鐧诲綍澶辫触瑕侀攣璐﹀彿**锛氭湰椤圭洰瀹炵幇浜?5 娆″け璐ラ攣 15 鍒嗛挓锛屼笖鐢ㄦ暟鎹簱鍘熷瓙 SQL 闃插苟鍙戠粫杩囥€?9. **淇敼瀵嗙爜銆佺櫥鍑哄悗鎾ら攢鏃?token**锛氶伩鍏嶆硠闇茬殑 token 缁х画鍙敤銆?10. **鐢熶骇鐜鐢?Redis 瀛橀粦鍚嶅崟**锛氬唴瀛樻柟妗堝瀹炰緥涓嶄竴鑷淬€?
### 涓€鍙ヨ瘽鎬荤粨
> JWT 鏄?甯︾鍚嶇殑韬唤璇?锛屾湰椤圭洰鐢?access + refresh 鍙?token銆佽疆鎹€侀粦鍚嶅崟銆佺櫥褰曢攣銆丠TTPS銆丆ORS 鐧藉悕鍗曠瓑缁勫悎鎷筹紝鎶婃棤鐘舵€佽璇佸仛寰楁棦濂界敤鍙堝畨鍏ㄣ€?
---

# 绗簩閮ㄥ垎灏忕粨

鍒拌繖閲岋紝妗嗘灦鏍稿績鐨勫洓澶ф敮鏌变綘閮藉凡缁忔帉鎻★細

1. **MyBatis Plus**锛氱敤 `@TableName / @TableId / @TableLogic / @TableField` 鎶婄被鏄犲皠鍒拌〃锛孊aseMapper 鐧藉珫 CRUD锛屽垎椤点€佽嚜鍔ㄥ～鍏呫€侀€昏緫鍒犻櫎涓€閿紑鍚€?2. **鍒嗗眰鏋舵瀯**锛欳ontroller / Service / Mapper / Entity 鍚勫徃鍏惰亴锛孌TO 鎺ュ墠绔€乂O 缁欏墠绔紝IoC 瀹瑰櫒鎶婂畠浠覆璧锋潵銆?3. **缁熶竴鍝嶅簲涓庡紓甯?*锛歚Result` 鍖呰繑鍥炲€笺€乣BusinessException` 鎶涗笟鍔￠敊銆乣GlobalExceptionHandler` 鍏ㄥ眬鍏滃簳锛屽墠鍚庣濂戠害娓呮櫚銆?4. **Spring Security + JWT**锛欱Crypt 鍔犲瘑瀵嗙爜銆佽繃婊ゅ櫒瑙ｆ瀽 token銆佸弻 token 鍒锋柊銆侀粦鍚嶅崟鎾ら攢銆丆ORS 鐧藉悕鍗曘€佺櫥褰曢攣瀹氾紝鏋勬垚涓€濂椾紒涓氱骇鐨勫畨鍏ㄩ槻绾裤€?
鎺ヤ笅鏉ョ殑绗笁閮ㄥ垎灏嗚繘鍏?涓氬姟瀹炴垬"锛氫粠涓€涓湡瀹炵殑"鍙戝竷鏂囩珷 / 鐐硅禐 / 璇勮 / 鍏虫敞 / 閫氱煡 / 鍦堝瓙"鍔熻兘锛屾妸鍓嶉潰瀛︾殑鎵€鏈夌煡璇嗘弶鍦ㄤ竴璧凤紝鍋氬嚭鍙繍琛岀殑鎴愬搧銆?
---

> 鍏ㄧ珷鑺傞厤濂楃湡瀹炰唬鐮佸潎浣嶄簬鏈」鐩粨搴擄細
> - GitHub锛歨ttps://github.com/Xinghe-0203/Campus_Blog
> - 鍏抽敭鏂囦欢锛歚Result.java`銆乣BusinessException.java`銆乣GlobalExceptionHandler.java`銆乣MybatisPlusConfig.java`銆乣MyMetaObjectHandler.java`銆乣SecurityConfig.java`銆乣JwtAuthenticationFilter.java`銆乣JwtUtils.java`銆乣SecurityUtils.java`銆乣SysUser.java`銆乣BlogPost.java`銆乣UserRegisterRequest.java`銆乣SysUserMapper.java`銆乣SysUserService.java`銆乣SysUserServiceImpl.java`銆乣SysUserController.java`銆?# 銆奐ava Spring Boot 闆跺熀纭€瀹屾暣瀛︿範鎵嬪唽銆?
## 绗笁閮ㄥ垎 椤圭洰瀹炴垬锛氫竴琛岃璇绘噦鏍″洯鍗氬璁哄潧

> 鏈儴鍒嗗熀浜庣湡瀹為」鐩?`edu_project`锛坴1.34锛夌殑婧愮爜锛屾寜鐓?闇€姹?鈫?琛?鈫?DTO 鈫?Service 鈫?Controller"鐨勯『搴忥紝鎶婂叚澶т笟鍔℃ā鍧楁媶缁欓浂鍩虹璇昏€呯湅銆?> 闃呰鏈儴鍒嗗墠锛岃纭繚宸茬粡鎺屾彙绗簩閮ㄥ垎涓叧浜?Spring Boot銆丮yBatis Plus銆丼pring Security 鐨勫叆闂ㄧ煡璇嗐€?
---

# 绗?10 绔?鐢ㄦ埛妯″潡瀹炴垬

鐢ㄦ埛妯″潡鏄暣涓鍧涚殑鍏ュ彛銆傛墍鏈?鎴?鎵嶈兘鍋氱殑浜嬧€斺€斿彂鏂囩珷銆佺偣璧炪€佸叧娉ㄣ€佹敹钘忊€斺€旈兘渚濊禆涓€浠朵簨锛?*绯荤粺鐭ラ亾褰撳墠璇锋眰鏄皝鍙戠殑**銆傛湰绔犳垜浠氨涓€琛岃璇绘噦瀹冦€?
## 10.1 鐢ㄦ埛琛?sys_user 瀛楁瑙ｈ

鏍″洯鍗氬鐨勭敤鎴蜂俊鎭叏閮ㄤ繚瀛樺湪 `sys_user` 琛ㄤ腑銆傝鎴戜滑鍏堢湅鐪嬭繖寮犺〃閮芥湁鍝簺瀛楁锛?
| 瀛楁鍚?| 绫诲瀷 | 鍚箟 | 璁捐瑕佺偣 |
| --- | --- | --- | --- |
| `id` | BIGINT | 涓婚敭锛岃嚜澧?| 鍏ㄥ眬鍞竴韬唤鏍囪瘑 |
| `username` | VARCHAR(50) | 鐧诲綍鐢ㄦ埛鍚?| **鍞竴绱㈠紩**锛岀姝㈤噸澶?|
| `password` | VARCHAR(100) | 鍔犲瘑鍚庣殑瀵嗙爜 | BCrypt 鎽樿锛屾案涓嶆槑鏂囧瓨鍌?|
| `nickname` | VARCHAR(50) | 鏄电О锛堝叕寮€灞曠ず锛?| 娌″～灏辩敤 username 鍏滃簳 |
| `email` | VARCHAR(100) | 閭 | **鍞竴绱㈠紩**锛屽彲绌?|
| `avatar` | VARCHAR(255) | 澶村儚 URL | 榛樿绌猴紝鍓嶇鍙樉绀哄崰浣嶅浘 |
| `role` | VARCHAR(20) | 瑙掕壊锛歚user` / `admin` | 鐢ㄤ簬 Spring Security 鏉冮檺鍒ゆ柇 |
| `status` | TINYINT | 璐﹀彿鐘舵€侊細1 姝ｅ父锛? 绂佺敤 | 绠＄悊鍛樺彲涓€閿皝绂?|
| `login_fail_count` | INT | 杩炵画鐧诲綍澶辫触娆℃暟 | 闃茬垎鐮存牳蹇?|
| `lock_until` | DATETIME | 閿佸畾鎴鏃堕棿 | 澶辫触瓒?5 娆￠攣 15 鍒嗛挓 |
| `follower_count` | INT | 绮変笣鏁?| 鍐椾綑瀛楁锛岄伩鍏嶆瘡娆?COUNT |
| `following_count` | INT | 鍏虫敞鏁?| 鍚屼笂 |
| `create_time` / `update_time` | DATETIME | 鍒涘缓/鏇存柊鏃堕棿 | MyBatis Plus 鑷姩濉厖 |
| `is_deleted` | TINYINT | 閫昏緫鍒犻櫎鏍囪 | 1 鍒犻櫎锛? 姝ｅ父 |

馃挕 **璁捐鍐崇瓥**锛氭妸"绮変笣鏁?杩欑缁熻鍊艰惤鍦板瓨鍌ㄨ€屼笉鏄瘡娆?`SELECT COUNT(*)`銆傝繖鍙?鍐椾綑瀛楁"銆備唬浠锋槸姣忔鍏虫敞/鍙栧叧闇€瑕佸仛涓€娆?`UPDATE`锛屼絾鐩稿姣忔鍒锋柊涓婚〉閮芥墽琛?COUNT 鏉ヨ锛屾€т环姣旀瀬楂樸€?
鈿狅笍 **鏄撻敊鐐?*锛歚is_deleted` 瀛楁涓嶈兘鐩存帴 `WHERE is_deleted = 0`锛孧yBatis Plus 鐨?`@TableLogic` 娉ㄨВ浼氳嚜鍔ㄥ姞杩欎釜鏉′欢锛屾墜鍐欏弽鑰屽鏄撳啓鍙屽眰銆?
## 10.2 SysUser 瀹炰綋绫伙紙@TableLogic銆丂JsonIgnore 闃插瘑鐮佹硠闇诧級

瀹炰綋绫绘槸 Java 涓栫晫瀵规暟鎹簱琛岀殑闀滃儚锛?
```java
@Data
@TableName("sys_user")
public class SysUser {

    @TableId(value = "id", type = IdType.AUTO)
    private Long id;

    private String username;

    @JsonIgnore   // 鈿狅笍 鍏抽敭锛氬簭鍒楀寲涓?JSON 鏃跺拷鐣ュ瘑鐮佸瓧娈?    private String password;

    private String nickname;
    private String email;
    private String avatar;
    private String role;
    private Integer status;

    private Integer loginFailCount;
    private LocalDateTime lockUntil;

    private Integer followerCount;
    private Integer followingCount;

    @TableField(fill = FieldFill.INSERT)
    private LocalDateTime createTime;

    @TableField(fill = FieldFill.INSERT_UPDATE)
    private LocalDateTime updateTime;

    @TableLogic   // 閫昏緫鍒犻櫎鏍囪
    private Integer isDeleted;
}
```

閫愯瑙ｈ锛?
- `@TableName("sys_user")`锛氬憡璇?MyBatis Plus锛岃繖涓?Java 绫诲搴旀暟鎹簱鐨?`sys_user` 琛ㄣ€?- `@TableId(type = IdType.AUTO)`锛氫富閿敱鏁版嵁搴撹嚜澧炵敓鎴愶紝鏂板鏃朵笉瑕佽嚜宸卞啓 id銆?- `@JsonIgnore`锛歋pring MVC 鎶婂璞″簭鍒楀寲鎴?JSON 杩斿洖鍓嶇鏃讹紝璺宠繃璇ュ瓧娈碘€斺€?*杩欐槸闃叉瀵嗙爜娉勯湶缁欏墠绔渶绠€鍗曚篃鏈€鏈夋晥鐨勪竴閬撻椄闂?*銆?- `@TableField(fill = ...)`锛氶厤鍚?`MyMetaObjectHandler`锛岃嚜鍔ㄥ～鍏呮椂闂淬€侷NSERT 鏃跺～ `createTime`锛孶PDATE 鏃跺悓鏃跺～ `updateTime`銆?- `@TableLogic`锛氳〃绀鸿繖鏄€昏緫鍒犻櫎瀛楁銆傝皟鐢?`removeById` 鏃朵笉浼氱湡鐨勬墽琛?DELETE锛岃€屾槸 UPDATE 鎶?`is_deleted` 鏀逛负 1銆?
鈿狅笍 **鏂版墜鏈€鐖辩姱鐨勯敊**锛氱洿鎺ユ妸 `SysUser` 褰撳搷搴旇繑鍥炪€傚嵆渚挎湁 `@JsonIgnore`锛屾湭鏉ユ煇娆￠渶姹傛敼鍔ㄥ繕浜嗘墦杩欎釜娉ㄨВ锛屽瘑鐮佸氨瑁稿鍒板墠绔簡銆?*鎵€浠ラ」鐩噷涓撻棬鏈変竴涓?`UserVO`锛堣鍥惧璞★級绫荤敤鏉ヨ繑鍥?*锛屼粠婧愬ご鏉滅粷淇℃伅澶栨硠銆?
## 10.3 娉ㄥ唽鎺ュ彛锛欴TO 鏍￠獙 鈫?鍞竴鎬ф鏌?鈫?BCrypt 鈫?鐢ㄦ埛鏋氫妇闃叉姢

鎴戜滑浠?`SysUserController#register` 鐪嬭捣锛?
```java
@PostMapping("/register")
public Result<UserRegisterResponse> register(
        @Valid @RequestBody UserRegisterRequest request) {
    UserRegisterResponse response = sysUserService.register(request);
    return Result.success(response);
}
```

- `@RequestBody`锛氭妸璇锋眰浣撻噷鐨?JSON 鍙嶅簭鍒楀寲鎴?Java 瀵硅薄銆?- `@Valid`锛氳Е鍙?Bean Validation銆傛牎楠屼笉閫氳繃浼氳 `GlobalExceptionHandler` 鎹曡幏骞惰繑鍥?400銆?
DTO锛堣姹傚璞★級绫讳技锛?
```java
@Data
public class UserRegisterRequest {
    @NotBlank(message = "鐢ㄦ埛鍚嶄笉鑳戒负绌?)
    @Size(min = 3, max = 20)
    private String username;

    @NotBlank(message = "瀵嗙爜涓嶈兘涓虹┖")
    @Size(min = 8, max = 50)
    private String password;

    @Size(max = 50)
    private String nickname;

    @Email
    private String email;
}
```

杩涘叆 Service 灞傚氨寮€濮嬪仛"纭鍒?锛?
```java
@Override
@Transactional(rollbackFor = Exception.class)
public UserRegisterResponse register(UserRegisterRequest request) {
    // 1. 瀵嗙爜寮哄害鏍￠獙锛氳嚦灏?8 浣?+ 鍖呭惈澶у皬鍐?鏁板瓧/鐗规畩瀛楃浠绘剰 3 绫?    String password = request.getPassword();
    int categories = 0;
    if (password.matches(".*[A-Z].*")) categories++;
    if (password.matches(".*[a-z].*")) categories++;
    if (password.matches(".*\\d.*")) categories++;
    if (password.matches(".*[!@#$%^&*()_+...].*")) categories++;
    if (categories < 3) {
        throw new BusinessException(400,
            "瀵嗙爜蹇呴』鍖呭惈澶у皬鍐欏瓧姣嶃€佹暟瀛楁垨鐗规畩瀛楃涓殑鑷冲皯3绉?);
    }

    // 2. 鐢ㄦ埛鍚嶅敮涓€鎬?鈥斺€斺€?娉ㄦ剰閿欒淇℃伅锛?    if (this.count(new LambdaQueryWrapper<SysUser>()
            .eq(SysUser::getUsername, request.getUsername())) > 0) {
        throw new BusinessException(400, "娉ㄥ唽澶辫触锛岃绋嶅悗閲嶈瘯");
    }

    // 3. 閭鍞竴鎬?    if (request.getEmail() != null && !request.getEmail().isEmpty()) {
        if (this.count(new LambdaQueryWrapper<SysUser>()
                .eq(SysUser::getEmail, request.getEmail())) > 0) {
            throw new BusinessException(400, "娉ㄥ唽澶辫触锛岃绋嶅悗閲嶈瘯");
        }
    }

    // 4. 鍒涘缓鐢ㄦ埛瀵硅薄
    SysUser user = new SysUser();
    user.setUsername(request.getUsername());
    user.setPassword(passwordEncoder.encode(request.getPassword())); // BCrypt
    user.setNickname(request.getNickname() != null
            ? request.getNickname() : request.getUsername());
    user.setEmail(request.getEmail());
    user.setRole("user");
    user.setStatus(1);
    user.setLoginFailCount(0);

    // 5. 鍏ュ簱锛堟崟鑾峰苟鍙戝満鏅笅鐨勫敮涓€绾︽潫鍐茬獊锛?    try {
        this.save(user);
    } catch (DuplicateKeyException e) {
        throw new BusinessException(400, "娉ㄥ唽澶辫触锛岃绋嶅悗閲嶈瘯");
    }

    return new UserRegisterResponse(user.getId(), user.getUsername());
}
```

鍏抽敭鐐归€愪竴灞曞紑锛?
馃挕 **涓轰粈涔堥敊璇俊鎭姝ゆā绯婏紵**
娉ㄦ剰绗?2/3 姝ョ殑閿欒閮芥槸"娉ㄥ唽澶辫触锛岃绋嶅悗閲嶈瘯"锛?*涓嶆槸**"鐢ㄦ埛鍚嶅凡瀛樺湪""閭宸叉敞鍐?銆傝繖鍙?*鐢ㄦ埛鏋氫妇闃叉姢锛圲ser Enumeration Protection锛?*锛氬鏋滅郴缁熻€佽€佸疄瀹炲憡璇夋敾鍑昏€?閭宸叉敞鍐?锛屾敾鍑昏€呭氨鑳芥壒閲忕寽鍑哄摢浜涢偖绠卞湪浣犵珯鐐逛笂鏈夎处鍙凤紝鍐嶅幓瀵瑰簲鐨勯偖浠惰处鍙峰皾璇曠垎鐮淬€?
馃挕 **涓轰粈涔堝厛 count 妫€鏌ワ紝鍚庡張瑕?try DuplicateKeyException锛?*
涓ら亾闃茬嚎缂轰竴涓嶅彲锛?1. 鍗曠嚎绋嬫椂 count 妫€鏌ュ氨澶熶簡锛屼絾**涓や釜璇锋眰鍚屾椂娉ㄥ唽鍚屼竴涓敤鎴峰悕鏃?*锛屽畠浠兘鑳介€氳繃 count 妫€鏌ワ紝鐒跺悗涓や釜閮藉線鏁版嵁搴撴彃銆?2. 鏁版嵁搴撶殑鍞竴绱㈠紩鏄粓鏋侀槻绾匡紝蹇呯劧鎶?`DuplicateKeyException`銆傛垜浠崟鑾峰苟杩斿洖鍙嬪ソ鎻愮ず銆?
馃挕 **BCrypt 鐨勫己搴?12 鏄粈涔堬紵**
`BCryptPasswordEncoder` 榛樿 strength 鏄?10锛屾湰椤圭洰璁句负 12銆傛瘡鍔?1 璁＄畻鏃堕棿缈诲€嶁€斺€斿嵆渚挎暟鎹簱琚嫋搴擄紝鏀诲嚮鑰呮瘡灏濊瘯涓€涓瘑鐮佷篃瑕?200 澶氭绉掞紝1 浜挎缁勫悎闇€瑕佺害 240 澶╋紝瓒充互璁╃敤鎴峰湪瀵熻鍚庢敼瀵嗙爜銆?
鈿狅笍 **`@Transactional(rollbackFor = Exception.class)`** 蹇呬笉鍙皯銆係pring 榛樿鍙 `RuntimeException` 鍥炴粴锛屼絾淇濋櫓璧疯鎶婃墍鏈?`Exception` 閮界撼鍏ュ洖婊氭潯浠讹紝閬垮厤鏌愪簺 Checked Exception 璁?鍗婃垚鍝佽处鍙?鐣欏湪琛ㄩ噷銆?
## 10.4 鐧诲綍鎺ュ彛锛氳处鎴烽攣瀹氭鏌?鈫?瀵嗙爜楠岃瘉 鈫?JWT + refreshToken 杩斿洖

鐧诲綍鏄竴娈甸潪甯稿井濡欑殑浠ｇ爜锛氫綘瑕佹妸"鐢ㄦ埛浣撻獙濂?鍜?闃茬垎鐮?涓や釜闇€姹傛嫥鍦ㄤ竴璧枫€?
```java
@Override
@Transactional(rollbackFor = Exception.class)
public UserLoginResponse login(UserLoginRequest request) {
    // 1. 鍙栧嚭鐢ㄦ埛
    SysUser user = this.getOne(new LambdaQueryWrapper<SysUser>()
            .eq(SysUser::getUsername, request.getUsername()));
    if (user == null) {
        throw new BusinessException(401, "鐢ㄦ埛鍚嶆垨瀵嗙爜閿欒");
    }

    // 2. 閿佸畾妫€鏌ワ紙鍏堜簬瀵嗙爜鏍￠獙锛侊級
    if (user.getLockUntil() != null
            && user.getLockUntil().isAfter(LocalDateTime.now())) {
        throw new BusinessException(403, "鐧诲綍澶辫触娆℃暟杩囧锛岃绋嶅悗鍐嶈瘯");
    }

    // 3. 鐘舵€佹鏌?    if (user.getStatus() == 0) {
        throw new BusinessException(403, "璐﹀彿宸茶绂佺敤");
    }

    // 4. 瀵嗙爜鏍￠獙
    if (!passwordEncoder.matches(request.getPassword(), user.getPassword())) {
        // 4.1 澶辫触鏃跺師瀛愬湴绱姞澶辫触娆℃暟
        handleLoginFailAtomic(user.getId());

        // 4.2 閲嶆柊鏌ヨ鎷垮埌鏈€鏂伴攣瀹氱姸鎬?        SysUser updated = this.getById(user.getId());
        if (updated.getLockUntil() != null
                && updated.getLockUntil().isAfter(LocalDateTime.now())) {
            throw new BusinessException(403, "鐧诲綍澶辫触娆℃暟杩囧锛岃绋嶅悗鍐嶈瘯");
        }
        throw new BusinessException(401, "鐢ㄦ埛鍚嶆垨瀵嗙爜閿欒");
    }

    // 5. 鐧诲綍鎴愬姛锛岄噸缃鏁?    if (user.getLoginFailCount() == null || user.getLoginFailCount() > 0) {
        user.setLoginFailCount(0);
        user.setLockUntil(null);
        this.updateById(user);
    }

    // 6. 鐢熸垚鍙?Token
    String token = jwtUtils.generateToken(
            user.getId(), user.getUsername(), user.getRole());
    String refreshToken = jwtUtils.generateRefreshToken(
            user.getId(), user.getUsername(), user.getRole());

    return new UserLoginResponse(user.getId(), user.getUsername(),
            user.getNickname(), user.getAvatar(), token, refreshToken);
}
```

閫愰」鎷嗚В锛?
馃挕 **椤哄簭寰堝叧閿?*锛氬厛鐪嬮攣锛屽啀鐪嬪瘑鐮併€?濡傛灉鍏堟牎楠屽瘑鐮併€佸啀鍒ゆ柇鏄惁閿佸畾锛屾敾鍑昏€呮瘡娆′粛鐒朵細娑堣€椾竴娆?`passwordEncoder.matches`锛堢害 250ms锛夛紝浣嗘洿绯熺殑鏄細璁?宸查攣瀹氫絾浠嶅彲缁х画鎻愪氦瀵嗙爜"鈥斺€旈攣瀹氬氨褰㈠悓铏氳銆傛湰椤圭洰椤哄簭淇濊瘉锛氳处鍙蜂竴鏃﹂攣瀹氾紝鍚庣画璇锋眰浼氳蹇€熸嫤鎴紙鏃?BCrypt 璁＄畻锛夛紝淇濇姢鏁版嵁搴撳帇鍔涖€?
馃挕 **閿欒淇℃伅"鐢ㄦ埛鍚嶆垨瀵嗙爜閿欒"**鈥斺€斿悓鏍锋槸鐢ㄦ埛鏋氫妇闃叉姢锛氫笉鍛婅瘔鏀诲嚮鑰呯┒绔熸槸鐢ㄦ埛鍚嶉敊杩樻槸瀵嗙爜閿欍€?
馃挕 **refreshToken 鏄粈涔堬紵**
- `token`锛坅ccessToken锛夛細1 灏忔椂鏈夋晥鏈燂紝姣忔璇锋眰甯︿笂銆?- `refreshToken`锛? 澶╂湁鏁堟湡锛?*鍙?*缁?`/user/refresh` 绔偣鐢ㄣ€傚綋 accessToken 杩囨湡鏃讹紝鍓嶇鎷?refreshToken 鍘绘崲涓€瀵规柊鐨?token銆傝繖鏍锋棦鑳芥帶鍒?accessToken 鐭敓鍛藉懆鏈燂紙琚洍涔熷緢蹇け鏁堬級锛屽張涓嶉渶瑕佽鐢ㄦ埛姣忓皬鏃堕噸鏂扮櫥褰曘€?
## 10.5 鐧诲綍澶辫触閿佸畾锛? 娆″け璐ラ攣 15 鍒嗛挓锛?
`handleLoginFailAtomic` 璋冪敤浜?mapper 涓殑涓€娈佃嚜瀹氫箟 SQL锛?
```xml
<update id="incrementLoginFailCount">
    UPDATE sys_user
    SET login_fail_count = login_fail_count + 1,
        lock_until = CASE
            WHEN login_fail_count + 1 >= #{maxFailCount}
            THEN DATE_ADD(NOW(), INTERVAL #{lockMinutes} MINUTE)
            ELSE lock_until
        END
    WHERE id = #{userId}
</update>
```

涓轰粈涔堢敤涓€鏉?SQL 瀹屾垚鎵€鏈変簨锛?
鈿狅笍 **閿欒绀鸿寖**锛?```java
SysUser u = userMapper.selectById(id);
u.setLoginFailCount(u.getLoginFailCount() + 1);
if (u.getLoginFailCount() >= 5) {
    u.setLockUntil(LocalDateTime.now().plusMinutes(15));
}
userMapper.updateById(u);
```

杩欐浠ｇ爜鐪嬩技娌￠棶棰橈紝浣嗗湪骞跺彂涓嬶細涓や釜澶辫触璇锋眰鍚屾椂璇诲埌 `loginFailCount = 4`锛岄兘鍔?1 鍐欏洖 5锛屾渶缁堝€间粛鏄?5鈥斺€旇鏁板亸灏戜簡 1銆傛垜浠敤涓€鏉?SQL 璁╂暟鎹簱鑷繁 + 1 + 鍒ゆ柇锛屼竴鍘熷瓙鎼炲畾锛屾潨缁濈珵鎬併€?
馃挕 **缁嗚妭**锛氳閿佸畾鍚庯紝`lockUntil > now()` 灏辩洿鎺ユ嫤鎴紝杩炲瘑鐮佹牎楠岄兘涓嶅仛鈥斺€旇繖灏辨槸鍓嶉潰寮鸿皟"閿佸畾妫€鏌ュ厛浜庡瘑鐮佹牎楠?鐨勫師鍥犮€?
## 10.6 淇敼瀵嗙爜 + 鐢ㄦ埛鎼滅储

淇敼瀵嗙爜鍜屾敞鍐屾祦绋嬪嚑涔庡绉帮紝澶氫簡涓€姝?楠岃瘉鏃у瘑鐮?锛?
```java
public void changePassword(Long userId, String oldPassword, String newPassword) {
    SysUser user = this.getById(userId);
    if (user == null) throw new BusinessException(404, "鐢ㄦ埛涓嶅瓨鍦?);

    if (!passwordEncoder.matches(oldPassword, user.getPassword())) {
        throw new BusinessException(400, "鏃у瘑鐮佷笉姝ｇ‘");
    }

    // 澶嶆潅搴︽牎楠屽悓娉ㄥ唽锛堢暐锛?
    user.setPassword(passwordEncoder.encode(newPassword));
    this.updateById(user);
}
```

鈿狅笍 淇敼瀵嗙爜鍚庣悊璁轰笂搴旇鎶婂凡绛惧彂鐨?token 鍔犲叆榛戝悕鍗曪紝寮哄埗鍏跺畠璁惧閲嶆柊鐧诲綍銆傛湰椤圭洰鐨?JWT 榛戝悕鍗曟満鍒跺彲浠ュ仛鍒拌繖鐐癸紙鍦ㄧ浜岄儴鍒嗚杩囷級锛岀敓浜т腑鍔″繀鍚敤銆?
鐢ㄦ埛鎼滅储灏辨槸涓€涓畝鍗曠殑鍒嗛〉 + 妯＄硦鏌ヨ锛?
```java
public IPage<UserVO> searchUsers(UserSearchRequest request) {
    Page<SysUser> page = new Page<>(request.getPage(), request.getPageSize());
    LambdaQueryWrapper<SysUser> wrapper = new LambdaQueryWrapper<>();

    if (StringUtils.hasText(request.getKeyword())) {
        String kw = request.getKeyword().trim();
        wrapper.and(w -> w.like(SysUser::getUsername, kw)
                .or().like(SysUser::getNickname, kw));
    }
    wrapper.orderByDesc(SysUser::getCreateTime);

    return this.page(page, wrapper).convert(this::convertToUserVO);
}
```

馃挕 杩欓噷 `convertToUserVO` 浼氭竻鎺夊瘑鐮佸瓧娈碉紝鍙暀涓嬪睍绀虹敤鐨勫睘鎬э紝鍐嶆璐交"姘歌繙涓嶈繑鍥?SysUser"鐨勭邯寰嬨€?
---

# 绗?11 绔?鏂囩珷妯″潡瀹炴垬

## 11.1 blog_post 琛ㄧ粨鏋?
| 瀛楁 | 绫诲瀷 | 璇存槑 |
| --- | --- | --- |
| id | BIGINT | 涓婚敭 |
| user_id | BIGINT | 浣滆€匢D锛團K锛?|
| title | VARCHAR(200) | 鏍囬 |
| summary | VARCHAR(500) | 鎽樿锛堟墜鍔ㄦ垨鑷姩鎴彇锛?|
| content | TEXT | 姝ｆ枃锛堟渶闀?50000 瀛楃锛?|
| category | VARCHAR(50) | 鍒嗙被锛堥粯璁?榛樿鍒嗙被"锛?|
| view_count | INT | 闃呰鏁?|
| like_count | INT | 鐐硅禐鏁?|
| comment_count | INT | 璇勮鏁?|
| collect_count | INT | 鏀惰棌鏁?|
| status | TINYINT | 1 宸插彂甯?/ 0 鑽夌 / 2 涓嬫灦 |
| create_time / update_time | DATETIME | 鏃堕棿鎴?|
| is_deleted | TINYINT | 閫昏緫鍒犻櫎 |

馃挕 鍥涗釜 `count` 瀛楁閮芥槸鍐椾綑瀛楁銆傚師鍒欏悓 `sys_user` 鐨勭矇涓濇暟锛氬啓鍏ユ鏁拌繙灏忎簬璇诲彇娆℃暟锛屾妸缁熻钀藉湴鑳芥崲鏉ュ法澶ф€ц兘浼樺娍銆?
鈿狅笍 杩欎簺 count 涓嶈兘鐢?Java 灞備唬鐮?`++`銆乣--`锛?*蹇呴』**閫氳繃 `UPDATE blog_post SET like_count = like_count + 1 WHERE id = ?` 鐢辨暟鎹簱鍋氬姞娉曪紝閬垮厤骞跺彂涓㈠け鏇存柊銆?
## 11.2 鍙戝竷鏂囩珷锛圖TO + 鏍囩鍏宠仈 + XSS 杩囨护锛?
`BlogPostController#createPost`锛?
```java
@PostMapping
public Result<Long> createPost(@Valid @RequestBody PostCreateRequest request) {
    Long userId = SecurityUtils.getCurrentUserIdOrNull();
    if (userId == null) throw new BusinessException(401, "璇峰厛鐧诲綍");
    Long postId = blogPostService.createPost(request, userId);
    return Result.success(postId);
}
```

DTO `PostCreateRequest` 鍖呭惈锛歵itle銆乻ummary銆乧ontent銆乧ategory銆乼agIds锛圠ist<Long>锛夈€?
Service 鍐呴儴鏈€鍏抽敭鐨勪袱姝ワ細

1. **XSS 杩囨护**锛?
```java
String sanitizedTitle   = htmlSanitizer.sanitizeRichText(request.getTitle());
String sanitizedSummary = htmlSanitizer.sanitizeRichText(request.getSummary());
String sanitizedContent = htmlSanitizer.sanitizeRichText(request.getContent());
```

`HtmlSanitizer` 鍐呴儴鐢?Jsoup 鐨勭櫧鍚嶅崟锛氬瘜鏂囨湰鍏佽 `<p>`/`<strong>`/`<a>` 绛夊畨鍏ㄦ爣绛撅紝鍓ョ `<script>`/`onerror=` 绛夊嵄闄╁睘鎬с€俢ategory 鐢ㄦ洿涓ユ牸鐨?`sanitizePlainText` 瀹屽叏鍓ョ HTML銆?
2. **鏍囩鍏宠仈**锛?
```java
this.save(post);   // 鍏堜繚瀛樻枃绔犳嬁鍒?id
if (request.getTagIds() != null && !request.getTagIds().isEmpty()) {
    savePostTags(post.getId(), request.getTagIds());
}
```

`blog_post_tag` 鏄腑闂磋〃锛屼富閿?(postId, tagId)銆俙savePostTags` 鍐呴儴寰幆 insert銆?
鈿狅笍 **蹇呴』鍏堜繚瀛樻枃绔犳嬁鍒拌嚜澧?id**锛屽啀鍐欎腑闂磋〃銆傛柊鎵嬪父鐘殑閿欙細鍦?save 涔嬪墠灏辨嬁 id 鐢紝缁撴灉 id 杩樻槸 null銆?
馃挕 **鏍￠獙鏍囩 ID 鏈夋晥鎬?*锛氶」鐩皟鐢?`validateTagIds` 妫€鏌ヤ紶鍏ョ殑 tagId 閮界湡瀹炲瓨鍦紝閬垮厤鑴忔暟鎹€?
## 11.3 鏂囩珷鍒楄〃锛堝垎椤?+ 澶氭潯浠?LambdaQueryWrapper锛?
```java
public IPage<PostListResponse> getPostList(PostQueryRequest request) {
    Page<BlogPost> page = new Page<>(request.getPage(), request.getPageSize());

    LambdaQueryWrapper<BlogPost> wrapper = new LambdaQueryWrapper<>();
    wrapper.eq(BlogPost::getStatus, 1)         // 宸插彂甯?           .ne(BlogPost::getIsDeleted, 1);     // 鎺掗櫎宸插垹闄?
    if (StringUtils.hasText(request.getKeyword())) {
        wrapper.and(w -> w.like(BlogPost::getTitle, request.getKeyword())
                .or().like(BlogPost::getContent, request.getKeyword()));
    }
    if (StringUtils.hasText(request.getCategory())) {
        wrapper.eq(BlogPost::getCategory, request.getCategory());
    }
    if (request.getUserId() != null) {
        wrapper.eq(BlogPost::getUserId, request.getUserId());
    }
    if (request.getTagId() != null) {
        // 閫氳繃涓棿琛ㄥ弽鏌?        List<Long> ids = blogPostTagMapper.selectList(...).stream()
                .map(BlogPostTag::getPostId).toList();
        if (ids.isEmpty()) return new Page<>(...0...);
        wrapper.in(BlogPost::getId, ids);
    }
    wrapper.orderByDesc(BlogPost::getCreateTime);

    return this.page(page, wrapper).convert(this::toListVO);
}
```

馃挕 **`LambdaQueryWrapper` 鐨?`.and(w -> ...)`**锛氭嫭鍙烽噷鐨?`or()` 涓嶄細閫冨嚭鍘诲奖鍝嶅灞傛潯浠垛€斺€旇繖涓€鐐规柊鎵嬪緢瀹规槗韪╁潙銆傛瘮濡備笉鍐?`.and(...)` 鍖呰９ OR 瀛愬彞锛屽氨浼氬彉鎴?`WHERE status=1 AND title LIKE 'x' OR content LIKE 'x'`锛屽叧閿瓧娈靛叏閮ㄨ OR "鐭矾"杩囨护銆?
鈿狅笍 鏍囩绛涢€夎繖閲屾湁 **N+1 闅愭偅**锛氬厛鏌ヤ腑闂磋〃锛屽啀 `IN` 涓昏〃銆傚鏋滄煇鏍囩涓嬫枃绔犺繃澶氾紝鍙兘浜х敓涓婂崈涓?ID 鐨?IN 瀛愬彞锛屾湭鏉ラ渶瑕佹崲鎴?JOIN SQL 浼樺寲銆?
## 11.4 鏂囩珷璇︽儏 + 闃呰閲忛槻鍒?
璇︽儏鎺ュ彛寰堟櫘閫氣€斺€旀牴鎹?ID 鏌ヨ〃锛屾嫾瑁呬綔鑰呬俊鎭拰鏍囩銆?*閲嶅ご鎴忔槸闃呰閲忛槻鍒?*銆?
`incrementViewCount` 鍦?Controller 灞傚厛鍋氫簡涓€閬撹繃婊わ細

```java
@PutMapping("/{id}/view")
public Result<Void> incrementViewCount(@PathVariable Long id, HttpServletRequest req) {
    String userKey = getUserIdentifier(req) + "-" + id;
    long now = System.currentTimeMillis();
    AtomicLong lastViewTime = viewCountCache.computeIfAbsent(userKey, k -> new AtomicLong(0));

    while (true) {
        long lastTime = lastViewTime.get();
        if (now - lastTime < VIEW_COUNT_INTERVAL_MS) {
            return Result.success(null);   // 1 鍒嗛挓鍐呬笉閲嶅璁℃暟
        }
        if (lastViewTime.compareAndSet(lastTime, now)) break;  // CAS 鎴愬姛
        // 澶辫触锛岄噸璇?lastTime 鍐嶆寰幆
    }
    blogPostService.incrementViewCount(id);
    return Result.success(null);
}
```

閫愭瑙ｉ噴锛?
- **鐢ㄦ埛鏍囪瘑 `getUserIdentifier`**锛氱櫥褰曠敤鎴风敤 `user-{id}`锛涙湭鐧诲綍鐢?`guest-{IP}-{UA hash}`锛岃繖灏辨槸甯歌鐨?鎸囩汗"銆傛瘮鍗曠函 IP 鏇撮毦浼€狅紝浣嗘瘮寮鸿处鍙蜂綋绯绘垚鏈洿浣庛€?- **缂撳瓨浣跨敤 LRU**锛歚new LinkedHashMap<>(16, 0.75f, true)` + `removeEldestEntry` 瀹炵幇绠€鍗?LRU锛屾渶澶?10000 鏉★紝閬垮厤鍐呭瓨娉勬紡銆?- **CAS锛圕ompare-And-Set锛?*锛歚compareAndSet(lastTime, now)` 鍦ㄥ苟鍙戝満鏅笅淇濊瘉鍙湁涓€涓嚎绋嬭兘鎴愬姛鏇存柊鏃堕棿鎴筹紝鍏跺畠绾跨▼璇诲埌鏂板€煎悗浼氳嚜鍔ㄥ垽鏂?鍦?1 鍒嗛挓鍐?鑰?return銆傝繖灏辫В鍐充簡鎵€璋撶殑 **TOCTOU**锛圱ime-Of-Check-To-Time-Of-Use锛夌珵鎬併€?
馃挕 鐪熸鐨?incrementViewCount 钀借〃涔熸槸涓€鏉″師瀛?SQL锛歚UPDATE blog_post SET view_count = view_count + 1 WHERE id = ?`銆?
## 11.5 缂栬緫/鍒犻櫎锛堜粎浣滆€呮垨绠＄悊鍛橈級

```java
if (!post.getUserId().equals(userId) && !SecurityUtils.isCurrentUserAdmin()) {
    throw new BusinessException(403, "鏃犳潈淇敼姝ゆ枃绔?);
}
```

馃挕 杩欎竴琛屾潈闄愭鏌ワ紝鏄」鐩噷鑷冲皯鍑虹幇杩?20 娆＄殑鍥哄畾妯″紡锛?*璧勬簮鎵€鏈夎€?* 鎴?**绠＄悊鍛?* 鍙搷浣滐紝鍏朵粬浜?403銆?
鍒犻櫎閲囩敤**閫昏緫鍒犻櫎**鈥斺€擿removeById` 鍐呴儴鐢?`@TableLogic` 杞寲涓?UPDATE銆傚悓鏃舵墜鍔ㄦ竻鐞?`blog_post_tag` 涓棿琛ㄥ叧鑱旓紙鏍囩鏄叡浜祫婧愶紝鍏崇郴涓嶅簲淇濈暀锛夈€?
鈿狅笍 璇勮/鐐硅禐/鏀惰棌鏁版嵁**涓嶇骇鑱斿垹**锛屼繚鐣欏彲鐢ㄤ簬瀹¤锛屽睍绀烘椂閫氳繃 `is_deleted` / `status` 杩囨护鍗冲彲銆?
## 11.6 鑽夌鑷姩淇濆瓨

`blog_draft` 琛ㄤ笌 `blog_post` 瀛楁绫讳技锛屽浜?`user_id`锛屽皯浜嗙粺璁″瓧娈点€?
```java
public Long saveDraft(Long userId, SaveDraftRequest req) {
    BlogDraft draft = new BlogDraft();
    draft.setUserId(userId);
    draft.setTitle(htmlSanitizer.sanitizeRichText(req.getTitle()));
    draft.setContent(htmlSanitizer.sanitizeRichText(req.getContent()));
    // ...
    blogDraftMapper.insert(draft);
    return draft.getId();
}

public SaveDraftRequest getLatestDraft(Long userId) {
    return blogDraftMapper.selectOne(new LambdaQueryWrapper<BlogDraft>()
            .eq(BlogDraft::getUserId, userId)
            .orderByDesc(BlogDraft::getUpdateTime)
            .last("LIMIT 1"));
}
```

馃挕 鍓嶇鍙互鍋?*鑺傛祦锛坉ebounce锛?0 绉掕Е鍙戜竴娆?*鑷姩淇濆瓨锛屽姞涓婃墜鍔ㄤ繚瀛樻寜閽紝浣撻獙鍜?鐭ヤ箮鍐欐枃绔?鎺ヨ繎銆?
## 11.7 楂樼骇鎼滅储 + 鎼滅储寤鸿

`advancedSearch` 姣斿熀纭€鍒楄〃澶氫簡锛氬垎绫荤粍鍚堛€佹椂闂村尯闂淬€佹寜 view/like/createTime 鎺掑簭銆?
```java
if (req.getStartDate() != null) {
    wrapper.ge(BlogPost::getCreateTime, req.getStartDate());
}
if (req.getEndDate() != null) {
    wrapper.le(BlogPost::getCreateTime, req.getEndDate());
}
switch (req.getSortBy()) {
    case "viewCount" -> wrapper.orderByDesc(BlogPost::getViewCount);
    case "likeCount" -> wrapper.orderByDesc(BlogPost::getLikeCount);
    default -> wrapper.orderByDesc(BlogPost::getCreateTime);
}
```

`getSearchSuggestions` 缁欐悳绱㈡鍋氳嚜鍔ㄨˉ鍏細

```java
public List<String> getSearchSuggestions(String keyword) {
    if (!StringUtils.hasText(keyword)) return List.of();
    return blogPostMapper.selectList(new LambdaQueryWrapper<BlogPost>()
            .eq(BlogPost::getStatus, 1)
            .likeRight(BlogPost::getTitle, keyword)  // 鍓嶇紑鍖归厤
            .orderByDesc(BlogPost::getViewCount)
            .last("LIMIT 10"))
        .stream().map(BlogPost::getTitle).distinct().toList();
}
```

馃挕 `likeRight` 绛変环浜?`LIKE 'keyword%'`锛岃兘鍛戒腑绱㈠紩锛涘鏋滅敤 `like`锛屽墠缂€閫氶厤绗︿細璁?MySQL 鍏ㄨ〃鎵弿銆?
---

# 绗?12 绔?浜掑姩妯″潡锛堣瘎璁?/ 鐐硅禐 / 鏀惰棌锛?
浜掑姩妯″潡鏄鍧涚殑"琛€娑?銆備笁涓姩浣滃悇鏈夐毦鐐癸細璇勮鑰冮獙**鏍戝舰缁撴瀯**锛岀偣璧炶€冮獙**骞跺彂鍐?*锛屾敹钘忎笌鐐硅禐楂樺害鐩镐技銆?
## 12.1 璇勮锛氬祵濂楀洖澶嶃€佹爲褰㈢粍瑁呫€佺骇鑱斿垹闄?
`blog_comment` 瀛楁锛歩d銆乸ostId銆乽serId銆乸arentId銆乧ontent銆乧reateTime銆乮sDeleted銆?
鏂板缓璇勮鏃舵牎楠?鐖惰瘎璁哄繀椤诲睘浜庡悓涓€绡囨枃绔?鏄叧閿細

```java
if (request.getParentId() != null) {
    BlogComment parent = this.getById(request.getParentId());
    if (parent == null) throw new BusinessException(404, "鐖惰瘎璁轰笉瀛樺湪");
    if (!request.getPostId().equals(parent.getPostId())) {
        throw new BusinessException(400, "鐖惰瘎璁轰笉灞炰簬璇ユ枃绔?);
    }
}
```

馃挕 **涓轰粈涔堟牎楠岋紵** 鍚﹀垯鏀诲嚮鑰呭彲浠ラ€氳繃 `parentId` 鎶婂洖澶?绉绘"鍒板埆鐨勬枃绔犱笅锛屽埗閫犳贩涔便€?
鈿狅笍 **璇勮鐢?`sanitizePlainText`**鈥斺€旀瘮鏂囩珷姝ｆ枃鏇翠弗鏍硷紝**鍓ョ鎵€鏈?HTML**銆傚洜涓鸿瘎璁哄満鏅敤鎴锋病蹇呰鍙戝瘜鏂囨湰銆傝繖鏄?XSS 鐨勯澶栧姞鍥恒€?
闅忓悗 `incrementCommentCount(postId)` 鐢?SQL 鍘熷瓙鍔?1銆?
浜嬩欢鏈哄埗鍚屾鎶涘嚭 `CommentCreatedEvent`锛岀暀缁欓€氱煡妯″潡鍘绘秷璐癸紙瑙?13 绔狅級銆?
**鏍戝舰缁勮**锛?
```java
List<BlogComment> comments = this.list(...);  // 鎷嶅钩鐨勮瘎璁哄垪琛?Map<Long, CommentVO> voMap = comments.stream()
    .map(this::toVO)
    .collect(Collectors.toMap(CommentVO::getId, c -> c));

List<CommentVO> roots = new ArrayList<>();
for (CommentVO vo : voMap.values()) {
    if (vo.getParentId() == null) roots.add(vo);
    else {
        CommentVO parent = voMap.get(vo.getParentId());
        if (parent != null) parent.getReplies().add(vo);
    }
}
return roots;
```

馃挕 杩欐槸涓€閬嶅惊鐜氨鏋勫缓鏍戠殑缁忓吀鍐欐硶鈥斺€斿厛鎶婃墍鏈夎妭鐐?put 杩?Map锛屽啀浜屾寰幆鎸傚埌 parent 鐨?children 涓娿€?*O(n) 涓嶉噸澶嶆煡璇?*锛岃繙蹇簬"閫掑綊+SQL 澶氭璁块棶"銆?
**绾ц仈鍒犻櫎**锛?
```java
public void deleteComment(Long commentId, Long userId) {
    BlogComment c = this.getById(commentId);
    // 鏉冮檺妫€鏌ュ悓鍓?    List<Long> idsToDelete = new ArrayList<>();
    idsToDelete.add(commentId);
    collectChildCommentIds(commentId, idsToDelete, 1);  // 閫掑綊鏀堕泦
    this.removeByIds(idsToDelete);   // 鎵归噺閫昏緫鍒犻櫎
}
```

鈿狅笍 `collectChildCommentIds` 绗笁涓弬鏁版槸**閫掑綊娣卞害**锛岄檺鍒跺祵濂楀眰绾э紙濡?5 灞傦級闃叉鎭舵剰鏋勯€犵殑"娣卞害鐐稿脊"鎾戠垎 JVM銆?
## 12.2 鐐硅禐锛氬敮涓€绾︽潫 + 閫昏緫鍒犻櫎 + 缁嗙矑搴﹂攣 + DuplicateKeyException

`blog_like` 琛ㄧ殑澶嶅悎鍞竴绱㈠紩 `(user_id, post_id)`锛氫繚璇佷竴浜哄涓€鏂囩珷鍙兘鐐逛竴娆¤禐銆?
浣嗗姞浜?`is_deleted` 瀛楁鍚庯紝浼氬嚭鐜颁竴涓煕鐩撅細
- A 鐐硅禐 鈫?鎻掑叆璁板綍 (1, 100, isDeleted=0)
- A 鍙栨秷 鈫?閫昏緫鍒犻櫎鍙樻垚 (1, 100, isDeleted=1)
- A 鍙堢偣璧?鈫?鎯冲啀鎻?(1, 100, isDeleted=0) **鍗磋鍞竴绱㈠紩鎸′綇**锛?
椤圭洰鐨勮В娉曪細**鍞竴绱㈠紩甯︿笂 isDeleted 鍒?*锛歚UNIQUE (user_id, post_id, is_deleted)`锛岃繖鏍峰垹闄ゅ悗鐨勮褰曚笌鏂拌褰曠殑 (is_deleted) 涓嶅悓锛屽氨涓嶄細鍐茬獊銆傛垨鑰呭彟涓€绉嶅疄鐜帮細**涓嶅啀鎻掓柊琛岋紝鎶婂凡鍒犻櫎琛?isDeleted 鏀瑰洖 0**銆傛湰椤圭洰璧板墠鑰呮柟妗堛€?
鏍稿績瀹炵幇 `toggleLike`锛?
```java
String lockKey = userId + "-" + postId;
synchronized (getLock(lockKey)) {                // 缁嗙矑搴﹂攣
    BlogLike existing = this.getOne(...);
    if (existing != null) {
        // 鍙栨秷鐐硅禐锛堥€昏緫鍒犻櫎锛?        ((BlogLikeMapper) baseMapper).logicalDeleteById(existing.getId());
        blogPostService.decrementLikeCount(postId);
        result.setAction("unlike");
    } else {
        try {
            this.save(newLike);
            blogPostService.incrementLikeCount(postId);
            eventPublisher.publishEvent(new LikeCreatedEvent(...));
            result.setAction("like");
        } catch (DuplicateKeyException e) {
            // 骞跺彂锛氬彟涓€绾跨▼宸茬粡鎻掑叆
            BlogLike concurrent = this.getOne(...);
            if (concurrent != null) {
                logicalDelete(concurrent.getId());
                decrementLikeCount(postId);
                result.setAction("unlike");
            }
        }
    }
}
```

馃挕 **缁嗙矑搴﹂攣**锛氱敤 `userId-postId` 浣滀负 key锛屼粠 `ConcurrentHashMap` 鍙栦竴鎶?Object 閿併€傚悓涓€鐢ㄦ埛瀵瑰悓涓€鏂囩珷鐨勫苟鍙戣姹備細琚覆琛屽寲锛屼絾涓嶅奖鍝?100 涓囧叾瀹冪敤鎴枫€傛瘮 `synchronized(this)` 閭ｇ绮楃矑搴﹂攣楂樻晥鐧惧€嶃€?
鈿狅笍 **缁嗙矑搴﹂攣鐨勫唴瀛樻硠婕忛棶棰?*锛氭瘡娆＄偣璧為兘 put 涓€涓柊瀵硅薄杩?map锛屾案杩滀笉鍒犫€斺€旂櫨涓囩敤鎴峰悗 OOM銆傛湰椤圭洰閫氳繃 `LockEntry.createTime` + `MAX_LOCKS_SIZE` 鍋?LRU + 杩囨湡娓呯悊銆?
馃挕 **DuplicateKeyException 鏄渶鍚庨槻绾?*锛氬嵆浣垮墠闈?`getOne` 娌℃煡鍒帮紝浠嶅彲鑳芥湁鍙︿竴绾跨▼鍒氭彃瀹屻€傛暟鎹簱鍞竴绱㈠紩浼氬厹浣忥紝骞剁敱浠ｇ爜澶勭悊涓?鍙栨秷鐐硅禐"鎴?閲嶈瘯"銆?
## 12.3 鏀惰棌锛氱被浼肩偣璧?+ "鎴戠殑鏀惰棌"鍒楄〃

`blog_collect` 琛ㄧ粨鏋勪笌 `blog_like` 鍑犱箮涓€妯′竴鏍凤紝閫昏緫涔熷鐢ㄥ悓鏍风殑"缁嗙矑搴﹂攣 + 鍞竴绱㈠紩 + DuplicateKey 鍏滃簳"妯″紡銆傚樊寮傚湪澶氫簡涓€涓?鎴戠殑鏀惰棌"鎺ュ彛锛?
```java
public IPage<PostListResponse> myCollects(Long userId, int page, int size) {
    Page<BlogCollect> p = new Page<>(page, size);
    IPage<BlogCollect> collects = blogCollectMapper.selectPage(p,
        new LambdaQueryWrapper<BlogCollect>()
            .eq(BlogCollect::getUserId, userId)
            .orderByDesc(BlogCollect::getCreateTime));

    List<Long> postIds = collects.getRecords().stream()
            .map(BlogCollect::getPostId).toList();
    if (postIds.isEmpty()) return new Page<>(page, size, 0);

    List<BlogPost> posts = blogPostMapper.selectBatchIds(postIds);
    // 杞?VO 鐣?}
```

馃挕 **鎵归噺鏌ヨ selectBatchIds**鈥斺€旈伩鍏?N+1銆備竴瀹氳蹇嶄綇"鍦ㄥ惊鐜噷 selectById"鐨勫啿鍔ㄣ€?
---

# 绗?13 绔?鍏虫敞涓庨€氱煡

## 13.1 鍏虫敞鍏崇郴琛?blog_follow

| 瀛楁 | 璇存槑 |
| --- | --- |
| id | 涓婚敭 |
| follower_id | 璋佸叧娉紙绮変笣锛?|
| following_id | 琚皝鍏虫敞锛堝崥涓伙級 |
| create_time | 鍏虫敞鏃堕棿 |
| is_deleted | 閫昏緫鍒犻櫎 |

鍞竴绱㈠紩 `(follower_id, following_id, is_deleted)`锛屽惈涔夊悓鐐硅禐銆?
## 13.2 鍏虫敞/鍙栧叧鎺ュ彛锛堜笉鑳藉叧鑷繁 + 鍙屽悜璁℃暟锛?
`FollowServiceImpl#follow` 涓?`toggleLike` 楂樺害鐩镐技锛?
```java
if (targetUserId.equals(currentUserId)) {
    throw new BusinessException(400, "涓嶈兘鍏虫敞鑷繁");
}
SysUser target = sysUserMapper.selectById(targetUserId);
if (target == null) throw new BusinessException(404, "鐢ㄦ埛涓嶅瓨鍦?);

synchronized (getLock(currentUserId + "-" + targetUserId)) {
    BlogFollow exists = this.getOne(...);
    if (exists != null) {
        result.setAction("already_following");
    } else {
        try {
            this.save(newFollow);
            sysUserMapper.incrementFollowerCount(targetUserId);   // 鍗氫富绮変笣+1
            sysUserMapper.incrementFollowingCount(currentUserId); // 鎴戝叧娉?1
            eventPublisher.publishEvent(new FollowCreatedEvent(currentUserId, targetUserId));
        } catch (DuplicateKeyException e) {
            // 骞跺彂鍏滃簳
        }
    }
}
```

馃挕 **鍙屽悜璁℃暟**锛氱矇涓濇暟鍜屽叧娉ㄦ暟鍚勮嚜缁存姢鍦?`sys_user` 琛紝鍘熷瓙 SQL 鍔犲噺銆?
鈿狅笍 **蹇呴』鍏堟牎楠?鐩爣鐢ㄦ埛瀛樺湪"鍐嶆彃琛?*鈥斺€斿惁鍒欐彃浜嗚剰鏁版嵁锛岀粺璁℃案杩滃亸銆?
鍙栧叧娴佺▼鍑犱箮瀵圭О锛氭鏌ヨ褰曞湪 鈫?閫昏緫鍒犻櫎 鈫?鍙屽悜鍑?1銆?
## 13.3 绮変笣/鍏虫敞鍒楄〃锛堝垎椤碉級

```java
public IPage<UserVO> getFollowersPage(Long userId, int page, int size) {
    Page<BlogFollow> p = new Page<>(page, size);
    IPage<BlogFollow> followPage = this.page(p,
        new LambdaQueryWrapper<BlogFollow>()
            .eq(BlogFollow::getFollowingId, userId)
            .orderByDesc(BlogFollow::getCreateTime));

    List<Long> followerIds = followPage.getRecords().stream()
            .map(BlogFollow::getFollowerId).toList();
    if (followerIds.isEmpty()) return new Page<>(page, size, 0);

    List<SysUser> users = sysUserMapper.selectBatchIds(followerIds);
    // 鎷?VO 杩斿洖
}
```

馃挕 鍚屾牱鏄?**selectBatchIds** 閬垮厤 N+1銆?
## 13.4 閫氱煡绯荤粺锛歜log_notification

| 瀛楁 | 璇存槑 |
| --- | --- |
| id | 涓婚敭 |
| type | 閫氱煡绫诲瀷锛坈omment/like/follow/system锛?|
| title | 鏍囬 |
| content | 鍐呭 |
| from_user_id | 瑙﹀彂鑰咃紙鍙兘涓?null锛氱郴缁熼€氱煡锛?|
| to_user_id | 鎺ユ敹鑰?|
| target_type | 鐩爣绫诲瀷锛坧ost/comment锛?|
| target_id | 鐩爣 ID |
| is_read | 0 鏈 / 1 宸茶 |
| create_time | |

`NotificationServiceImpl#sendNotification` 鍐欏緱寰堣皑鎱庯細

```java
public void sendNotification(String type, String title, String content,
        Long fromUserId, Long toUserId, String targetType, Long targetId) {
    // 1. 涓嶉€氱煡鑷繁锛堣嚜宸辫瘎璁鸿嚜宸辩殑鏂囩珷涓嶄細浜х敓閫氱煡锛?    if (fromUserId != null && fromUserId.equals(toUserId)) return;

    // 2. 妫€鏌ユ帴鏀惰€呮槸鍚﹁繕瀛樺湪
    if (toUserId != null) {
        SysUser target = sysUserMapper.selectById(toUserId);
        if (target == null) return;
    }

    BlogNotification n = new BlogNotification();
    n.setType(type);
    n.setTitle(title);
    n.setContent(content);
    n.setFromUserId(fromUserId);
    n.setToUserId(toUserId);
    n.setTargetType(targetType);
    n.setTargetId(targetId);
    n.setIsRead(0);
    this.save(n);
}
```

馃挕 "鑷繁涓嶉€氱煡鑷繁"鐪嬩技灏忎簨锛屽疄闄呮槸鐢ㄦ埛浣撻獙缁嗚妭锛氫綘缁欒嚜宸辨枃绔犵偣浜嗚禐銆佽嚜宸卞洖澶嶈嚜宸辫瘎璁烘椂锛岄€氱煡涓績涓嶄細鍒峰嚭鏉ヤ竴鏉℃棤鎰忎箟璁板綍銆?
## 13.5 浜嬩欢鏈哄埗锛欳ommentCreatedEvent / LikeCreatedEvent / FollowCreatedEvent

浜嬩欢绫诲彧鏄畝鍗曠殑鏁版嵁杞戒綋锛?
```java
@Getter
public class LikeCreatedEvent {
    private final Long fromUserId;
    private final Long toUserId;
    private final Long postId;
    private final String postTitle;
    public LikeCreatedEvent(Long fromUserId, Long toUserId, Long postId, String title) {
        this.fromUserId = fromUserId;
        this.toUserId = toUserId;
        this.postId = postId;
        this.postTitle = title;
    }
}
```

鎴戜滑鍦ㄤ笁涓湴鏂?`eventPublisher.publishEvent(...)`锛氳瘎璁哄垱寤恒€佺偣璧炪€佸叧娉ㄣ€?
馃挕 **涓轰粈涔堣浜嬩欢鏈哄埗锛?*
- **瑙ｈ€?*锛氫笟鍔￠€昏緫锛堢偣璧烇級涓嶉渶瑕佺煡閬撴湁"閫氱煡涓績"瀛樺湪銆傛湭鏉ュ姞"鐭俊鎻愰啋"涔熷彧闇€澶氫竴涓洃鍚櫒銆?- **鍙紓姝?*锛氱洃鍚櫒鍙敞瑙ｄ负寮傛鎵ц锛岄伩鍏嶆嫋鎱富娴佺▼銆?
## 13.6 @TransactionalEventListener 寮傛鍙戦€侀€氱煡锛堜簨鍔℃彁浜ゅ悗锛?
```java
@Component
public class NotificationEventListener {

    @Autowired
    private NotificationService notificationService;

    @Async
    @TransactionalEventListener(phase = TransactionPhase.AFTER_COMMIT)
    public void onCommentCreated(CommentCreatedEvent e) {
        notificationService.sendNotification(
            "comment",
            "鎮ㄧ殑鏂囩珷鏀跺埌浜嗘柊璇勮",
            e.getContent(),
            e.getFromUserId(),
            e.getToUserId(),
            "post", e.getPostId());
    }

    @Async
    @TransactionalEventListener(phase = TransactionPhase.AFTER_COMMIT)
    public void onLikeCreated(LikeCreatedEvent e) {
        notificationService.sendNotification(
            "like", "鎮ㄧ殑鏂囩珷鏀跺埌浜嗘柊鐨勭偣璧?,
            "鐐硅禐浜嗕綘鐨勬枃绔犮€? + e.getPostTitle() + "銆?,
            e.getFromUserId(), e.getToUserId(),
            "post", e.getPostId());
    }
}
```

閫愰」瑙ｉ噴锛?
- `@TransactionalEventListener(phase = AFTER_COMMIT)`锛氱瓑褰撳墠浜嬪姟**鐪熺殑鎻愪氦**涔嬪悗鎵嶈Е鍙戯紝閬垮厤"浜嬪姟鍥炴粴浣嗛€氱煡宸插彂"鐨勮剰鏁版嵁銆?- `@Async`锛氭妸鍙戦€氱煡閫昏緫鏀惧埌鐙珛绾跨▼姹犳墽琛岋紝涓嶉樆濉炰富璇锋眰銆?- 闇€瑕佸湪閰嶇疆绫诲姞 `@EnableAsync` 鍚敤銆?
鈿狅笍 **涓轰綍涓嶇敤 Phase.BEFORE_COMMIT锛?* 鍥犱负濡傛灉浜嬪姟鏈€鍚庡洖婊氾紝閫氱煡灏辨垚浜嗗菇鐏碉細鐢ㄦ埛姘歌繙鎵句笉鍒伴偅鏉＄偣璧烇紝浣嗚閫氱煡"琚偣璧炰簡"銆?
---

# 绗?14 绔?鏍″弸鍦堜笌濯掍綋

鏍″弸鍦堬紙Circle锛夌被浼煎井鍗?Twitter 鐨勭煭鍔ㄦ€佺郴缁燂紝涓庡崥瀹紙闀挎枃绔狅級骞宠銆?
## 14.1 blog_circle_post 瀛楁

| 瀛楁 | 璇存槑 |
| --- | --- |
| id | 涓婚敭 |
| user_id | 浣滆€?|
| content | 鏂囧瓧鍐呭锛堟渶闀?2000 瀛楋級 |
| content_type | 1 绾枃鏈?/ 2 鍥炬枃 / 3 杞彂 |
| image_urls | JSON 鏁扮粍锛屽瓨鍥剧墖 URL |
| location | 浣嶇疆淇℃伅 |
| repost_id | 鍘熷姩鎬?id锛堜粎杞彂鏃讹級 |
| view_count / like_count / comment_count / repost_count | 璁℃暟 |
| visibility | 0 鍏紑 / 1 浠呭叧娉ㄨ€?/ 2 浠呰嚜宸?|
| allow_comment | 鏄惁鍏佽璇勮锛?/1锛?|
| allow_repost | 鏄惁鍏佽杞彂锛?/1锛?|
| is_top | 鏄惁缃《 |
| status | 1 姝ｅ父 / 2 宸插垹闄わ紙杩欓噷鐢?status 浠ｆ浛 is_deleted锛?|
| tags | JSON 鏁扮粍 |
| create_time / update_time | |

馃挕 **涓轰綍 status 鑰屼笉鐢?@TableLogic**锛熷洜涓烘牎鍙嬪湀鐨?鍒犻櫎"涓嶆槸绠€鍗曟爣蹇楋紝鍙兘鏈?鏆傚瓨""杩濊涓嬫灦"绛夌姸鎬侊紝鏁呯敤 status 鏁板€笺€?
## 14.2 鎺ㄨ崘娴?vs 鍏虫敞娴?
`getRecommendFeed`锛?
```java
LambdaQueryWrapper<CirclePost> wrapper = new LambdaQueryWrapper<>();
wrapper.eq(CirclePost::getStatus, 1)
       .and(w -> w.eq(CirclePost::getVisibility, 0)        // 鍏紑
                  .or(currentUserId != null, w2 ->
                      w2.eq(CirclePost::getUserId, currentUserId)
                        .ne(CirclePost::getVisibility, 0)))// 鑷繁鐨勯潪鍏紑
       .orderByDesc(CirclePost::getIsTop)   // 缃《浼樺厛
       .orderByDesc(CirclePost::getCreateTime);
```

`getFollowingFeed`锛?
```java
List<UserVO> followings = followService.getFollowing(userId);
List<Long> ids = followings.stream().map(UserVO::getId).toList();

wrapper.eq(CirclePost::getStatus, 1)
       .in(CirclePost::getUserId, ids)
       .and(w -> w.eq(CirclePost::getVisibility, 0)
                  .or().eq(CirclePost::getVisibility, 1)
                  .or().eq(CirclePost::getVisibility, 2)
                       .eq(CirclePost::getUserId, userId));
```

馃挕 **鍏虫敞娴?*鍙睍绀?*鎴戝叧娉ㄧ殑浜?*鐨勫姩鎬侊細鍏堝彇鍏虫敞鍒楄〃锛屽啀鐢?`in` 鎷煎嚭 SQL銆傜┖鍏虫敞鍒楄〃鐩存帴杩斿洖绌洪泦鍚堬紙閬垮厤 IN () 鎶ラ敊锛夈€?
## 14.3 canViewPost 鏉冮檺鏍￠獙

```java
private boolean canViewPost(CirclePost post, Long currentUserId) {
    // 1. 浣滆€呮湰浜烘€绘槸鍙互鐪?    if (currentUserId != null && post.getUserId().equals(currentUserId)) return true;
    // 2. 鍏紑鍔ㄦ€佷汉浜哄彲鐪?    if (post.getVisibility() == null || post.getVisibility() == 0) return true;
    // 3. 浠呭叧娉ㄨ€呭彲瑙佲€斺€斿繀椤绘槸鐧诲綍鐢ㄦ埛涓斿叧娉ㄤ簡鍗氫富
    if (post.getVisibility() == 1) {
        if (currentUserId == null) return false;
        return followService.isFollowing(currentUserId, post.getUserId());
    }
    // 4. 浠呰嚜宸卞彲瑙侊紝浣嗕笉鏄綔鑰呮湰浜猴紝鎷掔粷
    return false;
}
```

鈿狅笍 杩涘叆 `getPostDetail` 绛夋柟娉曟椂鍔″繀鍏堣皟 `canViewPost`锛屽惁鍒欎細娉勯湶闅愮鍔ㄦ€併€?
## 14.4 杞彂鍔ㄦ€侊紙鍘熷姩鎬侀殣钘忓鐞嗭級

```java
if (repostId != null) {
    CirclePost original = this.getById(repostId);
    if (original == null || original.getStatus() == 2) {
        throw new BusinessException(404, "鍘熷姩鎬佷笉瀛樺湪");
    }
    if (original.getAllowRepost() == 0) {
        throw new BusinessException(403, "璇ュ姩鎬佺姝㈣浆鍙?);
    }
    if (!canViewPost(original, userId)) {
        throw new BusinessException(403, "鏃犳潈杞彂姝ゅ姩鎬?);
    }
    if (original.getVisibility() == 2) {  // 鍘熷姩鎬佷粎鑷繁鍙
        visibility = 1;                    // 鑷姩闄嶇骇鍒颁粎鍏虫敞鑰?    }
    contentType = 3;
}
```

馃挕 涓€绯诲垪鏍￠獙淇濊瘉杞彂鍏崇郴涓嶈婊ョ敤锛氬師鍔ㄦ€佸繀椤诲瓨鍦?/ 鍏佽杞彂 / 鎴戣兘鐪嬪埌銆傛渶鍚庨偅鏉?鍘熷姩鎬佷粎鑷繁鍙鏃讹紝杞彂鑷姩璁句负浠呭叧娉ㄨ€?鏄釜闅愮鍗囩骇鈥斺€斾笉鍙兘璁?鑷垜鍙"閫氳繃杞彂鏆撮湶缁欓檶鐢熶汉銆?
## 14.5 鏍″弸鍦堢偣璧?璇勮/鎼滅储

鎶€鏈粏鑺備笌鍗氬鐐硅禐銆佸崥瀹㈣瘎璁轰竴妯′竴鏍凤細缁嗙矑搴﹂攣銆丏uplicateKeyException 鍏滃簳銆佸師瀛?+/-銆佷簨浠舵満鍒躲€?*澶嶇敤鏃㈡湁妯″紡锛岄伩鍏嶉噸澶嶉€犺疆瀛?*鈥斺€旇繖鏄」鐩唬鐮佽嚜濮嬭嚦缁堢殑绾緥銆?
## 14.6 濯掍綋涓婁紶 blog_media锛?00MB + 绫诲瀷鐧藉悕鍗?+ 閲嶅懡鍚嶏級

```java
public Long upload(MultipartFile file, Long userId) {
    if (file.getSize() > 500L * 1024 * 1024) {
        throw new BusinessException(400, "鏂囦欢涓嶈兘瓒呰繃 500MB");
    }
    String original = file.getOriginalFilename();
    String ext = getExtension(original).toLowerCase();
    if (!ALLOWED_EXT.contains(ext)) {  // jpg/png/mp4/...
        throw new BusinessException(400, "涓嶆敮鎸佺殑鏂囦欢绫诲瀷");
    }
    String newName = UUID.randomUUID() + "." + ext;
    Path target = Paths.get(uploadDir, newName);
    Files.copy(file.getInputStream(), target);

    BlogMedia m = new BlogMedia();
    m.setUserId(userId);
    m.setOriginalName(original);
    m.setStoredName(newName);
    m.setUrl("/media/" + newName);
    m.setSize(file.getSize());
    m.setMimeType(file.getContentType());
    blogMediaMapper.insert(m);
    return m.getId();
}
```

馃挕 **涓夐亾闃茬嚎**锛?1. **澶у皬闄愬埗**锛氶伩鍏?DOS锛堢敤鎴风柉鐙備笂浼犺秴澶ф枃浠讹級銆?2. **鍚庣紑鐧藉悕鍗?*锛氭嫆缁?.exe / .sh / .php锛岄伩鍏嶅湪鏈嶅姟鍣ㄤ笂钀藉湴鎭舵剰鍙墽琛屾枃浠躲€?3. **UUID 閲嶅懡鍚?*锛氶槻姝㈢敤鎴蜂笂浼?`../../../etc/passwd` 杩欐牱鐨?璺緞绌胯秺"鏀诲嚮銆?
鈿狅笍 浠呴潬鍚庣紑涓嶅鈥斺€旀敾鍑昏€呭彲浠ユ妸 .php 鏂囦欢鏀瑰悕涓?.jpg銆傜敓浜х幆澧冭繕闇€鏍￠獙 magic number锛堟枃浠跺ご锛夈€?
## 14.7 鏂囩珷缁戝畾濯掍綋 blog_post_media

涓棿琛?`(post_id, media_id, sort_order)`锛氫竴绡囨枃绔犲彲鎸傚寮犲浘锛屾寜 sort_order 鎺掑簭銆傚垹闄ゆ枃绔犳椂鍙渶绉婚櫎鍏宠仈锛屼笉鍒犲獟浣撴湰浣撯€斺€斿獟浣撳彲琚涓姩鎬?鏂囩珷鍏变韩銆?
---

# 绗?15 绔?瓒嬪娍 + 涓炬姤绯荤粺

## 15.1 blog_trending 鐑害缁熻

| 瀛楁 | 璇存槑 |
| --- | --- |
| id | 涓婚敭 |
| target_type | post / tag |
| target_id | 鐩爣 ID |
| score | 鐑害鍒嗭紙璁＄畻缁撴灉锛?|
| period | 鏃堕棿鍛ㄦ湡锛歞aily / weekly |
| stat_time | 缁熻鍩哄噯鏃堕棿 |
| create_time | |

## 15.2 鐑害鍏紡

鐪熷疄椤圭洰鐨勭儹搴﹁绠楅噰鐢?*鍥哄畾鏉冮噸鍔犳潈绱姞**锛屽叕寮忓涓嬶細

```
score = view_count 脳 1 + like_count 脳 5 + comment_count 脳 10
```

涓変釜甯搁噺鐨勫畾涔夊湪 `TrendingServiceImpl.java` 涓紙绗?43-45 琛岋級锛?
```java
private static final int VIEW_WEIGHT = 1;
private static final int LIKE_WEIGHT = 5;
private static final int COMMENT_WEIGHT = 10;
```

**娌℃湁** `collect_count` 鏉冮噸锛屼篃娌℃湁鏃堕棿琛板噺鍑芥暟 `decay()`銆傛瘡澶╁噷鏅?0 鐐瑰畾鏃朵换鍔★紙`@Scheduled(cron = "0 0 0 * * ?")`锛夊叏閲忛噸鏂拌绠楁墍鏈夊凡鍙戝竷鏂囩珷鐨勭儹搴﹀垎锛岀粨鏋滃啓鍏?`blog_trending` 琛ㄣ€傛煡璇㈡帴鍙ｅ彧璇昏繖寮犺〃锛岄浂璁＄畻鍘嬪姏銆?
鈿狅笍 椤圭洰鏈娇鐢ㄦ敹钘忔暟鏉冮噸鍜屾椂闂磋“鍑忋€傚闇€璋冩暣鏉冮噸锛岄渶淇敼婧愮爜涓繖涓変釜甯搁噺骞堕噸鏂伴儴缃层€?
## 15.3 鐑棬鏂囩珷/鐑棬鏍囩 API

```java
@GetMapping("/trending/posts")
public Result<List<PostListResponse>> hotPosts(
        @RequestParam(defaultValue = "daily") String period,
        @RequestParam(defaultValue = "10") int limit) {
    return Result.success(trendingService.getHotPosts(period, limit));
}
```

Service 鍐呴儴鎸?score 闄嶅簭锛屽啀鍘?`blog_post` 琛ㄦ煡璇︽儏銆?
馃挕 **姣忓ぉ 0 鐐硅窇涓€娆″畾鏃朵换鍔?*閲嶆柊璁＄畻鎵€鏈夋枃绔犵儹搴︼紝缁撴灉鍐欏叆 `blog_trending`銆傝鎺ュ彛鍙煡杩欏紶琛紝闆惰绠椼€?
## 15.4 涓炬姤妯″潡锛氱敤鎴蜂妇鎶?+ 閲嶅妫€鏌?+ 绠＄悊鍛樺皝绂?涓嬫灦

`blog_report` 瀛楁锛歩d銆乺eporterId銆乼argetType锛坧ost/comment/circle/user锛夈€乼argetId銆乺eason銆乻tatus锛? 寰呭鐞?1 宸插鐞?2 宸查┏鍥烇級銆乭andleResult銆乭andleTime銆乭andlerId銆乧reate_time銆?
涓炬姤鏍稿績浠ｇ爜锛?
```java
public Long report(ReportCreateRequest req, Long userId) {
    // 1. 24 灏忔椂鍐呬笉鑳介噸澶嶄妇鎶ュ悓涓€鐩爣
    LambdaQueryWrapper<BlogReport> w = new LambdaQueryWrapper<>();
    w.eq(BlogReport::getReporterId, userId)
     .eq(BlogReport::getTargetType, req.getTargetType())
     .eq(BlogReport::getTargetId, req.getTargetId())
     .ge(BlogReport::getCreateTime, LocalDateTime.now().minusHours(24));
    if (this.count(w) > 0) {
        throw new BusinessException(400, "鎮ㄥ凡涓炬姤杩囨鍐呭");
    }
    // 2. 鍏ュ簱
    BlogReport r = new BlogReport();
    BeanUtils.copyProperties(req, r);
    r.setReporterId(userId);
    r.setStatus(0);
    this.save(r);
    return r.getId();
}
```

绠＄悊鍛樺鐞嗘椂锛?
```java
public void handleReport(Long reportId, Integer action, String result, Long adminId) {
    BlogReport r = this.getById(reportId);
    if (r == null) throw new BusinessException(404, "涓炬姤涓嶅瓨鍦?);

    r.setStatus(action == 1 ? 1 : 2);
    r.setHandleResult(result);
    r.setHandlerId(adminId);
    r.setHandleTime(LocalDateTime.now());
    this.updateById(r);

    if (action == 1) {
        // 澶勭疆锛氭牴鎹?targetType 涓嬫灦鍐呭 / 灏佺鐢ㄦ埛
        switch (r.getTargetType()) {
            case "post" -> blogPostMapper.updateStatus(r.getTargetId(), 2);
            case "comment" -> blogCommentMapper.deleteById(r.getTargetId());
            case "user" -> sysUserMapper.disableUser(r.getTargetId());
        }
    }
}
```

馃挕 **閲嶅涓炬姤闃叉姢**锛氶檺鍒?24 灏忔椂鍐呭彧鑳戒妇鎶ュ悓涓€鐩爣涓€娆★紝閬垮厤涓€涓敤鎴风柉鐙傚埛閲忥紱涓?閫氱煡涓嶉€氱煡鑷繁"鍚屽睘浜庝綋楠岀粏鑺傘€?
鈿狅笍 鐪熸鐢熶骇鐜杩橀渶瑕侊細
- 涓炬姤鍐呭 XSS 杩囨护锛坮eason 瀛楁鍚屾牱瑕?sanitizePlainText锛夈€?- 绠＄悊鍛樻搷浣滄棩蹇楋紙鍝釜 admin 鍦ㄤ綍鏃跺皝浜嗚皝锛屼究浜庝簨鍚庤拷婧級銆?- 涓ラ噸涓炬姤闃堝€兼満鍒讹細鍚屼竴鍐呭琚?N 涓敤鎴蜂妇鎶ュ悗鑷姩闅愯棌锛堜汉宸ュ鏍稿墠鍏堟挙涓嬶級銆?
---

## 鏈珷灏忕粨

璧板畬鍏ぇ妯″潡锛屾垜浠兘鍥炵瓟涓嬮潰杩欎簺闂浜嗭細

1. **濡備綍璁捐涓€寮犲疄浣撹〃锛?* 鈫?涓氬姟瀛楁 + 鍐椾綑缁熻 + 鏃堕棿鎴?+ 閫昏緫鍒犻櫎鏍囪銆?2. **濡備綍闃叉鐢ㄦ埛鏋氫妇锛?* 鈫?娉ㄥ唽鍜岀櫥褰曠殑澶辫触鎻愮ず缁熶竴妯＄硦鍖栥€?3. **濡備綍闃茬垎鐮达紵** 鈫?澶辫触娆℃暟鍘熷瓙绱姞 + 閿佸畾鏃堕棿绐楀彛銆?4. **濡備綍闃?XSS锛?* 鈫?Jsoup 鐧藉悕鍗曡繃婊わ紝瀵屾枃鏈鏉俱€佺函鏂囨湰涓ユ牸銆?5. **濡備綍闃插苟鍙戝啓閿欎贡锛?* 鈫?缁嗙矑搴﹂攣 + 鏁版嵁搴撳敮涓€绱㈠紩 + DuplicateKeyException 鍏滃簳銆?6. **濡備綍閬垮厤 N+1 鏌ヨ锛?* 鈫?`selectBatchIds` 涓€娆″彇榻?+ Map O(1) 鏌ユ壘銆?7. **濡備綍璁╅€氱煡涓嶆薄鏌撲富娴佺▼锛?* 鈫?ApplicationEventPublisher + `@TransactionalEventListener(AFTER_COMMIT) + @Async`銆?8. **濡備綍缁熻鐑害锛?* 鈫?鍥哄畾鏉冮噸鍔犳潈锛坴iew脳1 + like脳5 + comment脳10锛? 姣忓ぉ鍑屾櫒瀹氭椂浠诲姟鍏ㄩ噺棰勮绠椼€?
---

涓嬩竴閮ㄥ垎灏嗚繘鍏?**鍓嶇瀹炴垬**锛屾妸杩欎簺 API 鎺ュ埌涓€涓敤 HTML5 + JavaScript 鍐欑殑璁哄潧涓婚〉閲屸€斺€斿眾鏃朵綘灏辫兘浠庢祻瑙堝櫒鐨?鐐瑰嚮鐐硅禐"鎸夐挳锛屼竴璺拷鍒版湰绔犻噷鐨?`toggleLike` 鏂规硶锛屾妸鏁翠釜鍏ㄦ爤閾捐矾鎵撻€氥€?# 銆奐ava Spring Boot 闆跺熀纭€瀹屾暣瀛︿範鎵嬪唽銆?
## 绗洓閮ㄥ垎 杩涢樁涓庨儴缃?
> 鍩轰簬鐪熷疄椤圭洰"鏍″洯鍗氬璁哄潧绯荤粺 v1.34"鐨勫疄鎴樻暀鏉?> 椤圭洰鍦板潃锛歨ttps://github.com/Xinghe-0203/Campus_Blog

---

璇诲畬鍓嶄笁閮ㄥ垎锛屼綘搴旇宸茬粡鑳藉啓鍑哄熀鏈殑 Spring Boot CRUD 鎺ュ彛锛岃兘鐧诲綍銆佽兘鍙戞枃绔犮€佽兘璇勮銆備絾杩欒繙杩滀笉澶熴€備竴涓兘涓婄嚎銆佽兘鎵涗綇鐪熷疄鐢ㄦ埛鐨勭郴缁燂紝蹇呴』缁忚繃**瀹夊叏鍔犲浐銆佹€ц兘浼樺寲銆佸厖鍒嗘祴璇曘€佽鑼冮儴缃?*杩欏洓鍏炽€?
绗洓閮ㄥ垎灏辨槸甯︿綘璧板畬杩欏洓鍏炽€傛墍鏈夎瑙ｉ兘浼氬紩鐢ㄦ湰椤圭洰浠?v1.10 鍒?v1.34 鐨勭湡瀹炰慨澶嶆渚?鈥斺€?杩欎簺"鍧?鏄」鐩綔鑰呯湡韪╄繃鐨勶紝姣忎竴涓兘瀵瑰簲涓€娆′唬鐮佹彁浜ゃ€?
---

# 绗?16 绔?瀹夊叏鍔犲浐瀹炴垬

## 16.1 OWASP Top 10 瀹夊叏椋庨櫓姒傝

OWASP锛圤pen Web Application Security Project锛夋瘡闅斿嚑骞翠細鍙戝竷涓€娆?Web 搴旂敤鍗佸ぇ瀹夊叏椋庨櫓姒滃崟"銆傚涔犲畨鍏ㄧ殑绗竴姝ワ紝鏄煡閬撴湁鍝簺鍧戙€備笅闈㈡槸 2021 鐗堢殑绮剧畝娓呭崟锛?
| 椋庨櫓缂栧彿 | 鍚嶇О | 閫氫織瑙ｉ噴 | 鏈」鐩搴旈槻鎶?|
|----------|------|----------|----------------|
| A01 | 澶辨晥鐨勮闂帶鍒?| 鏅€氱敤鎴疯兘鏀瑰埆浜烘枃绔?| 瓒婃潈鏍￠獙锛?6.8 鑺傦級 |
| A02 | 鍔犲瘑鏈哄埗澶辨晥 | 瀵嗙爜鏄庢枃瀛樻暟鎹簱 | BCrypt 鍔犵洂锛?6.4 鑺傦級 |
| A03 | 娉ㄥ叆 | SQL 娉ㄥ叆銆佸懡浠ゆ敞鍏?| MyBatis #{} 鍙傛暟鍖栵紙16.2 鑺傦級 |
| A04 | 涓嶅畨鍏ㄨ璁?| 娌℃湁闄愭祦銆佹病鏈夐攣 | 鐧诲綍闄愭祦锛?6.7 鑺傦級 |
| A05 | 瀹夊叏閰嶇疆閿欒 | 榛樿瀵嗙爜銆佽皟璇曟ā寮忓紑 | .env 闅旂锛?6.5 鑺傦級 |
| A06 | 鑷甫婕忔礊鍜岃繃鏃剁粍浠?| 鑰佺増鏈緷璧栨湁 CVE | pom.xml 鐢ㄦ渶鏂?LTS |
| A07 | 韬唤璁よ瘉澶辨晥 | Token 涓嶈兘鎾ら攢 | JWT 榛戝悕鍗曪紙16.5 鑺傦級 |
| A08 | 杞欢鍜屾暟鎹畬鏁存€уけ鏁?| 鍙嶅簭鍒楀寲婕忔礊 | 涓嶆帴鏀朵笉鍙俊瀵硅薄 |
| A09 | 瀹夊叏鏃ュ織鍜岀洃鎺х己澶?| 鏀诲嚮浜嗛兘涓嶇煡閬?| log.warn 鍏抽敭鎿嶄綔 |
| A10 | 鏈嶅姟绔姹備吉閫狅紙SSRF锛?| 璁╂湇鍔″櫒鍘昏闂唴缃?| URL 鐧藉悕鍗?|

鈿狅笍 **閲嶈瑙傚康**锛氬畨鍏ㄤ笉鏄煇涓?妯″潡"锛岃€屾槸娓楅€忓埌姣忎竴琛屼唬鐮侀噷鐨?鎬濈淮鏂瑰紡"銆傛湰椤圭洰浠?v1.10 寮€濮嬪氨涓€鐩村湪鍋氬畨鍏ㄥ姞鍥猴紝鍒?v1.34 宸茬粡杩唬浜?20 澶氭銆?
---

## 16.2 SQL 娉ㄥ叆闃叉姢

### 16.2.1 浠€涔堟槸 SQL 娉ㄥ叆

鍋囪鏈変竴娈垫嫾鎺?SQL 鐨勪唬鐮侊細

```java
// 鍗遍櫓鍐欐硶锛堜笉瑕佽繖鏍峰啓锛侊級
String sql = "SELECT * FROM sys_user WHERE username = '" + username + "'";
```

濡傛灉鏀诲嚮鑰呮妸 `username` 浼犳垚 `' OR '1'='1`锛屾渶缁堟嫾鍑烘潵鐨?SQL 鏄細

```sql
SELECT * FROM sys_user WHERE username = '' OR '1'='1'
```

`'1'='1'` 姘歌繙涓虹湡锛岃繖鏉?SQL 浼氭妸鏁村紶鐢ㄦ埛琛ㄦ煡鍑烘潵銆傛洿鐙犵殑鏀诲嚮鑰呯敋鑷宠兘浼?`'; DROP TABLE sys_user; --`锛岀洿鎺ユ妸琛ㄥ垹浜嗐€?
### 16.2.2 MyBatis 鐨?#{} 涓?${}

鏈」鐩娇鐢?MyBatis Plus锛屾墍鏈?SQL 鍙傛暟閮介€氳繃 `#{}` 鍗犱綅绗︿紶閫掋€?*杩欐槸鏈€閲嶈鐨勬敞鍏ラ槻鎶?*銆?
| 鍐欐硶 | 鏁堟灉 | 瀹夊叏鎬?|
|------|------|--------|
| `#{username}` | 缂栬瘧涓洪缂栬瘧璇彞鐨?`?` 鍗犱綅绗︼紝鍙傛暟鍊肩敱 JDBC 椹卞姩杞箟 | 瀹夊叏 |
| `${username}` | 鐩存帴鍋氬瓧绗︿覆鏇挎崲 | 鍗遍櫓 |

涓句釜渚嬪瓙锛屼笅闈㈣繖涓ゆ潯涔嶇湅涓€鏍凤細

```xml
<!-- 瀹夊叏锛氬弬鏁板寲鏌ヨ -->
<select id="findByUsername">
  SELECT * FROM sys_user WHERE username = #{username}
</select>

<!-- 鍗遍櫓锛氬瓧绗︿覆鎷兼帴 -->
<select id="findByUsername">
  SELECT * FROM sys_user WHERE username = '${username}'
</select>
```

绗竴鏉★紝鏃犺 `username` 鏄粈涔堝瓧绗︼紙鍝€曞甫鍗曞紩鍙凤級锛岄兘鍙細琚綋鎴?涓€涓€?澶勭悊锛涚浜屾潯锛屾敾鍑昏€呭畬鍏ㄨ兘鏀瑰彉 SQL 缁撴瀯銆?
### 16.2.3 椤圭洰涓殑瀹炶返

鏈」鐩殑鎵€鏈?Mapper 閮界户鎵胯嚜 `BaseMapper<T>`锛屾爣鍑?CRUD 鏂规硶锛坕nsert銆乽pdateById銆乻electById銆乻electList锛夐兘鏄?MyBatis Plus 鍐呯疆鐨勶紝鍏ㄩ儴浣跨敤棰勭紪璇?SQL锛岄浂鎷兼帴椋庨櫓銆?
鈿狅笍 **閾佸緥**锛氶櫎浜?`ORDER BY 瀛楁鍚峘銆乣琛ㄥ悕` 杩欑缁撴瀯鎬у唴瀹瑰锛?*浠讳綍鐢ㄦ埛杈撳叆閮戒笉鑳界敤 `${}`**銆傚鏋滀竴瀹氳鍋氬姩鎬佹帓搴忥紝鍔″繀鍏堢敤鐧藉悕鍗曟牎楠屽瓧娈靛悕銆?
---

## 16.3 XSS 璺ㄧ珯鑴氭湰闃叉姢锛堝熀浜庣湡瀹?HtmlSanitizer.java锛?
### 16.3.1 浠€涔堟槸 XSS

XSS锛圕ross-Site Scripting锛夌殑鏈川鏄?*璁╂祻瑙堝櫒鍘绘墽琛屾敾鍑昏€呮敞鍏ョ殑鑴氭湰**銆傛瘮濡傦細

- 鐢ㄦ埛 A 鍙戜簡涓€绡囨枃绔狅紝鏍囬閲屽啓浜?`<script>alert('琚敾鍑讳簡')</script>`
- 杩欐鏍囬琚師鏍峰瓨杩涙暟鎹簱
- 鐢ㄦ埛 B 鎵撳紑杩欑瘒鏂囩珷鍒楄〃锛屾祻瑙堝櫒鐪嬪埌 `<script>` 灏变細鎵ц
- 鏀诲嚮鑰呭彲浠ョ敤鑴氭湰鍋?B 鐨?Cookie銆佹敼 B 鐨勫瘑鐮併€佽浆璐︹€︹€?
XSS 鍦ㄥ崥瀹€佽瘎璁鸿繖绉嶅瘜鏂囨湰鍦烘櫙閲屾渶甯歌銆?
### 16.3.2 椤圭洰鐨勮В鍐虫柟妗堬細Jsoup 鐧藉悕鍗曡繃婊?
鏈」鐩湪 v1.10 寮曞叆 Jsoup 鍋?XSS 闃叉姢锛屾牳蹇冧唬鐮佸氨鍦?`HtmlSanitizer.java` 閲岋細

```java
@Component
public class HtmlSanitizer {

    /**
     * 瀹芥澗鐧藉悕鍗曪細鍏佽閮ㄥ垎 HTML 鏍囩锛堢敤浜庢枃绔犲唴瀹圭瓑瀵屾枃鏈級
     */
    private static final Safelist RELAXED_WHITELIST = Safelist.relaxed()
            .addTags("span", "div", "hr", "table", "thead", "tbody", "tr", "th", "td")
            .addAttributes("a", "href", "title", "target")
            .addAttributes("img", "src", "alt", "title", "width", "height")
            .addProtocols("img", "src", "http", "https")
            .addProtocols("a", "href", "http", "https", "mailto")
            .preserveRelativeLinks(false);

    /**
     * 涓ユ牸鐧藉悕鍗曪細瀹屽叏娓呯┖鎵€鏈?HTML 鏍囩锛堢敤浜庤瘎璁猴級
     */
    private static final Safelist STRICT_WHITELIST = Safelist.none();

    public String sanitizeRichText(String html) {
        if (html == null || html.isEmpty()) {
            return html;
        }
        return Jsoup.clean(html, RELAXED_WHITELIST);
    }

    public String sanitizePlainText(String text) {
        if (text == null || text.isEmpty()) {
            return text;
        }
        return Jsoup.clean(text, STRICT_WHITELIST);
    }
}
```

**涓ゅ鐧藉悕鍗曠殑璁捐鐞嗗康**锛?
1. **`RELAXED_WHITELIST`锛堝鏉撅級**锛氬厑璁告枃绔犳鏂囧嚭鐜?`<p>`銆乣<h1>`銆乣<img>` 杩欎簺甯歌瀵屾枃鏈爣绛撅紝浣嗙姝?`<script>`銆乣<iframe>`銆乣onclick=...` 绛夊嵄闄╁厓绱犮€?2. **`STRICT_WHITELIST`锛堜弗鏍硷級**锛氱敤浜庤瘎璁恒€佸垎绫诲悕绛変笉闇€瑕佸瘜鏂囨湰鐨勫満鏅紝**鎵€鏈?* HTML 鏍囩鍏ㄩ儴娓呮帀銆?
### 16.3.3 鍏抽敭缁嗚妭锛氶檺鍒跺浘鐗囧崗璁?
娉ㄦ剰杩欎竴琛岋細

```java
.addProtocols("img", "src", "http", "https")
```

杩欐槸 v1.10 涓€娆″畨鍏ㄥ鏌ュ悗涓撻棬鍔犵殑銆?*Jsoup 榛樿鍏佽 `data:` 鍗忚**锛屾敾鍑昏€呭彲鑳藉啓锛?
```html
<img src="data:image/svg+xml,<svg onload=alert(1)></svg>">
```

鍙厑璁?`http`銆乣https` 鍗忚鍚庯紝杩欑 bypass 灏辫鍫垫浜嗐€?
### 16.3.4 瀹為檯浣跨敤

鍦ㄦ枃绔?Service 閲岋細

```java
@Autowired
private HtmlSanitizer htmlSanitizer;

public void createPost(BlogPost post) {
    // 鏂囩珷鍐呭鏄瘜鏂囨湰锛屼娇鐢ㄥ鏉剧櫧鍚嶅崟
    post.setTitle(htmlSanitizer.sanitizePlainText(post.getTitle()));
    post.setContent(htmlSanitizer.sanitizeRichText(post.getContent()));
    post.setSummary(htmlSanitizer.sanitizePlainText(post.getSummary()));
    blogPostMapper.insert(post);
}
```

鈿狅笍 **杩囨护鐨勪綅缃?*锛氬繀椤诲湪**鍏ュ簱鍓?*杩囨护銆傚鏋滃彧鍦ㄥ墠绔睍绀烘椂杩囨护锛岀粫杩囬潪甯稿鏄擄紙姣斿鐩存帴鐢?Postman 璋冩帴鍙ｏ級銆?*姘歌繙涓嶈鐩镐俊鍓嶇**銆?
---

## 16.4 瀵嗙爜瀹夊叏

### 16.4.1 涓轰粈涔堜笉鑳芥槑鏂囧瓨瀵嗙爜

鏁版嵁搴撹鑴卞簱鐨勪簨缁忓父鍙戠敓銆傚鏋滀綘瀛樼殑鏄槑鏂囷紝鏀诲嚮鑰呮嬁鍒版暟鎹簱灏辨嬁鍒颁簡鎵€鏈夌敤鎴风殑瀵嗙爜 鈥斺€?鑰屼笖寰堝鐢ㄦ埛鍦ㄥ涓綉绔欑敤鍚屼竴涓瘑鐮侊紝浣犺繕杩炵疮浜嗗埆鐨勭綉绔欍€?
### 16.4.2 BCrypt 鍔犵洂 + 12 杞?
鏈」鐩湪 `SecurityConfig` 涓厤缃細

```java
@Bean
public PasswordEncoder passwordEncoder() {
    // 寮哄害 12锛屾洿瀹夊叏
    return new BCryptPasswordEncoder(12);
}
```

**BCrypt 涓夊ぇ鐗规€?*锛?
1. **鍔犵洂**锛氭瘡娆″姞瀵嗛兘鑷姩鐢熸垚涓嶅悓鐨勯殢鏈虹洂锛屾墍浠ュ悓涓€涓瘑鐮?123456"涓ゆ鍔犲瘑缁撴灉涓嶅悓銆?2. **鎱㈠嚱鏁?*锛?2 杞?BCrypt 澶х害闇€瑕?200~300 姣銆傛敾鍑昏€呭氨绠楁嬁鍒板搱甯岋紝鏆村姏鐮磋В涔熸瀬鎱€?3. **涓嶅彲閫?*锛氬彧鑳?楠岃瘉"瀵嗙爜锛屼笉鑳?杩樺師"瀵嗙爜銆傛墍浠?蹇樿瀵嗙爜"鍔熻兘鏄彂閭欢閲嶇疆锛屼笉鏄妸瀵嗙爜瀵勭粰浣犮€?
### 16.4.3 @JsonIgnore 闃插簭鍒楀寲娉勯湶

鍏夊姞瀵嗚繕涓嶅锛岃繕寰楅槻姝㈠瘑鐮佸搱甯岃搴忓垪鍖栧埌 JSON 杩斿洖缁欏墠绔€傜湅鏈」鐩?`SysUser` 瀹炰綋锛?
```java
@JsonIgnore
@TableField("password")
private String password;
```

`@JsonIgnore` 鏄?Jackson 鎻愪緵鐨勬敞瑙ｏ紝鍛婅瘔 JSON 搴忓垪鍖栧櫒锛?杩欎釜瀛楁姘歌繙涓嶈杈撳嚭"銆傚嵆浣夸綘涓嶅皬蹇?`return user`锛屽瘑鐮佷篃涓嶄細娉勯湶銆?
鈿狅笍 **鏇寸ǔ濡ュ仛娉?*锛氭案杩滀笉瑕佺洿鎺ヨ繑鍥?`SysUser`锛岃€屾槸杩斿洖 `UserVO`锛圴iew Object锛屼笓闂ㄧ粰鍓嶇鐪嬬殑锛夈€傛湰椤圭洰鎵€鏈夎繑鍥炵敤鎴蜂俊鎭殑鎺ュ彛閮介伒瀹堣繖涓€瑙勫垯銆?
---

## 16.5 JWT 瀹夊叏

### 16.5.1 椤圭洰鐨勭幆澧冨彉閲忛殧绂?
JWT 瀵嗛挜涓嶈兘鍐欐鍦ㄤ唬鐮侀噷銆傛湰椤圭洰閫氳繃 `.env` 鏂囦欢 + `DotenvConfig` 鍔犺浇鍣ㄥ疄鐜板瘑閽ラ殧绂伙細

```
# .env.example
JWT_SECRET=your_jwt_secret_key_here_minimum_32_characters
JWT_EXPIRATION=86400000
JWT_REFRESH_EXPIRATION=604800000
```

鍚姩鏃?`EnvValidationConfig` 浼氬厛鏍￠獙锛?
```java
if (isBlank(jwtSecret)) {
    log.error("   鉁?JWT_SECRET 鏈厤缃?);
    hasError = true;
}
// 鈥︹€?if (hasError) {
    throw new IllegalStateException("鐜鍙橀噺閰嶇疆涓嶅畬鏁达紝鍚姩澶辫触");
}
```

鍙 `JWT_SECRET` 娌￠厤锛屽簲鐢ㄧ洿鎺ュ惎鍔ㄥけ璐ャ€傝繖绉?蹇€熷け璐?锛坒ail-fast锛夋€濇兂鑳介伩鍏嶇嚎涓婄幆澧冭８濂斻€?
鈿狅笍 **瀵嗛挜闀垮害**锛欽WT HS256 绠楁硶瑕佹眰瀵嗛挜鑷冲皯 256 浣嶏紝涔熷氨鏄?**32 涓?ASCII 瀛楃**銆傜煭浜?jjwt 搴撲細鐩存帴鎶涘紓甯搞€?
### 16.5.2 JWT 榛戝悕鍗曟満鍒讹紙鎾ら攢 Token锛?
JWT 鐨勭棝鐐规槸"鏃犵姸鎬? 鈥斺€?Token 涓€鏃︾鍙戯紝鍒版湡鍓嶅氨涓€鐩存湁鏁堬紝**娌℃硶涓诲姩鎾ら攢**銆備絾鐢ㄦ埛鐧诲嚭銆佷慨鏀瑰瘑鐮併€佽灏佺鏃讹紝鏄庢槑搴旇璁╂棫 Token 绔嬪埢澶辨晥銆?
鏈」鐩敤"榛戝悕鍗?瑙ｅ喅杩欎釜闂銆俙JwtUtils` 缁存姢涓€涓?ConcurrentMap锛屽瓨鏀捐鎾ら攢鐨?Token锛?
```java
// 鐢ㄦ埛鐧诲嚭
public void logout(String token) {
    jwtUtils.revokeToken(token);  // 鍔犲叆榛戝悕鍗?}

// 楠岃瘉 Token 鏃?public boolean validateToken(String token) {
    if (jwtUtils.isBlacklisted(token)) {
        return false;
    }
    // 鈥︹€?}
```

浣嗛粦鍚嶅崟浼氳秺鏉ヨ秺澶э紝鎵€浠ユ湰椤圭洰鐢?`JwtSchedulerConfig` 瀹氭椂娓呯悊锛?
```java
@Component
@EnableScheduling
public class JwtSchedulerConfig {

    @Autowired
    private JwtUtils jwtUtils;

    /**
     * 姣忓皬鏃舵竻鐞嗕竴娆¤繃鏈?Token 榛戝悕鍗?     */
    @Scheduled(fixedRate = 3600000) // 1 灏忔椂
    public void cleanExpiredTokens() {
        jwtUtils.cleanExpiredTokens();
    }
}
```

鈿狅笍 **鐢熶骇绾у缓璁?*锛氬唴瀛橀粦鍚嶅崟鍦ㄥ鏈洪儴缃叉椂涓嶄竴鑷达紝寤鸿鍗囩骇鍒?Redis锛堣嚜甯?TTL 杩囨湡锛夈€傛湰椤圭洰宸茶鍒掍絾灏氭湭闆嗘垚銆?
### 16.5.3 Refresh Token 杞崲锛坴1.29 淇锛?
鍒锋柊 Token锛坮efresh token锛夋湁鏁堟湡鏇撮暱锛? 澶╋級锛屾槸涓珮浠峰€肩洰鏍囷紝涓€鏃︽硠闇插嵄瀹虫洿澶с€傛墍浠ユ湰椤圭洰瀹炵幇浜?*杞崲锛坮otation锛?*锛?
> 鐢ㄤ竴娆″氨搴熷純锛屾瘡娆″埛鏂伴鍙?*鏂扮殑 access + 鏂扮殑 refresh**锛屾棫鐨?refresh 绔嬪嵆鍔犲叆榛戝悕鍗曘€?
```java
public TokenPair refreshToken(String oldRefreshToken) {
    // 1. 鏍￠獙鏃?refresh token
    Long userId = jwtUtils.parseUserId(oldRefreshToken);

    // 2. 绔嬪埢鎶婃棫 refresh 鍔犲叆榛戝悕鍗曪紙闃叉閲嶆斁锛?    jwtUtils.revokeToken(oldRefreshToken);

    // 3. 棰佸彂鏂扮殑 access + refresh
    String newAccessToken = jwtUtils.generateAccessToken(userId);
    String newRefreshToken = jwtUtils.generateRefreshToken(userId);

    return new TokenPair(newAccessToken, newRefreshToken);
}
```

### 16.5.4 鍏堥獙绛惧啀鏌ラ粦鍚嶅崟锛坴1.34 淇锛?
v1.34 淇浜嗕竴涓綔鍦?bypass锛氬師鏈粦鍚嶅崟鏌ヨ鐢ㄧ殑鏄?Token 瀛楃涓叉湰韬紝鏀诲嚮鑰呭彲鑳戒吉閫犱釜鐪嬭捣鏉ュ儚 Token 鐨勫瓧绗︿覆鍘?鏌ラ粦鍚嶅崟"锛岀粫杩囬€昏緫銆?
淇鏂规硶鏄厛鍋氱鍚嶉獙璇侊紝楠岀閫氳繃鐨勬墠鏌ラ粦鍚嶅崟锛?
```java
public boolean validateToken(String token) {
    try {
        // 1. 鍏堥獙璇佺鍚嶏紙浼€犵殑 Token 鍦ㄨ繖閲屽氨琚嫆浜嗭級
        Claims claims = Jwts.parser()
                .verifyWith(secretKey)
                .build()
                .parseSignedClaims(token)
                .getPayload();

        // 2. 楠岀閫氳繃鍚庡啀鏌ラ粦鍚嶅崟
        if (isBlacklisted(token)) {
            return false;
        }
        return true;
    } catch (JwtException e) {
        return false;
    }
}
```

---

## 16.6 闃叉淇℃伅娉勯湶

### 16.6.1 鐧诲綍鍝嶅簲涓嶈繑鍥炴晱鎰熶俊鎭紙v1.29 淇锛?
v1.29 涔嬪墠锛岀櫥褰曟垚鍔熷悗杩斿洖鐨?JSON 鍖呭惈浜?email銆乺ole銆乸hone 绛夊瓧娈点€傝繖浜涗俊鎭竴鏃﹀湪鍓嶇 JS 閲岋紝娴忚鍣ㄨ皟璇曞伐鍏峰氨鑳界湅鍒帮紝鏅€氱敤鎴疯兘鐪嬪埌鑷繁鐨勬病闂锛屼絾鏈変簺瀛楁锛堝 `loginFailCount`锛夊睘浜庡唴閮ㄥ疄鐜帮紝涓嶈鏆撮湶銆?
淇鍚庡彧杩斿洖蹇呰淇℃伅锛?
```java
public LoginResponseVO login(LoginRequest request) {
    // 鈥︹€﹂獙璇侀€昏緫
    LoginResponseVO vo = new LoginResponseVO();
    vo.setUserId(user.getId());
    vo.setUsername(user.getUsername());
    vo.setNickname(user.getNickname());
    vo.setAvatar(user.getAvatar());
    vo.setAccessToken(accessToken);
    vo.setRefreshToken(refreshToken);
    // 涓嶅啀杩斿洖 email銆乺ole銆乸hone 绛?    return vo;
}
```

### 16.6.2 鐢ㄦ埛鏋氫妇闃叉姢

娉ㄥ唽鎺ュ彛鐨勫父瑙佹紡娲烇細

- 鐢ㄦ埛鍚嶅凡瀛樺湪 鈫?杩斿洖 "鐢ㄦ埛鍚嶅凡琚敞鍐?
- 鐢ㄦ埛鍚嶄笉瀛樺湪 鈫?杩斿洖 "娉ㄥ唽鎴愬姛"

鏀诲嚮鑰呯敤鑴氭湰鏋氫妇涓€涓囦釜甯歌鐢ㄦ埛鍚嶏紝灏辫兘鐭ラ亾鍝簺宸茬粡瀛樺湪 鈥斺€?杩欏彨**鐢ㄦ埛鏋氫妇锛坲ser enumeration锛?*銆?
鏈」鐩殑淇鏂规锛氭敞鍐屽け璐ヤ竴寰嬭繑鍥為€氱敤閿欒锛?
```java
if (existingUser != null) {
    // 涓嶆毚闇?鐢ㄦ埛鍚嶅凡瀛樺湪"
    throw new BusinessException(400, "娉ㄥ唽澶辫触锛岃绋嶅悗閲嶈瘯");
}
```

鐧诲綍鎺ュ彛鍚岀悊锛氱敤鎴峰悕涓嶅瓨鍦ㄥ拰瀵嗙爜閿欒锛?*杩斿洖瀹屽叏鐩稿悓鐨勯敊璇俊鎭?*锛?鐢ㄦ埛鍚嶆垨瀵嗙爜閿欒"銆?
### 16.6.3 鍏ㄥ眬寮傚父鍏滃簳涓嶆毚闇插紓甯哥被鍚?
`GlobalExceptionHandler.java` 澶勭悊鎵€鏈夋湭鎹曡幏寮傚父锛?
```java
@ExceptionHandler(Exception.class)
public Result<?> handleException(Exception e) {
    log.error("绯荤粺寮傚父", e);  // 鏈嶅姟鍣ㄦ棩蹇楄褰曡缁嗗爢鏍?    return Result.error("鏈嶅姟鍣ㄧ箒蹇欙紝璇风◢鍚庨噸璇?); // 缁欑敤鎴风殑鍙嬪ソ鎻愮ず
}
```

鈿狅笍 **缁濆涓嶈**杩欐牱鍐欙細

```java
return Result.error("绯荤粺閿欒锛? + e.getMessage()); // 鍗遍櫓锛?```

`e.getMessage()` 鍙兘鍖呭惈 SQL 璇彞銆佹枃浠惰矾寰勩€佹暟鎹簱琛ㄥ悕锛屾敾鍑昏€呬粠涓彲鎺ㄦ柇鏋舵瀯缁嗚妭銆?
---

## 16.7 鐧诲綍闄愭祦涓庤处鎴烽攣瀹?
### 16.7.1 鏆村姏鐮磋В鐨勫嵄瀹?
濡傛灉鎺ュ彛瀵瑰悓涓€璐﹀彿鏃犻檺娆″皾璇曠櫥褰曪紝鏀诲嚮鑰呭彲浠ョ敤鑴氭湰涓€绉掑皾璇曚竴鍗冩锛屽父鐢ㄥ瘑鐮佸瓧鍏稿彧闇€鍑犲垎閽熷氨鑳借窇瀹屻€?
### 16.7.2 椤圭洰鐨勬柟妗堬細5 娆″け璐ラ攣 15 鍒嗛挓

`SysUser` 瀹炰綋閲屾湁杩欎袱涓瓧娈碉細

```java
private Integer loginFailCount;        // 澶辫触娆℃暟
private LocalDateTime lockedUntil;     // 閿佸畾鍒版湡鏃堕棿
```

鐧诲綍閫昏緫锛堢畝鍖栫増锛夛細

```java
public void login(String username, String password) {
    SysUser user = sysUserMapper.findByUsername(username);

    // 1. 鏄惁鍦ㄩ攣瀹氭湡鍐咃紵
    if (user.getLockedUntil() != null && user.getLockedUntil().isAfter(LocalDateTime.now())) {
        throw new BusinessException(423, "璐﹀彿宸查攣瀹氾紝璇?15 鍒嗛挓鍚庡啀璇?);
    }

    // 2. 鏍￠獙瀵嗙爜
    if (!passwordEncoder.matches(password, user.getPassword())) {
        // 澶辫触娆℃暟 +1锛堝師瀛愭洿鏂帮紝涓嬩竴鑺傝锛?        sysUserMapper.incrementLoginFailCount(user.getId());

        if (user.getLoginFailCount() + 1 >= 5) {
            // 閿佸畾 15 鍒嗛挓
            sysUserMapper.lockUser(user.getId(), LocalDateTime.now().plusMinutes(15));
        }
        throw new BusinessException(401, "鐢ㄦ埛鍚嶆垨瀵嗙爜閿欒");
    }

    // 3. 鐧诲綍鎴愬姛锛屾竻闆跺け璐ユ鏁?    sysUserMapper.resetLoginFailCount(user.getId());
}
```

### 16.7.3 鍘熷瓙鏇存柊闃插苟鍙?
濡傛灉涓や釜璇锋眰鍚屾椂鏉ワ紝鍒嗗埆璇诲埌 `loginFailCount=4`锛屽垎鍒?`+1` 鍚庡啓鍥?`5`锛屽氨鎴愪簡"涓㈠け鏇存柊"銆傛湰椤圭洰鐢?SQL 鐩存帴 `count = count + 1` 瑙ｅ喅锛?
```xml
<update id="incrementLoginFailCount">
    UPDATE sys_user
    SET login_fail_count = login_fail_count + 1
    WHERE id = #{userId}
</update>
```

鏁版嵁搴撶殑 UPDATE 鎿嶄綔鏈韩鍘熷瓙锛屼笉闇€瑕?Java 鍔犻攣銆?
鈿狅笍 **璁捐鍙栬垗**锛氶攣瀹氬埌鏈熸椂闂寸敤缁濆鏃堕棿锛坄lockedUntil`锛夛紝涓嶆槸璁℃暟鍣ㄥ€掓暟銆傝繖鏍锋湇鍔″櫒閲嶅惎涓嶄涪鐘舵€併€?
---

## 16.8 瓒婃潈闃叉姢

### 16.8.1 瓒婃潈鐨勪袱绉嶇被鍨?
- **姘村钩瓒婃潈**锛氱敤鎴?A 鎿嶄綔鐢ㄦ埛 B 鐨勮祫婧愶紙A 鍒犱簡 B 鐨勬枃绔狅級
- **鍨傜洿瓒婃潈**锛氭櫘閫氱敤鎴峰仛浜嗙鐞嗗憳鎵嶈兘鍋氱殑浜嬶紙鏅€氱敤鎴疯皟鐢?`/api/admin/banUser`锛?
### 16.8.2 椤圭洰鐨勭粺涓€澶勭悊

姣忎釜淇敼/鍒犻櫎鎺ュ彛蹇呴』鍋?鎵€鏈夋潈妫€鏌?锛?
```java
public void deletePost(Long postId) {
    Long currentUserId = SecurityUtils.getCurrentUserIdOrNull();
    if (currentUserId == null) {
        throw new BusinessException(401, "璇峰厛鐧诲綍");
    }

    BlogPost post = blogPostMapper.selectById(postId);
    if (post == null) {
        throw new BusinessException(404, "鏂囩珷涓嶅瓨鍦?);
    }

    // 鍏抽敭锛氬彧鏈変綔鑰呮垨绠＄悊鍛樿兘鍒?    SysUser currentUser = sysUserMapper.selectById(currentUserId);
    if (!post.getUserId().equals(currentUserId) && !"ADMIN".equals(currentUser.getRole())) {
        throw new BusinessException(403, "鏃犳潈鎿嶄綔");
    }

    blogPostMapper.deleteById(postId);
}
```

### 16.8.3 SecurityUtils 鍙栧綋鍓嶇敤鎴?
`SecurityUtils.getCurrentUserIdOrNull()` 浠?SecurityContext 涓彁鍙栧綋鍓嶇櫥褰曠敤鎴?ID銆傝繖涓柟娉?*涓嶆姏寮傚父锛岃繑鍥?null**锛屾柟渚胯皟鐢ㄦ柟鎸夐渶澶勭悊锛堝叕鍏辨帴鍙ｅ厑璁告父瀹㈣闂級銆?
鈿狅笍 **瀹℃煡娓呭崟**锛氭湰椤圭洰浠?v1.20 寮€濮嬪缓绔嬩簡"鏁忔劅鎺ュ彛瀹℃煡娓呭崟"锛屾瘡娆″彂鐗堝墠瀵规墍鏈夊啓鎺ュ彛閫愪竴纭鏉冮檺鏍￠獙鏄惁鍋ュ叏銆?
---

## 16.9 鏂囦欢涓婁紶瀹夊叏

### 16.9.1 涓夐亾鍏冲崱

鏂囦欢涓婁紶鏄敾鍑婚噸鐏惧尯锛屾湰椤圭洰璁句笁閬撳叧锛?
1. **绫诲瀷鐧藉悕鍗?*锛氬彧鍏佽鍥剧墖锛坖pg/png/gif/webp锛夊拰瑙嗛锛坢p4/avi锛?
```java
private static final Set<String> ALLOWED_IMAGE_EXT = Set.of("jpg", "jpeg", "png", "gif", "webp");

if (!ALLOWED_IMAGE_EXT.contains(ext.toLowerCase())) {
    throw new BusinessException(400, "涓嶆敮鎸佺殑鏂囦欢绫诲瀷");
}
```

2. **澶у皬闄愬埗**锛坄application.yml`锛夛細

```yaml
mybatis-plus:
  servlet:
    multipart:
      enabled: true
      max-file-size: 500MB
      max-request-size: 500MB
```

3. **閲嶅懡鍚嶉槻璺緞绌胯秺**锛氱敤 UUID 閲嶆柊鐢熸垚鏂囦欢鍚嶏紝閬垮厤鏀诲嚮鑰呬笂浼?`../../../etc/passwd` 杩欑鎭舵剰璺緞锛?
```java
String newName = UUID.randomUUID().toString().replace("-", "") + "." + ext;
File target = new File(uploadDir, newName);
```

### 16.9.2 闈欐€佽祫婧愯闂厤缃?
`WebMvcConfig` 鎶婁笂浼犵洰褰曟槧灏勬垚 HTTP 璺緞锛?
```java
@Override
public void addResourceHandlers(ResourceHandlerRegistry registry) {
    String projectRoot = System.getProperty("user.dir");
    String uploadPath = Paths.get(projectRoot, uploadBasePath).toString();

    registry.addResourceHandler("/uploads/**")
            .addResourceLocations("file:" + uploadPath + "/");
}
```

鈿狅笍 **鐢熶骇鐜鏈€浣冲疄璺?*锛氫笂浼犳枃浠朵笉鏀惧湪搴旂敤鏈嶅姟鍣紝鑰屾槸鏀惧璞″瓨鍌紙OSS銆丼3銆丮inIO锛夛紝鐙珛鍩熷悕锛屽苟閰嶇疆涓嶅厑璁告墽琛屼换浣曡剼鏈紙鍗充究涓婁紶鎴愬姛浜嗕篃鏃犳硶琚В鏋愪负鍙墽琛岋級銆?
---

### 绗?16 绔?瀹炴垬娓呭崟

- [ ] 鎵€鏈?SQL 鐢?`#{}` 鑰屼笉鏄?`${}`
- [ ] 鍏ュ簱鍓嶈皟鐢?`HtmlSanitizer` 杩囨护 HTML
- [ ] 瀵嗙爜鐢?`BCryptPasswordEncoder(12)` 鍔犲瘑
- [ ] 瀹炰綋鐨勫瘑鐮佸瓧娈靛姞 `@JsonIgnore`
- [ ] JWT 瀵嗛挜鏀?`.env`锛屽惎鍔ㄦ牎楠?- [ ] 鐢ㄦ埛鐧诲嚭瀹炵幇榛戝悕鍗曟挙閿€
- [ ] Refresh Token 涓€娆℃€ц疆鎹?- [ ] 鐧诲綍澶辫触 5 娆￠攣 15 鍒嗛挓
- [ ] 鎵€鏈夊啓鎺ュ彛鏍￠獙鎵€鏈夋潈
- [ ] 鏂囦欢涓婁紶鏍￠獙绫诲瀷 + 閲嶅懡鍚?
---

# 绗?17 绔?鎬ц兘浼樺寲鎶€宸?
鎬ц兘浼樺寲鐨勭涓€鍘熷垯锛?*涓嶈杩囨棭浼樺寲锛屽厛娴嬪嚭鐡堕鍐嶅姩鎵?*銆備絾鐞嗚В甯歌浼樺寲濂楄矾鑳藉府浣犲啓鍑?寮€绠辨€ц兘灏变笉宸?鐨勪唬鐮併€?
## 17.1 鏁版嵁搴撲紭鍖?
### 17.1.1 绱㈠紩璁捐

鏈」鐩暟鎹簱璁捐鐨勭储寮曟竻鍗曪細

| 琛?| 绱㈠紩瀛楁 | 绫诲瀷 | 鍘熷洜 |
|----|----------|------|------|
| `sys_user` | username | UNIQUE | 鐧诲綍鏌ユ壘 + 鍞竴绾︽潫 |
| `sys_user` | email | UNIQUE | 娉ㄥ唽鏍￠獙 + 鍞竴绾︽潫 |
| `blog_post` | user_id | NORMAL | 鏌?鎴戠殑鏂囩珷" |
| `blog_post` | category_id | NORMAL | 鎸夊垎绫荤瓫閫?|
| `blog_post` | create_time | NORMAL | 鎸夋椂闂存帓搴?|
| `blog_like` | (user_id, post_id) | UNIQUE | 闃查噸澶嶇偣璧?+ 澶嶅悎绱㈠紩 |
| `blog_post_tag` | (post_id, tag_id) | PRIMARY | 鍏宠仈琛ㄤ富閿?|

### 17.1.2 澶嶅悎绱㈠紩椤哄簭寰堝叧閿?
澶嶅悎绱㈠紩 `(user_id, post_id)` 鑳藉姞閫燂細

```sql
WHERE user_id = ? AND post_id = ?     -- 鍏ㄧ储寮曞懡涓?WHERE user_id = ?                     -- 鍛戒腑鍓嶇紑
```

浣?*涓嶈兘**鍔犻€燂細

```sql
WHERE post_id = ?  -- 鐢ㄤ笉鍒拌繖涓储寮曪紙鏈€宸﹀墠缂€鍘熷垯锛?```

鈿狅笍 **缁忛獙娉曞垯**锛氬鍚堢储寮曟妸"鍖哄垎搴﹂珮"鍜?缁忓父鍗曠嫭鏌?鐨勫瓧娈垫斁鍓嶉潰銆?
### 17.1.3 鍒敤 select *

```java
// 涓嶅ソ
List<BlogPost> posts = blogPostMapper.selectList(null);

// 鏇村ソ锛堝彧鏌ラ渶瑕佺殑瀛楁锛?LambdaQueryWrapper<BlogPost> wrapper = new LambdaQueryWrapper<>();
wrapper.select(BlogPost::getId, BlogPost::getTitle, BlogPost::getCreateTime);
```

鏂囩珷姝ｆ枃 `content` 瀛楁寰€寰€鍑?KB锛屽垪琛ㄩ〉鏍规湰鐢ㄤ笉鍒帮紝姣忔閮芥煡娴垂甯﹀鍜屽唴瀛樸€?
---

## 17.2 N+1 鏌ヨ闂

### 17.2.1 浠€涔堟槸 N+1

鏈€缁忓吀鐨勬€ц兘鍧戙€傚亣璁句綘鏌?100 绡囨枃绔狅紝鐒跺悗鎸ㄤ釜鏌ヤ綔鑰咃細

```java
// 鍙嶉潰绀轰緥
List<BlogPost> posts = blogPostMapper.selectList(null);  // 1 鏉?SQL
for (BlogPost post : posts) {
    SysUser author = sysUserMapper.selectById(post.getUserId()); // 100 鏉?SQL
    post.setAuthor(author);
}
// 涓€鍏?1 + 100 = 101 鏉?SQL
```

### 17.2.2 瑙ｅ喅锛氭壒閲忔煡璇?+ Map 缁勮

```java
List<BlogPost> posts = blogPostMapper.selectList(null);

// 1. 鏀堕泦鎵€鏈?userId
Set<Long> userIds = posts.stream()
        .map(BlogPost::getUserId)
        .collect(Collectors.toSet());

// 2. 涓€娆℃煡鍑烘墍鏈変綔鑰?List<SysUser> authors = sysUserMapper.selectBatchIds(userIds);

// 3. 杞?Map 鏂逛究鏌ユ壘
Map<Long, SysUser> authorMap = authors.stream()
        .collect(Collectors.toMap(SysUser::getId, u -> u));

// 4. 缁勮
for (BlogPost post : posts) {
    post.setAuthor(authorMap.get(post.getUserId()));
}
// 鎬诲叡 2 鏉?SQL锛屾棤璁烘枃绔犲灏?```

鈿狅笍 **妫€娴嬫柟娉?*锛氬紑鍚?SQL 鏃ュ織锛堣 17.4锛夛紝濡傛灉涓€涓帴鍙ｆ墦鍗板嚭鍑犲崄涓婄櫨鏉?SELECT锛屽鍗婃槸 N+1銆?
---

## 17.3 鍒嗛〉浼樺寲

### 17.3.1 PaginationInnerInterceptor

MyBatis Plus 鎻愪緵浜嗗垎椤垫彃浠讹細

```java
@Configuration
public class MybatisPlusConfig {
    @Bean
    public MybatisPlusInterceptor mybatisPlusInterceptor() {
        MybatisPlusInterceptor interceptor = new MybatisPlusInterceptor();
        interceptor.addInnerInterceptor(new PaginationInnerInterceptor(DbType.MYSQL));
        return interceptor;
    }
}
```

浣跨敤鏂瑰紡锛?
```java
Page<BlogPost> page = new Page<>(1, 10); // 绗?1 椤碉紝姣忛〉 10 鏉?Page<BlogPost> result = blogPostMapper.selectPage(page, null);
```

### 17.3.2 娣卞垎椤甸棶棰?
```sql
SELECT * FROM blog_post LIMIT 1000000, 10
```

MySQL 蹇呴』鎵弿鍓?100 涓囨潯鎵嶈兘璺宠繃鍘诲彇鍚?10 鏉°€傝В鍐虫€濊矾锛?*鐢ㄤ富閿繃婊?*

```sql
-- 宸茬煡涓婁竴椤垫渶鍚庝竴鏉?id 鏄?1000000
SELECT * FROM blog_post WHERE id > 1000000 LIMIT 10
```

杩欑鍙?娓告爣鍒嗛〉"鎴?keyset pagination"锛屾€ц兘鎭掑畾銆?
---

## 17.4 缂撳瓨绛栫暐

### 17.4.1 Spring Cache 娉ㄨВ锛堝凡瑙勫垝锛?
```java
@Cacheable(value = "post", key = "#postId")
public BlogPost getPostById(Long postId) {
    return blogPostMapper.selectById(postId);
}

@CacheEvict(value = "post", key = "#postId")
public void deletePost(Long postId) {
    blogPostMapper.deleteById(postId);
}
```

`@Cacheable`锛氬厛鏌ョ紦瀛橈紝娌℃湁灏辨墽琛屾柟娉曞苟缂撳瓨缁撴灉銆?`@CacheEvict`锛氭墽琛屾柟娉曞悗娓呴櫎缂撳瓨銆?
### 17.4.2 椤圭洰鐜扮姸

鏈」鐩洰鍓嶇敤 ConcurrentHashMap 鍋氬唴瀛樼紦瀛橈紙濡傞粦鍚嶅崟銆侀槻鍒锋寚绾癸級锛屽皻鏈泦鎴?Redis銆?*v1.31 瑙勫垝鎺ュ叆 Redis**锛屼綔涓猴細

- JWT 榛戝悕鍗曪紙鑷姩 TTL锛?- 鐑棬鏂囩珷鍒楄〃缂撳瓨
- 闄愭祦璁℃暟鍣?
---

## 17.5 鍑忓皯閲嶅璁＄畻

### 17.5.1 闃呰閲忓鍔狅細CAS 鏇夸唬 select-then-update锛坴1.14 淇锛?
v1.14 涔嬪墠鐨勪唬鐮侊紙鍏稿瀷鐨?TOCTOU 婕忔礊锛孴ime-of-check to time-of-use锛夛細

```java
// 鍙嶉潰绀轰緥
BlogPost post = blogPostMapper.selectById(postId);
post.setViewCount(post.getViewCount() + 1);
blogPostMapper.updateById(post);
// 100 涓苟鍙戣姹傛潵鏃讹紝浼氫涪澶卞ぇ閲忚鏁?```

淇鍚庣敤 SQL 鍘熷瓙鏇存柊锛?
```xml
<update id="incrementViewCount">
    UPDATE blog_post
    SET view_count = view_count + 1
    WHERE id = #{postId}
</update>
```

### 17.5.2 闃插埛锛欳oncurrentHashMap 缂撳瓨鎸囩汗

闃呰閲忎篃涓嶈兘璁╁悓涓€鐢ㄦ埛鐙傚埛銆傜敤 IP+userId 浣滀负 key 缂撳瓨锛?
```java
private final Map<String, Long> viewFingerprint = new ConcurrentHashMap<>();

public void addView(Long postId, Long userId, String ip) {
    String key = postId + ":" + userId + ":" + ip;
    Long lastView = viewFingerprint.get(key);
    long now = System.currentTimeMillis();

    if (lastView == null || now - lastView > 60 * 1000) {  // 1 鍒嗛挓鍐呬笉閲嶅璁℃暟
        blogPostMapper.incrementViewCount(postId);
        viewFingerprint.put(key, now);
    }
}
```

鈿狅笍 ConcurrentHashMap 浼氭棤闄愬闀匡紝闇€瑕佸畾鏈熸竻鐞嗭紙椤圭洰鏈夊畾鏃朵换鍔℃竻鐞嗚繃鏈?key锛夈€?
---

## 17.6 寮傛澶勭悊

### 17.6.1 閫氱煡鍙戦€佸紓姝ュ寲

鐢ㄦ埛鐐硅禐鏂囩珷鏃讹紝闇€瑕佺粰浣滆€呭彂閫氱煡銆傚鏋滃悓姝ュ彂锛屼富娴佺▼灏辫鎷栨參锛?
```java
// 鍚屾锛堜笉濂斤級
public void likePost(Long postId, Long userId) {
    blogLikeMapper.insert(new BlogLike(userId, postId));
    notificationService.sendLikeNotification(postId, userId);  // 闃诲锛?}
```

鏈」鐩敤 `@TransactionalEventListener` 寮傛澶勭悊锛?
```java
@Service
public class BlogLikeService {
    @Autowired
    private ApplicationEventPublisher eventPublisher;

    @Transactional
    public void likePost(Long postId, Long userId) {
        blogLikeMapper.insert(new BlogLike(userId, postId));
        // 鍙戝竷浜嬩欢锛堜簨鍔℃彁浜ゅ悗鎵嶄細瑙﹀彂锛?        eventPublisher.publishEvent(new LikeEvent(postId, userId));
    }
}

@Component
public class NotificationListener {
    @Async
    @TransactionalEventListener(phase = TransactionPhase.AFTER_COMMIT)
    public void onLike(LikeEvent event) {
        notificationService.sendLikeNotification(event.getPostId(), event.getUserId());
    }
}
```

**涓や釜鍏抽敭鐐?*锛?
- `AFTER_COMMIT`锛氫簨鍔℃彁浜ゅ悗鎵嶅彂閫氱煡銆傚惁鍒欑偣璧炴彃鍏ュけ璐ユ椂锛岄€氱煡鍗村凡缁忓彂浜嗐€?- `@Async`锛氭斁杩涚嚎绋嬫睜寮傛鎵ц锛屼笉闃诲涓绘祦绋嬨€?
璁板緱鍦?main 绫诲姞 `@EnableAsync`銆?
---

## 17.7 閿佺殑浼樺寲

### 17.7.1 缁嗙矑搴﹂攣

濡傛灉鐢ㄥ叏灞€閿侊紝鎵€鏈夌敤鎴风殑鎵€鏈夌偣璧炴搷浣滄帓闃熸墽琛?鈥斺€?鎬ц兘鐏鹃毦銆傛湰椤圭洰鎸?`postId` 鍒嗛攣锛?
```java
private final ConcurrentHashMap<Long, ReentrantLock> lockMap = new ConcurrentHashMap<>();

private ReentrantLock getLock(Long postId) {
    return lockMap.computeIfAbsent(postId, k -> new ReentrantLock());
}

public void likePost(Long postId, Long userId) {
    ReentrantLock lock = getLock(postId);
    lock.lock();
    try {
        // 涓寸晫鍖?    } finally {
        lock.unlock();
    }
}
```

涓嶅悓鏂囩珷鐨勫苟鍙戜簰涓嶅奖鍝嶃€?
### 17.7.2 闃查攣鍐呭瓨娉勬紡

ConcurrentHashMap 瓒婃潵瓒婂ぇ鎬庝箞鍔烇紵v1.20 鍔犱簡娓呯悊閫昏緫锛氭瘡娆?`getLock` 鏃舵鏌ラ攣鏄惁闀挎湡绌洪棽锛岀┖闂插氨娓呮帀銆傛垨鑰呯畝鍗曠矖鏆达細鐢?Guava 鐨?`Striped<Lock>`锛屽浐瀹氭暟閲忕殑閿侀殢鏈烘槧灏勩€?
---

## 17.8 鎵归噺鎿嶄綔

```java
// 鍙嶉潰锛氫竴鏉′竴鏉℃彃鍏?for (Long tagId : tagIds) {
    blogPostTagMapper.insert(new BlogPostTag(postId, tagId));
}
// 10 涓爣绛?= 10 鏉?SQL锛?0 娆＄綉缁滃線杩?
// 姝ｉ潰锛氭壒閲忔彃鍏?blogPostTagMapper.batchInsert(postId, tagIds);
```

```xml
<insert id="batchInsert">
    INSERT INTO blog_post_tag (post_id, tag_id) VALUES
    <foreach collection="tagIds" item="tagId" separator=",">
        (#{postId}, #{tagId})
    </foreach>
</insert>
```

涓€鏉?SQL 瑙ｅ喅锛屾€ц兘鎻愬崌鏁板崄鍊嶃€?
---

## 17.9 鍙浜嬪姟鐨勫ソ澶?
```java
@Transactional(readOnly = true)
public BlogPost getPostById(Long postId) {
    return blogPostMapper.selectById(postId);
}
```

`readOnly = true` 鍛婅瘔鏁版嵁搴撳拰 Spring锛?杩欐槸鍙锛屼笉瑕佸仛鑴忔鏌ャ€佷笉瑕侀攣琛?銆侻ySQL 鍙互璺敱鍒颁粠搴撱€?
鈿狅笍 鍐欐搷浣滃繀椤荤敤 `@Transactional(rollbackFor = Exception.class)` 淇濊瘉寮傚父鏃跺洖婊氾紙榛樿鍙洖婊?RuntimeException锛屼絾鍔?`rollbackFor = Exception.class` 鏇寸ǔ锛夈€?
---

### 绗?17 绔?瀹炴垬娓呭崟

- [ ] 楂橀鏌ヨ瀛楁寤虹储寮?- [ ] 鍒楄〃鏌ヨ涓嶅甫 select *
- [ ] 鍏宠仈鏌ヨ璀︽儠 N+1
- [ ] 鍒嗛〉鐢?MyBatis Plus 鐨?Page
- [ ] 璁℃暟鍣ㄧ敤 SQL `+1` 鑰屼笉鏄?read-modify-write
- [ ] 閫氱煡/閭欢鐢?`@Async` + `@TransactionalEventListener`
- [ ] 閿佸敖閲忕粏绮掑害
- [ ] 鎵归噺鎻掑叆鐢?foreach
- [ ] 鍙鏂规硶鍔?`readOnly = true`

---

# 绗?18 绔?娴嬭瘯涓庤皟璇?
## 18.1 涓夊眰娴嬭瘯閲戝瓧濉?
```
        /\
       /E2E\          灏戦噺绔埌绔祴璇曪紙鍚姩鏁翠釜搴旂敤锛屾ā鎷熺湡瀹炶姹傦級
      /----\
     /  闆嗘垚  \       涓瓑閲忛泦鎴愭祴璇曪紙澶氫釜缁勪欢閰嶅悎锛?    /---------\
   /   鍗曞厓娴嬭瘯  \    澶ч噺鍗曞厓娴嬭瘯锛堝崟涓被/鏂规硶锛?  /-------------\
```

| 绫诲瀷 | 閫熷害 | 瑕嗙洊鑼冨洿 | 鍐欏灏?|
|------|------|----------|--------|
| 鍗曞厓娴嬭瘯 | 姣绾?| 鍗曚釜鏂规硶 | 70% |
| 闆嗘垚娴嬭瘯 | 绉掔骇 | 澶氫釜缁勪欢 | 20% |
| 绔埌绔祴璇?| 鍒嗛挓绾?| 鏁翠釜绯荤粺 | 10% |

## 18.2 Spring Boot Test 鍩虹

鏈」鐩嚜甯︾殑娴嬭瘯绫?`EduProjectApplicationTests.java`锛?
```java
@SpringBootTest
class EduProjectApplicationTests {
    @Test
    void contextLoads() {
        // 杩欎竴涓祴璇曪紝鑳介獙璇佹暣涓?Spring 瀹瑰櫒鍚姩姝ｅ父
    }
}
```

`@SpringBootTest` 浼氬惎鍔ㄦ暣涓?Spring 涓婁笅鏂囷紝鍔犺浇鎵€鏈?Bean銆傝繖鏄?闆嗘垚娴嬭瘯"鐨勫叆闂ㄧ骇銆?
### 18.2.1 妯℃嫙 HTTP 璇锋眰锛歁ockMvc

```java
@SpringBootTest
@AutoConfigureMockMvc
class PostControllerTest {
    @Autowired
    private MockMvc mockMvc;

    @Test
    void getPostList_shouldReturn200() throws Exception {
        mockMvc.perform(get("/api/post/list"))
                .andExpect(status().isOk())
                .andExpect(jsonPath("$.code").value(200));
    }
}
```

`MockMvc` 涓嶄細鐪熻捣 HTTP 鏈嶅姟鍣紝浣嗚兘妯℃嫙鏁翠釜 Spring MVC 娴佺▼銆?
## 18.3 鍗曞厓娴嬭瘯 JUnit 5

```java
class HtmlSanitizerTest {

    private HtmlSanitizer sanitizer;

    @BeforeEach
    void setUp() {
        sanitizer = new HtmlSanitizer();
    }

    @Test
    void shouldRemoveScriptTag() {
        String dirty = "<p>hello</p><script>alert(1)</script>";
        String clean = sanitizer.sanitizeRichText(dirty);
        assertFalse(clean.contains("<script>"));
        assertTrue(clean.contains("<p>hello</p>"));
    }

    @Test
    void shouldHandleNull() {
        assertNull(sanitizer.sanitizeRichText(null));
    }
}
```

| 娉ㄨВ | 浣滅敤 |
|------|------|
| `@Test` | 鏍囪娴嬭瘯鏂规硶 |
| `@BeforeEach` | 姣忎釜娴嬭瘯鍓嶆墽琛岋紙鍒濆鍖栵級 |
| `@AfterEach` | 姣忎釜娴嬭瘯鍚庢墽琛岋紙娓呯悊锛?|
| `@BeforeAll` | 鏁翠釜娴嬭瘯绫诲墠鎵ц涓€娆?|
| `@DisplayName` | 缁欐祴璇曡捣浜虹被鍙鍚嶅瓧 |

甯哥敤鏂█锛?
```java
assertEquals(expected, actual);
assertTrue(condition);
assertNull(value);
assertThrows(BusinessException.class, () -> service.somethingThatThrows());
```

## 18.4 鎺ュ彛娴嬭瘯鏂瑰紡

### 18.4.1 Knife4j

鏈」鐩泦鎴愪簡 Knife4j锛岃闂?`http://localhost:8825/api/doc.html` 鍗冲彲鐪嬪埌鍏ㄩ儴鎺ュ彛鏂囨。銆?*鐐瑰嚮"璋冭瘯"灏辫兘鐩存帴鍙戣姹?*锛屼笉闇€瑕?Postman銆?
> 杩欐槸缁欏洟闃熴€佺粰鍓嶇銆佺粰娴嬭瘯鐨?鑷姪鐐归鏈?銆?
### 18.4.2 Postman

閫傚悎锛?
- 鍥㈤槦鍏变韩涓€濂楁帴鍙ｉ泦鍚?- 鍐欒嚜鍔ㄥ寲娴嬭瘯鐢ㄤ緥
- 璁剧疆鐜鍙橀噺锛坉ev / prod 鍒囨崲锛?
### 18.4.3 curl

鏈€蹇殑鍛戒护琛屽伐鍏凤細

```bash
# 鐧诲綍
curl -X POST http://localhost:8825/api/auth/login \
     -H "Content-Type: application/json" \
     -d '{"username":"admin","password":"admin123"}'

# 甯?token 璁块棶
curl http://localhost:8825/api/post/list \
     -H "Authorization: Bearer eyJhbGc..."
```

## 18.5 璋冭瘯鎶€宸?
### 18.5.1 IDEA 鏂偣璋冭瘯

1. 鍦ㄤ唬鐮佽鍙锋梺鐐逛竴涓嬶紝绾㈢偣鍑虹幇 = 鏅€氭柇鐐?2. 鐢?Debug 鏂瑰紡鍚姩锛堝皬铚樿洓鍥炬爣锛?3. 璇锋眰瑙﹀彂鍚庯紝绋嬪簭鍋滃湪鏂偣锛屽彲浠ヤ竴姝ユ鐪嬪彉閲?4. F8 = 鍗曟鎵ц涓嬩竴琛岋紱F7 = 杩涘叆鏂规硶鍐呴儴锛汧9 = 缁х画鐩村埌涓嬩竴涓柇鐐?
**鏉′欢鏂偣**锛氬彸閿柇鐐硅缃?`userId == 1L`锛屽彧鏈夋弧瓒虫潯浠舵墠鍋溿€?
### 18.5.2 鏃ュ織锛歋LF4J + Logback

Spring Boot 榛樿灏辩敤 SLF4J + Logback銆傛湰椤圭洰瑙勮寖锛?
```java
private static final Logger log = LoggerFactory.getLogger(MyService.class);
// 鎴栬€呯敤 Lombok锛?@Slf4j

log.debug("璋冭瘯淇℃伅: {}", obj);    // 寮€鍙戠幆澧冩墦鍗?log.info("鐢ㄦ埛 {} 鐧诲綍鎴愬姛", username);
log.warn("鐢ㄦ埛 {} 鐧诲綍澶辫触娆℃暟: {}", username, count);
log.error("鏁版嵁搴撳紓甯?, e);  // 寮傚父瀵硅薄鍗曠嫭浼狅紝浼氭墦鍗板爢鏍?```

鈿狅笍 **蹇呴』鐢?`{}` 鍗犱綅绗﹁€屼笉鏄瓧绗︿覆鎷兼帴**锛?
```java
// 涓嶅ソ锛堝嵆浣?debug 鍏抽棴浜嗭紝瀛楃涓蹭篃浼氳鎷兼帴锛?log.debug("鐢ㄦ埛 " + user.toJson() + " 鐧诲綍");

// 濂斤紙debug 鍏抽棴鏃舵牴鏈笉浼氭墽琛?toJson()锛?log.debug("鐢ㄦ埛 {} 鐧诲綍", user);
```

### 18.5.3 鏃ュ織绾у埆

| 绾у埆 | 鐢ㄩ€?|
|------|------|
| TRACE | 鏈€璇︾粏锛屽嚑涔庝笉鐢?|
| DEBUG | 寮€鍙戣皟璇曠敤 |
| INFO | 姝ｅ父涓氬姟娴佺▼鍏抽敭鑺傜偣 |
| WARN | 鍙枒浣嗚繕鑳界户缁繍琛?|
| ERROR | 鍑洪敊浜嗭紝蹇呴』鎺掓煡 |

鐢熶骇鐜閫氬父 INFO 绾у埆銆?
## 18.6 鏁版嵁搴撹皟璇?
### 18.6.1 寮€鍚?SQL 鏃ュ織

`application.yml` 閰嶇疆锛?
```yaml
mybatis-plus:
  configuration:
    log-impl: ${MYBATIS_SQL_LOG:org.apache.ibatis.logging.stdout.StdOutImpl}
```

閫氳繃 `.env` 鍒囨崲锛?
```
# 寮€鍚?MYBATIS_SQL_LOG=org.apache.ibatis.logging.stdout.StdOutImpl
# 鍏抽棴锛堢敓浜э級
MYBATIS_SQL_LOG=org.apache.ibatis.logging.nologging.NoLoggingImpl
```

寮€鍚悗鎺у埗鍙颁細鎵撳嚭姣忎竴鏉?SQL + 鍙傛暟 + 鑰楁椂锛屾槸鎺掓煡 N+1 鍜屾參鏌ヨ鐨勭鍣ㄣ€?
### 18.6.2 鏌ョ湅鎱㈡煡璇?
MySQL 鑷韩鏈夋參鏌ヨ鏃ュ織锛?
```sql
SHOW VARIABLES LIKE 'slow_query_log%';
SET GLOBAL slow_query_log = 'ON';
SET GLOBAL long_query_time = 1;  -- 瓒呰繃 1 绉掑氨璁板綍
```

涔嬪悗鐢?`EXPLAIN` 鍒嗘瀽鎱?SQL锛?
```sql
EXPLAIN SELECT * FROM blog_post WHERE user_id = 5;
```

閲嶇偣鐪?`type`锛堟渶濂芥槸 ref/range锛屾渶宸槸 ALL锛夊拰 `key`锛堢敤浜嗗摢涓储寮曪級銆?
## 18.7 甯歌 Bug 鎺掓煡

### 18.7.1 鍚姩鎶ラ敊

| 鎶ラ敊 | 鍘熷洜 | 瑙ｅ喅 |
|------|------|------|
| `Port 8825 already in use` | 绔彛琚崰 | 鏀?SERVER_PORT 鎴栨潃杩涚▼ |
| `Failed to configure DataSource` | DB_PASSWORD 涓虹┖ | 妫€鏌?.env |
| `JWT secret cannot be null` | JWT_SECRET 娌￠厤 | 妫€鏌?.env |
| `ClassNotFoundException` | 渚濊禆鍐茬獊 | mvn dependency:tree 鏌ラ噸澶?|

### 18.7.2 杩愯鏃?
- **NullPointerException**锛氱敤 IDEA 鐨?NullAway"鎻掍欢棰勯槻锛屾垨鐢?Optional
- **SQLSyntaxErrorException**锛氬線寰€鏄瓧娈靛悕鍐欓敊銆丼QL 鍏抽敭瀛楀啿绐侊紙濡?`order` 鏄叧閿瓧锛?- **DuplicateKeyException**锛氬敮涓€绱㈠紩鍐茬獊锛屾甯稿鐞嗭紙鎹曡幏 + 鍙嬪ソ鎻愮ず锛?
### 18.7.3 JWT 401 鎺掓煡

鎸変互涓嬮『搴忔鏌ワ細

1. 璇锋眰澶存槸鍚﹀甫浜?`Authorization: Bearer xxx`
2. token 鏄惁杩囨湡锛堣В鐮?https://jwt.io 鐪?exp锛?3. token 鏄惁鍦ㄩ粦鍚嶅崟锛堢敤鎴风櫥鍑鸿繃锛?4. JWT_SECRET 鏄惁鍙樹簡锛堝彉浜嗘墍鏈夋棫 token 閮藉け鏁堬級
5. 鏃堕挓鏄惁鍚屾锛堟湇鍔″櫒鏃堕棿鍋忓樊澶т細鍒ゅ畾杩囨湡锛?
---

### 绗?18 绔?瀹炴垬娓呭崟

- [ ] 鑷冲皯涓烘牳蹇?Service 鍐欏崟鍏冩祴璇?- [ ] 鐢?Knife4j 璧伴€氭瘡涓帴鍙?- [ ] 鏃ュ織鍏ㄩ儴鐢?`{}` 鍗犱綅绗?- [ ] 鐢熶骇鍏抽棴 SQL 鏃ュ織
- [ ] 瀛︿細鐢?EXPLAIN 鐪嬫墽琛岃鍒?- [ ] 甯哥敤蹇嵎閿細F8 鍗曟銆丗7 杩涘叆

---

# 绗?19 绔?閮ㄧ讲涓婄嚎

## 19.1 鎵撳寘娴佺▼

鍦ㄩ」鐩牴鐩綍鎵ц锛?
```bash
mvn clean package
```

瀹屾垚鍚庝細鍦?`target/` 鐩綍涓嬬敓鎴愶細

```
target/
鈹斺攢鈹€ edu_project-0.0.1-SNAPSHOT.jar  # 杩欏氨鏄儴缃茬敤鐨勫寘
```

杩欎釜 jar 鏄?Spring Boot 鐨?"fat jar"锛屽寘鍚簡鎵€鏈変緷璧?+ 鍐呭祵 Tomcat锛屽崟鏂囦欢灏辫兘璺戙€?
濡傛灉鎯宠烦杩囨祴璇曞姞閫燂細

```bash
mvn clean package -DskipTests
```

## 19.2 鏈嶅姟鍣ㄥ噯澶囷紙Linux锛?
### 19.2.1 瀹夎 JDK 21

Ubuntu / Debian锛?
```bash
sudo apt update
sudo apt install openjdk-21-jdk
java -version  # 楠岃瘉
```

CentOS / RHEL锛?
```bash
sudo yum install java-21-openjdk-devel
```

### 19.2.2 瀹夎 MySQL 8

```bash
sudo apt install mysql-server-8.0
sudo systemctl start mysql
sudo mysql_secure_installation
```

### 19.2.3 鍒涘缓鏁版嵁搴?
```sql
CREATE DATABASE campus_blog DEFAULT CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci;
CREATE USER 'campus_blog'@'%' IDENTIFIED BY 'YourStrongPassword2026!';
GRANT ALL PRIVILEGES ON campus_blog.* TO 'campus_blog'@'%';
FLUSH PRIVILEGES;
```

鐒跺悗瀵煎叆椤圭洰鑷甫鐨?鏁版嵁搴撹〃.sql"寤鸿〃銆?
## 19.3 鐜鍙橀噺閰嶇疆

鎶?`.env.example` 澶嶅埗涓?`.env`锛?
```bash
cp .env.example .env
nano .env
```

鐢熶骇鐜蹇呴』淇敼鐨勯」锛?
```bash
DB_HOST=127.0.0.1
DB_PORT=3306
DB_NAME=campus_blog
DB_USERNAME=campus_blog
DB_PASSWORD=YourStrongPassword2026!         # 寮哄瘑鐮侊紒
JWT_SECRET=A_Very_Long_Random_String_64_chars_or_more_DON_T_use_default
JWT_EXPIRATION=86400000                      # 24 灏忔椂
JWT_REFRESH_EXPIRATION=604800000             # 7 澶?SERVER_PORT=8825
CORS_ALLOWED_ORIGINS=https://campus-blog.com  # 鍏蜂綋鍩熷悕锛佷笉瑕?*
```

鈿狅笍 **閾佸緥**锛?
- `.env` 蹇呴』鍦?`.gitignore` 涓紝姘歌繙涓嶈兘鎻愪氦
- JWT_SECRET 鐢?`openssl rand -base64 64` 鐢熸垚
- 鏁版嵁搴撳瘑鐮佸繀椤诲己瀵嗙爜

## 19.4 鍚姩搴旂敤

### 19.4.1 nohup 鍚姩锛堢畝鍗曪級

```bash
nohup java -jar edu_project-0.0.1-SNAPSHOT.jar > app.log 2>&1 &
```

鍙傛暟瑙ｉ噴锛?
- `nohup`锛氬拷鐣ユ寕璧蜂俊鍙凤紝鍏抽棴 ssh 鍚庣▼搴忎粛鐒惰窇
- `>`锛氭爣鍑嗚緭鍑洪噸瀹氬悜鍒?app.log
- `2>&1`锛氶敊璇祦涔熷啓鍒?app.log
- `&`锛氬悗鍙拌繍琛?
鏌ョ湅鏃ュ織锛歚tail -f app.log`
鍋滄绋嬪簭锛歚ps -ef | grep edu_project` 鎵惧埌 PID 鍚?`kill <PID>`

### 19.4.2 systemd 鎵樼锛堟帹鑽愶級

鍒涘缓 `/etc/systemd/system/campus-blog.service`锛?
```ini
[Unit]
Description=Campus Blog Forum
After=network.target mysql.service

[Service]
Type=simple
User=appuser
WorkingDirectory=/opt/campus-blog
EnvironmentFile=/opt/campus-blog/.env
ExecStart=/usr/bin/java -Xmx512m -jar /opt/campus-blog/edu_project-0.0.1-SNAPSHOT.jar
Restart=always
RestartSec=5
StandardOutput=append:/var/log/campus-blog/app.log
StandardError=append:/var/log/campus-blog/error.log

[Install]
WantedBy=multi-user.target
```

鍚敤锛?
```bash
sudo systemctl daemon-reload
sudo systemctl enable campus-blog
sudo systemctl start campus-blog
sudo systemctl status campus-blog
```

systemd 浼樺娍锛氬紑鏈鸿嚜鍚€佸穿婧冭嚜鍔ㄩ噸鍚€侀泦涓鐞嗘棩蹇椼€?
## 19.5 鍙嶅悜浠ｇ悊锛歂ginx

璁╃敤鎴疯闂?80/443 绔彛锛岀敱 Nginx 杞彂鍒?8825锛?
```nginx
server {
    listen 80;
    server_name campus-blog.com www.campus-blog.com;

    # HTTP 璺?HTTPS
    return 301 https://$server_name$request_uri;
}

server {
    listen 443 ssl http2;
    server_name campus-blog.com;

    ssl_certificate     /etc/letsencrypt/live/campus-blog.com/fullchain.pem;
    ssl_certificate_key /etc/letsencrypt/live/campus-blog.com/privkey.pem;

    # 鍓嶇闈欐€佹枃浠?    location / {
        root /var/www/campus-blog-frontend;
        try_files $uri $uri/ /index.html;
    }

    # 鍚庣 API
    location /api/ {
        proxy_pass         http://127.0.0.1:8825/api/;
        proxy_set_header   Host              $host;
        proxy_set_header   X-Real-IP         $remote_addr;
        proxy_set_header   X-Forwarded-For   $proxy_add_x_forwarded_for;
        proxy_set_header   X-Forwarded-Proto $scheme;

        client_max_body_size 500m;  # 澶ф枃浠朵笂浼?    }
}
```

### 19.5.1 HTTPS 璇佷功

鐢?Let's Encrypt 鍏嶈垂璇佷功锛?
```bash
sudo apt install certbot python3-certbot-nginx
sudo certbot --nginx -d campus-blog.com -d www.campus-blog.com
```

鑷姩缁湡锛?
```bash
sudo certbot renew --dry-run
```

## 19.6 璺ㄥ煙閰嶇疆锛圕ORS锛?
鏈」鐩?CORS 閫氳繃鐜鍙橀噺閰嶇疆锛?
```yaml
cors:
  allowed-origins: ${CORS_ALLOWED_ORIGINS:http://localhost:8080,http://127.0.0.1:8080}
```

鈿狅笍 **鐢熶骇鐜缁濆涓嶈兘鐢?`*` 閫氶厤绗?*锛?
```bash
# 閿欒
CORS_ALLOWED_ORIGINS=*

# 姝ｇ‘
CORS_ALLOWED_ORIGINS=https://campus-blog.com,https://www.campus-blog.com
```

甯?Cookie 鐨勮姹傦紙`credentials: true`锛夐厤鍚?`*` 鏄祻瑙堝櫒绂佹鐨勶紱瀹夊叏瑙掑害涔熺姝换鎰忕綉绔欒皟浣犵殑鎺ュ彛銆?
## 19.7 鐩戞帶涓庢棩蹇?
### 19.7.1 鏃ュ織鍒囧壊

璁?Logback 鑷姩鎸夋棩鏈熷垏鍓诧細

```xml
<appender name="FILE" class="ch.qos.logback.core.rolling.RollingFileAppender">
    <file>logs/app.log</file>
    <rollingPolicy class="ch.qos.logback.core.rolling.SizeAndTimeBasedRollingPolicy">
        <fileNamePattern>logs/app-%d{yyyy-MM-dd}.%i.log.gz</fileNamePattern>
        <maxFileSize>100MB</maxFileSize>
        <maxHistory>30</maxHistory>           <!-- 淇濈暀 30 澶?-->
        <totalSizeCap>10GB</totalSizeCap>     <!-- 鎬诲ぇ灏忎笂闄?-->
    </rollingPolicy>
    <encoder>
        <pattern>%d{yyyy-MM-dd HH:mm:ss} [%thread] %-5level %logger - %msg%n</pattern>
    </encoder>
</appender>
```

### 19.7.2 鍋ュ悍妫€鏌?
鍔犲叆渚濊禆锛?
```xml
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-actuator</artifactId>
</dependency>
```

璁块棶 `http://localhost:8825/api/actuator/health` 杩斿洖锛?
```json
{"status": "UP"}
```

鍙互鎺ュ叆鐩戞帶绯荤粺锛圥rometheus + Grafana锛夛紝鑷姩鍙戠幇鏈嶅姟鎸傛帀銆?
## 19.8 鏁版嵁搴撳浠?
姣忔棩鍏ㄥ浠借剼鏈?`backup.sh`锛?
```bash
#!/bin/bash
DATE=$(date +%Y%m%d)
BACKUP_DIR=/var/backup/mysql
mkdir -p $BACKUP_DIR

mysqldump -u campus_blog -p'YourStrongPassword2026!' campus_blog \
          --single-transaction \
          --routines \
          | gzip > $BACKUP_DIR/campus_blog_$DATE.sql.gz

# 淇濈暀鏈€杩?30 澶?find $BACKUP_DIR -name "*.sql.gz" -mtime +30 -delete
```

鍔犲叆 crontab 姣忓ぉ鍑屾櫒 3 鐐硅窇锛?
```cron
0 3 * * * /opt/scripts/backup.sh
```

## 19.9 鐗堟湰鍗囩骇娴佺▼

1. 鏈湴鎷夋柊浠ｇ爜銆佹祴璇曢€氳繃
2. `mvn clean package -DskipTests`
3. scp 鎶?jar 涓婁紶鍒版湇鍔″櫒
4. `sudo systemctl stop campus-blog`
5. 澶囦唤鏃?jar锛歚mv app.jar app.jar.bak`
6. 鏇挎崲鏂?jar
7. `sudo systemctl start campus-blog`
8. `tail -f /var/log/campus-blog/app.log` 纭鍚姩鎴愬姛
9. 鐢?curl 璺戜笅鍋ュ悍妫€鏌?
鈿狅笍 **閲嶈锛氬崌绾у墠涓€瀹氬厛澶囦唤鏁版嵁搴?*銆傚鏋滄柊鐗堟湰鏀逛簡琛ㄧ粨鏋勶紝鍥炴粴闇€瑕佹暟鎹簱涔熻兘鍥炪€?
---

## 19.10 Docker 瀹瑰櫒鍖栭儴缃?
椤圭洰鏀寔 Docker 閮ㄧ讲锛岄€傚悎灏忓瀷椤圭洰蹇€熶笂绾裤€?
### Dockerfile锛堥」鐩牴鐩綍锛?
```dockerfile
# 闃舵涓€锛氭瀯寤?FROM maven:3.9-eclipse-temurin-21-alpine AS builder
WORKDIR /app
COPY pom.xml .
RUN mvn dependency:go-offline
COPY src ./src
RUN mvn clean package -DskipTests

# 闃舵浜岋細杩愯
FROM eclipse-temurin:21-jre-alpine
WORKDIR /app
COPY --from=builder /app/target/edu_project-*.jar app.jar

# 鍙橀噺鐢?docker-compose 鐨?.env 娉ㄥ叆
ENV JWT_SECRET=placeholder
ENV DB_HOST=db
ENV SERVER_PORT=8825

EXPOSE 8825
ENTRYPOINT ["java", "-jar", "app.jar"]
```

### docker-compose.yml

```yaml
version: '3.8'
services:
  db:
    image: mysql:8.0
    restart: always
    environment:
      MYSQL_ROOT_PASSWORD: ${MYSQL_ROOT_PASSWORD}
      MYSQL_DATABASE: ${DB_NAME}
    volumes:
      - mysql_data:/var/lib/mysql
      - ./init.sql:/docker-entrypoint-initdb.d/init.sql:ro
    ports:
      - "3306:3306"
    networks:
      - blog-net

  app:
    build: .
    restart: always
    depends_on:
      db:
        condition: service_healthy
    env_file:
      - .env
    environment:
      DB_HOST: db
      DB_PORT: 3306
      DB_NAME: ${DB_NAME}
      DB_USERNAME: root
      DB_PASSWORD: ${MYSQL_ROOT_PASSWORD}
    ports:
      - "8825:8825"
    networks:
      - blog-net

volumes:
  mysql_data:

networks:
  blog-net:
    driver: bridge
```

### 閮ㄧ讲姝ラ

```bash
# 1. 澶嶅埗鐜鍙橀噺妯℃澘
cp .env.example .env
# 缂栬緫 .env锛屽～鍏ョ湡瀹炲瘑鐮侊紙鐢熶骇鐜鍔″繀淇敼锛?
# 2. 鍚姩
docker compose up -d --build

# 3. 鏌ョ湅鏃ュ織
docker compose logs -f app

# 4. 鍋ュ悍妫€鏌?curl http://localhost:8825/api/doc.html

# 5. 鍋滄
docker compose down
```

鈿狅笍 鐢熶骇鐜浣跨敤 Docker 閮ㄧ讲鏃讹紝寤鸿锛?- `.env` 涓嶈鎻愪氦鍒?Git锛堝凡鍦?`.gitignore` 涓級
- MySQL 鏁版嵁閫氳繃 `volumes` 鎸佷箙鍖栵紝闃叉瀹瑰櫒閲嶅惎涓㈡暟鎹?- 鑰冭檻浣跨敤 Docker Swarm 鎴?Kubernetes 鍋氬鑺傜偣閮ㄧ讲

---

### 绗?19 绔?瀹炴垬娓呭崟

- [ ] mvn clean package 鎵撳寘鎴愬姛
- [ ] 鏈嶅姟鍣ㄨ濂?JDK 21 + MySQL 8
- [ ] .env 閰嶅ソ涓斾笉娉勯湶
- [ ] systemd 鎵樼搴旂敤
- [ ] Nginx + HTTPS 鍙嶅悜浠ｇ悊
- [ ] CORS 闄愬畾鍏蜂綋鍩熷悕
- [ ] 鏃ュ織鍒囧壊
- [ ] 鏁版嵁搴撴瘡鏃ュ浠?- [ ] 鍗囩骇鍓嶅浠?
---

# 闄勫綍 A锛氬父瑙侀棶棰?FAQ

### Q1锛氬惎鍔ㄦ姤閿?`JWT secret cannot be null`

**鍘熷洜**锛歚.env` 鏂囦欢娌″垱寤猴紝鎴栬€呮病閰?`JWT_SECRET`銆?
**瑙ｅ喅**锛?
```bash
cp .env.example .env
# 缂栬緫 .env锛屽～鍏?JWT_SECRET锛堣嚦灏?32 瀛楃锛?```

濡傛灉鐢?IDEA 鍚姩杩樻槸鎶ラ敊锛屽彲鑳芥槸 IDEA 娌¤鍙?.env銆俙DotenvConfig.load()` 浼氳嚜鍔ㄤ粠 `user.dir` 鎵?.env锛岀‘璁?IDEA 鐨?Working Directory 璁剧殑鏄」鐩牴鐩綍銆?
### Q2锛歀ombok 涓嶇敓鏁堬紝`@Slf4j` 鎶ラ敊鎵句笉鍒?log

**鍘熷洜**锛欼DEA 娌¤ Lombok 鎻掍欢锛屾垨娌″紑 annotation processing銆?
**瑙ｅ喅**锛?
1. IDEA 鈫?Settings 鈫?Plugins锛屾悳 Lombok 瀹夎
2. Settings 鈫?Build 鈫?Compiler 鈫?Annotation Processors 鈫?Enable

### Q3锛欳onnection refused锛岃繛涓嶄笂鏁版嵁搴?
鎸夐『搴忔帓鏌ワ細

1. MySQL 鏈嶅姟璧锋病璧凤細`systemctl status mysql`
2. 闃茬伀澧欐嫤娌℃嫤锛?306 绔彛
3. MySQL 鐩戝惉鍦板潃锛歚bind-address` 鏀规垚 0.0.0.0
4. 鐢ㄦ埛鎺堟潈锛歚GRANT ALL ON campus_blog.* TO 'campus_blog'@'%';`
5. .env 閲?DB_HOST/DB_PORT/DB_USERNAME/DB_PASSWORD 鏄惁瀵?6. 鐢?`mysql -h IP -P 3306 -u campus_blog -p` 鍦ㄥ懡浠よ璇曡繛

### Q4锛歍oken expired

**姝ｅ父鎯呭喌**锛氶粯璁?access token 24 灏忔椂杩囨湡銆?
**瑙ｅ喅鏂规**锛?
- 璋冪敤 `/api/auth/refresh` 鍒锋柊锛堝墠绔嫤鎴?401 鑷姩鍒凤級
- 鎴栭噸鏂扮櫥褰?
### Q5锛氫笂浼犲ぇ鏂囦欢鎶?413 Request Entity Too Large

涓ゅ眰闄愬埗閮借鏀癸細

1. Spring Boot锛歚application.yml` 閲?max-file-size銆乵ax-request-size
2. Nginx锛歚client_max_body_size 500m;`

### Q6锛氳法鍩熸姤閿?CORS

閿欒淇℃伅褰㈠ `No 'Access-Control-Allow-Origin' header is present`銆?
**鎺掓煡**锛?
1. 鍚庣鏄惁閰嶇疆浜?CorsFilter锛堥」鐩嚜甯︼級
2. `CORS_ALLOWED_ORIGINS` 鏄惁鍖呭惈鍓嶇鍩熷悕
3. 鏄惁鐢ㄤ簡 `*` 閰嶅悎 `withCredentials`锛堜笉鍏佽锛?4. 棰勬璇锋眰 OPTIONS 鏄惁閫氳繃锛氭祻瑙堝櫒 Network 闈㈡澘鐪?
---

# 闄勫綍 B锛氶」鐩湳璇〃

| 鏈 | 鍏ㄧО | 閫氫織瑙ｉ噴 |
|------|------|----------|
| **IoC** | Inversion of Control | 鎺у埗鍙嶈浆锛氬璞′笉鍐嶈嚜宸?new 渚濊禆锛岀敱 Spring 瀹瑰櫒娉ㄥ叆 |
| **DI** | Dependency Injection | 渚濊禆娉ㄥ叆锛欼oC 鐨勫叿浣撳疄鐜版柟寮忥紙@Autowired锛?|
| **AOP** | Aspect-Oriented Programming | 闈㈠悜鍒囬潰缂栫▼锛氭妸鏃ュ織銆佷簨鍔＄瓑妯垏鍏虫敞鐐规娊鍑烘潵 |
| **ORM** | Object-Relational Mapping | 瀵硅薄鍏崇郴鏄犲皠锛氬疄浣撶被 鈫?鏁版嵁搴撹〃 |
| **JWT** | JSON Web Token | 鐢?JSON + 绛惧悕琛ㄧず鐨?Token锛岃嚜鍖呭惈锛屽墠鍚庣鍒嗙甯哥敤 |
| **BCrypt** | - | 涓€绉嶆參鍝堝笇绠楁硶锛屼笓涓哄瘑鐮佸瓨鍌ㄨ璁★紝鑷姩鍔犵洂 |
| **CSRF** | Cross-Site Request Forgery | 璺ㄧ珯璇锋眰浼€狅細璇遍獥鐢ㄦ埛鍦ㄥ凡鐧诲綍绔欑偣鍙戣姹?|
| **XSS** | Cross-Site Scripting | 璺ㄧ珯鑴氭湰锛氭敞鍏ヨ剼鏈娴忚鍣ㄦ墽琛?|
| **CORS** | Cross-Origin Resource Sharing | 璺ㄦ簮璧勬簮鍏变韩锛氭祻瑙堝櫒鍚屾簮绛栫暐鐨勬斁琛屾満鍒?|
| **CRUD** | Create/Read/Update/Delete | 澧炲垹鏀规煡 |
| **DTO** | Data Transfer Object | 鏁版嵁浼犺緭瀵硅薄锛氭帴鍙ｅ叆鍙?鍑哄弬鐢?|
| **VO** | View Object | 瑙嗗浘瀵硅薄锛氳繑鍥炲墠绔敤锛屼笉鏆撮湶鍐呴儴瀛楁 |
| **Entity** | - | 瀹炰綋绫伙細鐩存帴瀵瑰簲鏁版嵁搴撹〃 |
| **CRUD** | Create/Read/Update/Delete | 澧炲垹鏀规煡 |
| **TOCTOU** | Time-of-check to time-of-use | 妫€鏌ユ椂涓庝娇鐢ㄦ椂涔嬮棿鐨勫苟鍙戞紡娲?|
| **CAS** | Compare-And-Swap | 姣旇緝骞朵氦鎹紝鏃犻攣鍘熷瓙鎿嶄綔 |
| **CDN** | Content Delivery Network | 鍐呭鍒嗗彂缃戠粶锛屽姞閫熼潤鎬佽祫婧?|
| **SSL/TLS** | - | HTTPS 鍔犲瘑鍗忚 |
| **REST** | Representational State Transfer | 涓€绉?API 璁捐椋庢牸锛孶RL 琛ㄧず璧勬簮 |
| **Bean** | - | Spring 瀹瑰櫒绠＄悊鐨勫璞?|
| **Bootstrap** | - | Spring Boot 鍚姩杩囩▼ |

---

# 鍚庤锛氫綘鐨勬垚闀夸箣璺?
鎭枩锛佷綘鍧氭寔璇诲畬浜嗚繖鏈功銆備粠鐜鎼缓銆丣ava 鍩虹銆丼pring Boot 鏍稿績锛屽埌瀹夊叏鍔犲浐銆佹€ц兘浼樺寲銆佷笂绾块儴缃?鈥斺€?浣犲凡缁忚蛋瀹屼簡涓€涓?Java 鍚庣寮€鍙戣€呮渶閲嶈鐨勫叆闂ㄦ梾绋嬨€?
浣嗚繖鍙槸璧风偣銆?
## 鎺ヤ笅鏉ュ浠€涔?
鎸夋帹鑽愰『搴忥細

1. **Redis**锛氱紦瀛樸€佸垎甯冨紡閿併€佹秷鎭槦鍒楀叆闂ㄣ€侀檺娴?2. **娑堟伅闃熷垪**锛歊abbitMQ / Kafka锛岃В鍐冲墛宄板～璋枫€佺郴缁熻В鑰?3. **鍒嗗竷寮忓熀纭€**锛欳AP 鐞嗚銆佹渶缁堜竴鑷存€с€佸垎甯冨紡浜嬪姟锛圫eata锛?4. **寰湇鍔?*锛歋pring Cloud锛圢acos銆丱penFeign銆丼entinel銆丟ateway锛?5. **瀹瑰櫒鍖?*锛欴ocker銆丏ocker Compose銆並ubernetes
6. **DevOps**锛欽enkins / GitHub Actions 鑷姩鍖栭儴缃?7. **鏁版嵁搴撹繘闃?*锛氬垎搴撳垎琛紙ShardingSphere锛夈€佽鍐欏垎绂?8. **JVM 璋冧紭**锛氬瀮鍦惧洖鏀躲€佸唴瀛樻ā鍨嬨€佹€ц兘璇婃柇锛圓rthas銆丣Profiler锛?
## 鎺ㄨ崘瀛︿範璧勬簮

- **Spring 瀹樻柟鏂囨。**锛歨ttps://spring.io/projects/spring-boot 鈥斺€?浠讳綍涓枃鏁欑▼閮芥瘮涓嶄笂瀹樻柟鏂囨。鏉冨▉
- **Spring Boot 绀轰緥**锛歨ttps://github.com/spring-projects/spring-boot/tree/main/spring-boot-samples
- **Awesome Java**锛歨ttps://github.com/akullpp/awesome-java 鈥斺€?鏁寸悊浜嗘捣閲忎紭绉€ Java 搴?- **OWASP**锛歨ttps://owasp.org/ 鈥斺€?瀹夊叏鏂归潰鐨勫湥缁?- **MySQL 瀹炴垬 45 璁?*锛堟瀬瀹㈡椂闂达級鈥斺€?鎶?MySQL 鐪熸璁查€忎簡
- **GitHub Trending**锛氭瘡澶╁幓鐪?Java 鍖猴紝璺熸渶鏂版疆娴?
## 涓€浜涜繃鏉ヤ汉鐨勮瘽

- **涓嶈鍥ゆ暀绋?*锛氫拱浜?100 涓绋嬩笉濡傛妸 1 涓」鐩仛瀹屻€傛湰涔︾殑椤圭洰灏辨槸鏈€濂界殑缁冧範瀵硅薄锛屾妸瀹冭窇璧锋潵銆佹敼璧锋潵銆佸姞鏂板姛鑳姐€?- **鎷ユ姳寮€婧?*锛氬湪 GitHub 涓婅浼樼椤圭洰婧愮爜锛堝 mall銆佽嫢渚濄€乯eecg-boot锛夛紝鐪嬬湅澶у叕鍙告€庝箞鍐欎唬鐮併€?- **澶氬啓銆佸鏀广€佸閲嶆瀯**锛氱涓€涓増鏈案杩滄槸涓戠殑銆傜湅鍒?v1.10 鈫?v1.34 涓€璺慨澶嶇棔杩逛簡鍚楋紵鐪熷疄椤圭洰灏辨槸杩欐牱闀垮ぇ鐨勩€?- **淇濇寔濂藉**锛氱鍒颁笉鎳傜殑鎶ラ敊锛屽埆鍙鍒剁櫨搴︼紝鐪嬪畬鎶ラ敊鐨勮嫳鏂?stack trace 鍜屽畼鏂规枃妗ｏ紝浣犱細姣?90% 鐨勪汉閮藉己銆?- **鍒€曢敊**锛氫綘鍐欑殑姣忎竴琛?bug锛岄兘鏄湭鏉ヤ笉鍐嶅啓 bug 鐨勮祫鏈€?
鏈€鍚庨€佷綘涓€鍙ヨ瘽锛屾槸鏈」鐩?`CLAUDE.md` 閲岀殑"寮€鍙戣崳鑰?锛屽笇鏈涗綘涔熻兘鍦ㄥ伐浣滀腑璺佃锛?
> 浠ョ瀻娓呮帴鍙ｄ负鑰伙紝浠ヨ鐪熸煡璇负鑽ｃ€?> 浠ユā绯婃墽琛屼负鑰伙紝浠ュ姹傜‘璁や负鑽ｃ€?> 浠ュ垱閫犳帴鍙ｄ负鑰伙紝浠ュ鐢ㄧ幇鏈変负鑽ｃ€?> 浠ヨ烦杩囬獙璇佷负鑰伙紝浠ヤ富鍔ㄦ祴璇曚负鑽ｃ€?> 浠ョ牬鍧忔灦鏋勪负鑰伙紝浠ラ伒寰鑼冧负鑽ｃ€?> 浠ュ亣瑁呯悊瑙ｄ负鑰伙紝浠ヨ瘹瀹炴棤鐭ヤ负鑽ｃ€?> 浠ョ洸鐩慨鏀逛负鑰伙紝浠ヨ皑鎱庨噸鏋勪负鑽ｃ€?> 浠ュ繕璁版洿鏂版枃妗ｄ负鑰伙紝浠ュ強鏃舵洿鏂版枃妗ｄ负鑽ｃ€?
鈥斺€?绁濅綘鍦?Java 鐨勪笘鐣岄噷璧板緱闀胯繙锛屽啓鍑鸿鑷繁楠勫偛鐨勪唬鐮併€?
**鍏ㄤ功瀹屻€?*

