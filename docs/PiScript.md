# PiScript

# 1. 개요

$[x2 :piscript:]

> 플레이 생활을 보다 즐기기 위한 스크립트

**아이스크립트**.

# 2. 주요 구문

* [연산자](연산자(AiScript).md)
* [변수 선언 및 자료형](변수_선언_및_자료형(AiScript).md)
* [함수 선언](함수_선언(AiScript).md)

* [print문](print(AiScript).md)
* [if문](if(AiScript).md)
* [for문](for(AiScript).md)
* [each문](each(AiScript).md)
* [loop문](loop(AiScript).md)

# 3. 내장 함수 및 변수

`:` 문자열은 파일 제목에선 `-`(하이픈) 으로 기입해주세요.

## 3.1 기본 내장 함수 및 변수

### 3.1.1 Core

* ✨ [Core:v](Core-v(AiScript).md)
* 📥 [Core:type](Core-type(AiScript).md)
* 📥 [Core:to_str](Core-to_str(AiScript).md)
* 📥 [Core:sleep](Core-sleep(AiScript).md)

### 3.1.2 Util

* 📥 [Util:uuid](Util-uuid(AiScript).md)

### 3.1.3 Json

* 📥 [Json:stringify](Json-stringify(AiScript).md)
* 📥 [Json:parse](Json-parse(AiScript).md)
* 📥 [Json:parsable](Json-parsable(AiScript).md)

### 3.1.4 Date

* 📥 [Date:now()](Date-now()(AiScript).md)
* 📥 [Date:year()](Date-year()(AiScript).md)
* 📥 [Date:month()](Date-month()(AiScript).md)
* 📥 [Date:weekDay()](Date-weekDay()(PiScript).md) 🍑
* 📥 [Date:day()](Date-day()(AiScript).md)
* 📥 [Date:hour()](Date-hour()(AiScript).md)
* 📥 [Date:minute()](Date-minute()(AiScript).md)
* 📥 [Date:second()](Date-second()(AiScript).md)
* 📥 [Date:daysFromEpoch()](Date-daysFromEpoch()(PiScript).md) 🍑
* 📥 [Date:dayOfYear()](Date-dayOfYear()(PiScript).md) 🍑
* 📥 [Date:getTime()](Date-getTime()(PiScript).md) 🍑
* 📥 [Date:parse()](Date-parse()(AiScript).md)

### 3.1.5 Math

* ✨ [Math:PI](Math-PI(AiScript).md)
* 📥 [Math:sin()](Math-sin()(AiScript).md)
* 📥 [Math:cos()](Math-cos()(AiScript).md)
* 📥 [Math:abs()](Math-abs()(AiScript).md)
* 📥 [Math:sqrt()](Math-sqrt()(AiScript).md)
* 📥 [Math:round()](Math-round()(AiScript).md)
* 📥 [Math:ceil()](Math-ceil()(AiScript).md)
* 📥 [Math:floor()](Math-floor()(AiScript).md)
* 📥 [Math:toFixed()](Math-toFixed()(PiScript).md) 🍑
* 📥 [Math:min()](Math-min()(AiScript).md)
* 📥 [Math:max()](Math-max()(AiScript).md)
* 📥 [Math:rnd()](Math-rnd()(AiScript).md)
* 📥 [Math:gen_rng()](Math-gen_rng()(AiScript).md)

### 3.1.6 Str

* ✨ [Str:lf](Str-lf(AiScript).md)
* ✨ [Str:lt](Str-lt(AiScript).md)
* ✨ [Str:gt](Str-gt(AiScript).md)
* 📥 [str.to_num()](str.to_num()(AiScript).md)
* 📥 [Str:parseFloat()](Str-parseFloat()(PiScript).md) 🍑
* 📥 [str.len](str.len(AiScript).md)
* 📥 [str.pick()](str.pick()(AiScript).md)
* 📥 [str.incl()](str.incl()(AiScript).md)
* 📥 [str.slice()](str.slice()(AiScript).md)
* 📥 [str.split()](str.split()(AiScript).md)
* 📥 [str.replace()](str.replace()(AiScript).md)
* 📥 [str.index_of()](str.index_of()(AiScript).md)
* 📥 [str.trim()](str.trim()(AiScript).md)
* 📥 [str.upper()](str.upper()(AiScript).md)
* 📥 [str.lower()](str.lower()(AiScript).md)
* 📥 [Str:regExReplace()](Str-regExReplace()(PiScript).md) 🍑
* 📥 [Str:URIReplace()](Str-URIReplace()(PiScript).md) 🍑
* 📥 [Str:encodeURI()](Str-encodeURI()(PiScript).md) 🍑
* 📥 [Str:encodeB64()](Str-encodeB64()(PiScript).md) 🍑
* 📥 [Str:decodeB64()](Str-decodeB64()(PiScript).md) 🍑

### 3.1.7 Arr

* 📥 [arr.len](arr.len(AiScript).md)
* 📥 [arr.push()](arr.push()(AiScript).md)
* 📥 [arr.unshift()](arr.unshift()(AiScript).md)
* 📥 [arr.pop()](arr.pop()(AiScript).md)
* 📥 [arr.shift()](arr.shift()(AiScript).md)
* 📥 [arr.concat()](arr.concat()(AiScript).md)
* 📥 [arr.join()](arr.join()(AiScript).md)
* 📥 [arr.slice()](arr.slice()(AiScript).md)
* 📥 [arr.incl()](arr.incl()(AiScript).md)
* 📥 [arr.map()](arr.map()(AiScript).md)
* 📥 [arr.filter()](arr.filter()(AiScript).md)
* 📥 [arr.reduce()](arr.reduce()(AiScript).md)
* 📥 [arr.find()](arr.find()(AiScript).md)
* 📥 [arr.reverse()](arr.reverse()(AiScript).md)
* 📥 [arr.copy()](arr.copy()(AiScript).md)
* 📥 [arr.sort()](arr.sort()(AiScript).md)

### 3.1.8 Obj

* 📥 [Obj:keys()](Obj-keys()(AiScript).md)
* 📥 [Obj:vals()](Obj-vals()(AiScript).md)
* 📥 [Obj:kvs()](Obj-kvs()(AiScript).md)
* 📥 [Obj:get()](Obj-get()(AiScript).md)
* 📥 [Obj:set()](Obj-set()(AiScript).md)
* 📥 [Obj:has()](Obj-has()(AiScript).md)
* 📥 [Obj:copy()](Obj-copy()(AiScript).md)

### 3.1.9 Async

* 📥 [Async:interval()](Async-interval()(AiScript).md)
* 📥 [Async:timeout()](Async-timeout()(AiScript).md)

## 3.2 Misskey에서 사용할 수 있는 내장 함수 및 변수

* ✨ [USER_ID](AS_USER_ID(AiScript).md)
* ✨ [USER_NAME](AS_USER_NAME(AiScript).md)
* ✨ [USER_USERNAME](USER_USERNAME(AiScript).md)
* ✨ [CUSTOM_EMOJI](CUSTOM_EMOJI(AiScript).md)
* 📥 [Mk:dialog()](Mk-dialog()(AiScript).md)
* 📥 [Mk:confirm()](Mk-confirm()(AiScript).md)
* 📥 [Mk:api()](Mk-api()(AiScript).md)
* 📥 [Mk:save()](Mk-save()(AiScript).md)
* 📥 [Mk:load()](Mk-load()(AiScript).md)
* 📥 [Mk:url()](Mk-url()(AiScript).md)
* 📥 [Mk:open_page()](Mk-open_page()(PiScript).md) 🍑
* 📥 [Mk:open_url()](Mk-open_url()(PiScript).md) 🍑
* 📥 [Mk:move_url()](Mk-move_url()(PiScript).md) 🍑
* 📥 [Mk:geolat()](Mk-geolat()(PiScript).md) 🍑
* 📥 [Mk:geolon()](Mk-geolon()(PiScript).md) 🍑
* 📥 [Mk:audio()](Mk-audio()(PiScript).md) 🍑
* 📥 [Mk:keyDown()](Mk-keyDown()(PiScript).md) 🍑
* 📥 [Mk:fetchMd()](Mk-fetchMd()(PiScript).md) 🍑
* 📥 [Mk:clipboard()](Mk-clipboard()(PiScript).md) 🍑

# 4. UI 컴포넌트

* [Ui:C:container](Ui-C-container(AiScript).md)
* [Ui:C:text](Ui-C-text(AiScript).md)
* [Ui:C:mfm](Ui-C-mfm(AiScript).md)
* [Ui:C:textarea](Ui-C-textarea(AiScript).md)
* [Ui:C:textInput](Ui-C-textInput(AiScript).md)
* [Ui:C:numberInput](Ui-C-numberInput(AiScript).md)
* [Ui:C:button](Ui-C-button(AiScript).md)
* [Ui:C:buttons](Ui-C-buttons(AiScript).md)
* [Ui:C:switch](Ui-C-switch(AiScript).md)
* [Ui:C:select](Ui-C-select(AiScript).md)
* [Ui:C:folder](Ui-C-folder(AiScript).md)
* [Ui:C:postFormButton](Ui-C-postFormButton(AiScript).md)
* [Ui:C:customChart](Ui-C-customChart(PiScript).md) 🍑

# 5. 관련 문서

* [PiScript](PiScript.md) : 아이스크립트의 확장판. [피치타르트](피치타르트.md)에서만 사용할 수 있습니다.
