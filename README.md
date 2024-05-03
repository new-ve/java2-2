# 황충은 학번 202330234

## 3월 15일
내용



# Markdown 문법

## 폰트관련 태그

# h1
## h2
### h3
#### h4
##### h5
###### h6

일반 글자는 그냥 작성 <br><br><br><br>
개행(newline)를 하려면
스페이스 2개 입력

*이탤릭체*
**굵게**
***이탤릭+볼드***

## 리스트(list)
1. 첫 번째 
2. 두 번째
3. 세 번째

* 첫 번째
    * 두 번째
        * 세 번째


## 코드블럭
```java
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello World");
    }
}
```

## 링크
[구글 링크](https://google.com)
[리스트](#markdown-문법)
[리트리버](./1.jpg)
[절대경로](https://dimg.donga.com/wps/NEWS/IMAGE/2023/06/22/119900215.1.jpg)

## 4/5
for-each

## 2차원 배열
    선언 : int intArray[][];
    생성 : int intArray[] = new int[2][5]   //배열 선언과 생성 동시
        intArray = new int[2][5]    //생성만

## 예외 
    실행 중 오동작이나 결과에 악영향 미치는 예상치 못한 상황 발생
        자바에선 실행 중 발생 에러 오류로 처리
    에러 처리 요구
    예외 처리
        발생한 예외에 대해 개발자가 작성한 프로그램 코드에서 대응하는 것
        try-catch-finally문 사용
        자바 플랫폼은 많은 예외를 클래스 형태로 제공
## 캡슐화
    객체보호
## 상속
    상위 개체 속성 하위 개체에 물려짐
    하위 개체가 상위 개체의 속성을 모두 가지는 관계
    상위 클래스 멤버 하위 클래스가 물려받음
## 다형성
    같은 이름의 메소드가 클래스 혹은 객체에 따라 다르게 구현되는 것
    사례
        메소드 오버로딩 : 한 클래스 내 같은 이름이지만 다르게 작동하는 여러 메소드
        메소드 오버라이딩 : 슈퍼 클래스의 메소드를 동일한 이름으로 서브 클래스마다 다르게 구현
## 객체 지향 언어 목적
    소프트웨어 생산성 향상
    소프트웨어 생명 주기 단축
        고속 생산 필요 증대
    객체 지향 언어 
        재사용 위한 여러 장치 내장
        재사용 부분수정 용이

## 절차 지향 
    작업 순서 표현 컴퓨터 명령 집합
    함수들의 집합으로 프로그램 작성
## 객체 지향
    컴퓨터가 수행하는 작업을 객체들간 상호 작용으로 표현
## 클래스 
    객체의 속성과 행위 선언
    객체의 설계도 혹은 틀
## 객체
    클래스의 틀로 찍어낸 실체 
    프로그램 실행 중 생성되는 실체
    메모리 공간을 갖는 구체적인 실체
    인스턴스라고도 부름
## 클래스
    class 키워드로 선언
    멤버 : 클래스 구성 요소
        필드와 메소드
    클래스에 대한 public 접근 지정 : 다른 모든 클래스에서 클래스 사용 허락
    멤버에 대한 public 접근 지정 : 다른 모든 클래스에게 멤버 접근 허용
## 생성자
    생성자명은 클래스명과 동일
    여러 개 작성 가능
    객체 생성시 한 번만 호출
    목적은 객체 생성 시 초기화 
    리턴 타입 지정 불가
## 객체 배열
    객체에 대한 레퍼런스 배열
## 객체 배열 생성 3 단계
    배열 레퍼런스 변수 선언
    레퍼런스 배열 생성
    배열의 각 원소 객체 생성
## 인자 전달
    객체의 레퍼런스만 전달
        매개 변수가 실인자 객체 공유
## 오버로딩
    한 클래스 내에서 두 개의 이름이 같은 메소드 작성
        메소드 이름 동일
        매개변수 개수 타입 다름
## 객체 치환은 객체 복사가 아님. 레퍼런스의 복사임.
## 객체 소멸
    new에 의해 할당 받은 객체와 배열 메모리를 자바 가상 기계로 되돌려 주는 행위
    소멸된 객체 공간은 가옹 메모리 포함
## 사용자 임의로 객체 소멸 안됨
    객체 소멸 연산자 비존재
    객체 소멸 가상 기계 고유 역할
    개발자에게는 매우 다행스러운 기능
    상황에 따라 단점
## 가비지
    레퍼런스가 하나도 없는 객체
    더 이상 접근불가로 사용불가 메모리
## 가비지 컬렉션
    자바 가상 기계의 가비지 컬렉터가 자동 가비지 수집, 변환

## 패키지
## 4/12
## 자바 접근 지정자
    4가지
        private, protected, public, default
    목적
        클래스나 일부 멤버 공개하여 다른 클래스 접근 허용
        캡슐화 정책 멤버 보호
    클래스 접근지정
        다른 클래스에서 사용 허용 여부 지정
            public
                다른 모든 클래스에게 접근 허용
            default
                같은 패키지의 클래스에만 접근 허용
            private
                동일 클래스 내에만 접근 허용
                상속 받은 서브 클래스에서 접근 불가
            protected
                같은 패키지 내 다른 모든 클래스에게 접근 허용
                상속 받은 서브 클래스는 다른 패키지에 있어도 접근 가능
##  static 멤버
        static 멤버 선언 예시
            class StaticSample {
                int n;
                void g() {...}

                static int m; static void f() {...}
            }
        객체 생성과 non-static 멤버의 생성
        static 멤버는 클래스당 하나만 생성
        객체들에 의해 공유됨
##    static 멤버 사용
        클래스 이름으로 접근 가능
        객체 멤버로 접근 가능
        non-static 멤버는 클래스 이름으로 접근 안 됨
##    static 메소드의 제약 조건 1
        static 메소드는 오직 static 멤버만 접근 가능
            객체가 생성되지 않은 상황에서도 static 메소드는 실행될 수 있기 때문에, non-static 멤버 활용 불가
            non-static 메소드는 static 멤버 사용 가능
##    static 메소드의 제약 조건 2
        static 메소드는 this 사용불가
            static 메소드는 객체 없이도 사용 가능하므로, this 레퍼런스 사용할 수 없음       
##  final 클래스와 메소드
        final 클래스 - 더 이상 클래스 상속 불가능
        final 메소드 - 더 이상 오버라이딩 불가능
    final 필드 
        상수선언
##  상속
        상속 선언
            extends 키워드로 선언
        클래스 다중 상속 불허
        C++는 다중 상속 가능
        자바는 interface의 다중 상속 허용
        모든 자바 클래스는 묵시적으로 Object클래스 상속받음
            java.lang.Object는 모든 클래스가 상속받음
##    서브 클래스 객체의 모양
##    슈퍼 클래스 멤버에 대한 서브 클래스의 접근
        슈퍼 클래스 private 멤버
            서브 클래스에서 접근 불가
##    서브 클래스 객체 생성 시
        슈퍼클래스 생성자와 서브클래스 생성자 모두 실행
        호출순서
            서브 클래스의 생성자 먼저 호출
            서브 클래스의 생성자는 실행 전 슈퍼 클래스 생성자 호출
        실행순서
            슈퍼 클래스의 생성자가 먼저 실행된 후 서브 클래스의 생성자 실행
##    슈퍼 클래스와 서브 클래스
        각각 여러 개의 생성자 작성 가능
##    서브 클래스의 객체가 생성될 때
        슈퍼 클래스 생성자 1개와 서브 클래스 생성자 1개가 실행
##    서브 클래스의 생성자와 슈퍼 클래스의 생성자가 결정되는 방식
        1.개발자의 명시적 선택
            서브 클래스 개발자가 슈퍼 클래스의 생성자 명시적 선택
            super() 키워드를 이용하여 선택
        2.컴파일러가 기본생성자 선택
            서브 클래스 개발자가 슈퍼 클래스의 생성자를 선택하지 않는 경우
            컴파일러가 자동으로 묵시적 선택
    super()
        서브 클래스에서 명시적으로 슈퍼 클래스 생성자 호출
## 업캐스팅
    서브 클래스의 레퍼런스를 슈퍼 클래스 레퍼런스에 대입
    슈퍼 클래스 레퍼런스로 서브 클래스 객체를 가리키게 되는 현상
## 다운캐스팅
    슈퍼 클래스 레퍼런스를 서브 클래스 레퍼런스에 대입
    업캐스팅한 것을 다시 원래대로 되돌리는 것
    반드시 명시적 타입 변환 지정
## 업캐스팅 레퍼런스로 객체 구별?
    업캐스팅된 레퍼런스로는 객체의 실제 타입 구별 어려움
## instanceof 연산자 
    instanceof 연산자
        레퍼런스가 가리키는 객체의 타입 식별
## 4/19
##    super 키워드로 슈퍼 클래스 멤버 접근
        super
            슈퍼 클래스의 멤버를 접근할 때 사용되는 레퍼런스
##    추상 클래스
        추상 메소드
            abstract로 선언된 메소드
##        온전한 클래스 아님-인스턴스 생성 불가
##        추상 클래스 상속
            추상 클래스를 상속받으면 추상 클래스 됨
            서브 클래스도 abstract로 선언해야 함
##        추상 클래스 구현 
            서브 클래스에서 슈퍼 클래스 추상 메소드 구현(오버라이딩)
            추상 클래스를 구현한 서브 클래스는 추상 클래스 아님
##    인터페이스 구성 요소
        상수
        추상 메소드
        defolt 메소드
##    인터페이스간 상속 가능
##    인터페이스 다중 상속 허용
##    패키지
        서로 관련된 클래스와 인터페이스를 컴파일한 클래스 파일들을 묶어 놓은 디렉터리
        하나의 응용프로그램은 한 개 이상의 패키지로 작성
        jar 파일로 압축할 수 있음
 ##   모듈 
        여러 패키지와 이미지 등의 자원을 모아 놓은 컨테이너
        하나의 모듈을 하나의 파일로 만들 수 있음
        자바 9부터 자바 API를 여러 모듈로 분8할(99개)
##    현실
        JAVA9부터 전면도입
        복잡한 개념 
        큰 자바 프로그램에는 적합
        현실적으로 여러 모듈로 나눌 필요 없음
##    자바 JDK에 제공되는 모듈 파일들
        jmods에 존재
##    다른 패키지 작성 클래스 사용
        import 이용X
        완전 경로명 소스 사용
        이용하면 위에 import 만 해주면 됨
##  5/3
##    컬렉션 자바 인터페이스와 클래스
        컬렉션은 제네릭 기법으로 구현
            제네릭
                특정 타입만 다루지 않고, 여러 종류의 타입으로 변신할 수 있도록 클래스나 메소드를 일반화시키는 기법
                클래스나 인터페이스 이름에 <E>,<K>,<V> 등 타입매개변수 포함
            제네릭 컬렉션 사례: 벡터 Vector<E>
                <E>에서 E에 구체적인 타입를 주어 구체적인 타입만 다루는 벡터로 활용
                    Vector<Integer>
                    Vector<>
            제네릭
                클래스나 메소드를 형판에서 찍어내듯이 생산할 수 있도록 일반적인 형판을 만드는 기법
                JDK 1.5부터 도입(2004년 기점)
                모든 종류의 데이터 타입을 다룰 수 있도록 일반화된 타입 매개 변수로 클래스(인터페이스)나 메소드를 작성하는 기법
                C++의 템플릿과 동일
            벡터 Vector<E>의 특징
                <E>에 사용할 요소의 특정 타입으로 구체화
                배열을 가변 크기로 다룰 수 있게 하는 컨테이너
                    배열의 길이 제한 극복
                    요소의 개수가 넘치면 자동으로 길이 조절
                요소 개체들을 삽입, 삭제, 검색하는 컨테이너
                    삽입, 삭제에 따라 자동으로 요소의 위치 조정
                Vector에 삽입 가능한 것
                    객체, null
            JDK 1.5이전
            기본 타입 데이터 Wrapper 객체화
            1.5부터는 기본 타입 가능
            JAVA7 이전은 타입 삽입
            JAVA7 이후 컴파일러 타입 추론 기능 추가
            10이후 var,지역변수 타입 추론
            ArrayList<E>
            가변 크기 배열을 구현한 클래스
                <E>에 요소로 사용할 특정 타입으로 구체화
            벡터와 거의 동일
                요소 삽입, 삭제 등 거의 동일
            HashMap
                키와 값의 쌍으로 구성되는 요소를 다루는 컬렉션
                삽입 및 검색이 빠른 특징
            제네릭 클래스 작성
                클래스 이름 옆에 일반화된 타입 매개 변수 추가
            제네릭 객체 생성 및 활용
                제네릭 타입에 구체적인 타입을 지정하여 객체를 생성하는 것을 구체화라고 함
            GLI 응용프로그램
                GLI
                    사용자가 편리하게 입출력 할 수 있도록 그래픽으로 화면을 구성하고, 마우스나 키보드로 입력받을 수 있도록 지원하는 사용자 인터페이스
                자바 언어에서 GLI 응용프로그램 작성
                    AWT와 Swing 패키지에 강력한 GUI 컴포넌트 제공 
                    쉬운 GUI 프로그래밍
            AWT와 Swing 패키지
                awt패키지 
                    자바가 처음 나왔을 때부터 배포된 패키지
            컨테이너
                다른 컴포넌트를 포함할 수 있는 GUI 컴포넌트
                다른 컨테이너에 포함될 수 있음
            컴포넌트
                컨테이너에 포함되어야 화면에 출력될 수 있는 GUI 개체 
                다른 컴포넌트를 포함할 수 없는 순수 컴포넌트
            스윙 프레임
                JFrame 클래스를 상속받은 클래스 작성
                    프레임의 크기 반드시 지정:setSize() 호출
                    프레임을 화면에 출력하는 코드 반드시 필요:setVisible(true) 호출
            프레임에 컴포넌트 붙이기
                타이틀 달기
                    super()나 setTitle() 이용
                컨텐트팬에 컴포넌트 달기
                    컨텐트팬이란?
                        -스윙 컴포넌트들이 부착되는 공간
                    컨텐트팬 알아내기
                        -스윙 프레임에 붙은 디폴트 컨텐트팬 알아내기
                    컨텐트팬에 컴포넌트 붙이기 
                    컨텐트팬 변경
