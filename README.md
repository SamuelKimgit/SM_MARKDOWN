# SM_MARKDOWN
SM_MARKDOWN

## 표 만들기
|왼쪽정렬|가운데정렬|오른쪽정렬|
|:---|:---:|---:|
|내용1내용1내용1|내용2내용2내용2|내용3내용3내용3|
|내용1내용1내용1|내용2내용2내용2|내용3내용3내용3|
|내용1내용1내용1|내용2내용2내용2|내용3내용3내용3|

## 이미지 삽입
![금](https://github.com/SamuelKimgit/SM_MARKDOWN/blob/main/gold_bar.png)

## 강조
굵게 표시 : **오늘은 즐거운 금요일 무야호**  
굵게 표시 : __오늘은 즐거운 금요일 무야호__

## 하이퍼링크 : [pcwk] -> Priview에 표시될 이름 (https://cafe.daum.net/pcwk "PCWK CAFE") -> ("url" "호버 시 나올 텍스트")
[pcwk](https://cafe.daum.net/pcwk "PCWK CAFE")

## 가로 선
---
***

## 코드블록 ``` 열고 ``` 닫아준다
```
public class Log4j2Mybatis {
	final static Logger LOG = LogManager.getLogger(Log4j2Mybatis.class);
	public static void main(String[] args) {
		System.out.println("----------------");
		LOG.debug("=======================");
		LOG.debug("=Log4j2Mybatis=");
		LOG.debug("=======================");
		
	}

}
```

## 순서가 있는 목록 : 번호가 나열되어 있지 않아도 자동으로 순서대로 나열
1. 아이템1  
3. 아이템2   
   9. 1단 하위 아이템  
      3. 2단 하위 아이템  
9. 아이템3

- 아이템1
+ 아이템2  
  - 1단계 하위 아이템
  * 2단계 하위 아이템

## 목록 : 기본적인 리스트 작성 방법 (아래 세가지 중 어느것을 사용해도 된다.불릿모양)
* 목록이름 
- 목록이름
+ 목록이름

## 인용상자 : > 내용 형식으로 인용 상자를 작성할 수 있다.
> 여기에 인용할 내용을 채워 넣으면 됩니다.  
빈 줄이 없으면 자동으로 인용상자에 포함이 됩니다.

## 문단 구분을 위한 강제 개행 : 줄의 마지막에 [Space bar] 두 번 이상 띄어쓰기를 하면 된다.  
가나

## 헤더 : #헤더이름 식으로 작성  
# 헤더1  
## 헤더2  
### 헤더3  
#### 헤더4  
##### 헤더5
