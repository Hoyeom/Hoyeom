[C#/기획] 기획과 개발을 배우고 있는 이동규 입니다.
========================================
🔎 정보
------

- 키 이슈로 4급 판정
- 산업기능요원 준비중
- 02년생 (으윽...월드컵 질문은 싫어요)
- 이메일 : [korehdrb@gmail.com](korehdrb@gmail.com)
- [Unity Learn](https://learn.unity.com/u/6016cfc7edbc2a08db00c5b0?tab=profile)
- 인프런에서 공부중 !!! 유니티 웨이브 화요일  간다ㅏㅏ

🐎 학습 중
---------

<img src = "https://img.shields.io/badge/-C%23%20-black?style=flat&logo=C%20Sharp" style="height : auto; margin-left : 2px; margin-right : 2px;"/><img src="https://img.shields.io/badge/Unity%20-%23000000.svg?&style=flat&logo=unity&logoColor=white" style="height : auto; margin-left : 2px; margin-right : 2px;"/><img src="https://img.shields.io/badge/-UniRx-black?style=flat&logo=unity" style="height : auto; margin-left : 2px; margin-right : 2px;"/><img src="https://img.shields.io/badge/-DOTween-black?style=flat&logo=unity" style="height : auto; margin-left : 2px; margin-right : 2px;"/><img src="https://img.shields.io/badge/-게임 기획-black?style=flat&" style="height : auto; margin-left : 2px; margin-right : 2px;"/>

![Hoyeom's Github stats](https://github-readme-stats.vercel.app/api?username=Hoyeom&show_icons=true&theme=radical)

## 기능 나열 (생각용)

### C#

<details>
<summary>자료형</summary>

|   자료형    |              최소값              |              최대값              |   크기   | 부호  |
|:--------:|:-----------------------------:|:-----------------------------:|:------:|:---:|
|  object  | Base type of all other types. | Base type of all other types. |        |  △  |
|   byte   |               0               |              255              |  8bit  |  X  |
|  sbyte   |             -128              |              127              |  8bit  |  O  |
|  short   |            -32,768            |            32,767             | 16bit  |  O  |
|  ushort  |               0               |            65,535             | 16bit  |  X  |
|   int    |        -2,147,483,648         |         2,147,483,647         | 32bit  |  O  |
|   uint   |               0               |         4,294,967,295         | 32bit  |  X  |
|   long   |  -9,223,372,036,854,775,808   |   9,223,372,036,854,775,807   | 64bit  |  O  |
|  ulong   |               0               |  18,446,744,073,709,551,615   | 64bit  |  X  |
|  float   |         -3.402823e38          |          3.402823e38          | 32bit  |  O  |
|  double  |     -1.79769313486232e308     |     1.79769313486232e308      | 64bit  |  O  |
| decimal  |     (+ or -)1.0 x 10e-28      |          7.9 x 10e28          | 128bit |  O  |
|   bool   |             False             |             True              |  8bit  |  X  |
|   char   |      Any valid character      |      Any valid character      | 16bit  |  X  |
|  string  |                               |                               |        |  X  |
| DateTime |       0:00:00am 1/1/01        |     11:59:59pm 12/31/9999     |        |  X  |

</details>

<details>
<summary>자료 구조</summary>

| 자료 구조  |               설명                |
|:------:|:-------------------------------:|
|   배열   |           크기가 정적인 배열            |
| 동적 배열  |         중간 삽입 삭제가 힘든 배열         |
| 연결 리스트 | 중간 삽입 삭제가 쉽지만 특정 값에 바로 접근 하기 힘듦 |

</details>

<details>
<summary>자료 구조 (Generic)</summary>

|           클래스           |                                 설명                                 |
|:-----------------------:|:------------------------------------------------------------------:|
| Dictionary<TKey,TValue> |                    키에 따라 구성된 키/값 쌍의 컬렉션을 나타냅니다.                    |
|         List<T>         | 인덱스로 액세스할 수 있는 개체 목록을 나타냅니다. 목록의 검색, 정렬 및 수정에 사용할 수 있는 메서드를 제공합니다. |
|        Queue<T>         |                   FIFO(선입선출) 방식의 개체 컬렉션을 나타냅니다.                    |
| SortedList<TKey,TValue> |       연관된 IComparer<T> 구현을 기반으로 키에 따라 정렬된 키/값 쌍의 컬렉션을 나타냅니다.       |
|        Stack<T>         |                  	 LIFO(후입선출) 방식의 개체 컬렉션을 나타냅니다.                   |

</details>

<details>
<summary>디자인 패턴</summary>

* 생성 패턴
  * 팩토리 메서드 패턴
  * 추상 팩토리 패턴
  * 싱글톤 패턴
  * 빌더 패턴
  * 프로토타입 패턴
* 구조 패턴
  * 어댑터 패턴
  * 브릿지 패턴
  * 컴포지트 패턴
  * 데코레이터 패턴
  * 퍼사드 패턴
  * 플라이웨이트 패턴
  * 프록시 패턴
* 행동 패턴
  * 책임 연쇄 패턴
  * 커맨드 패턴
  * 인터프리터 패턴
  * 이터레이터 패턴
  * 미디에이터 패턴
  * 메멘토 패턴
  * 옵저버 패턴
  * 스테이트 패턴
  * 스트래티지 패턴
  * 템플릿메서드 패턴
  * 비지터 패턴
  
</details>

<details>
<summary>문법</summary>

* Generic 제네릭
  * class ClassName<T> where T : struct
  * class ClassName<T> where T : class
  * class ClassName<T> where T : new()
  * class ClassName<T> where T : ClassName
  * void FuncName<T>(T value)

* Virtual Class 가상 클래스
  * Interface
  * abstract

* Property 프로퍼티
  * (접근 제한자) (프로퍼티 명) { get; set; }
  * (접근 제한자) (프로퍼티 명) { get => (변수 명) set => (변수 명) = value }
  * 
* Delegate 대리자
  * delegate
  * Action (미리 선언 되어 있는 delegate void)
  * Func (미리 선언 되어 있는 delegate T)
  
* Event 이벤트
  * event (delegate) (이벤트 명)
  * event Action (이벤트 명)
  
* Lambda 람다
  * Equal((a,b) => a == b)

* Exception 예외 처리
  * try
  * catch(Exception e)
  * finally
  * throw new Exception()

* Reflection 리플렉션
  * GetType()
  * type.GetFields(BindingFlags)
  * Attribute
    * [Attribute]
    * class ClassName : Attribute
  * field.GetCustomAttributes()

* Nullable
  * (자료형)? (변수명)
  * (변수명).Value
  * int temp = (변수명) ?? 0;

</details>

### 유니티

<details>
<summary>Unity Package</summary>

* TextMeshPro
* Cinemachine
* Universal RP
* Shader Graph
* Visual Effect Graph
* Timeline
* ProBuilder
* Polybrush

</details>

<details>
<summary>테스트 자동화</summary>

* TestRunner
* ML-Agent

</details>

<details>
<summary>유용한 API</summary>

* [UniRx](https://github.com/neuecc/UniRx)
* [DOTween](http://dotween.demigiant.com/index.php)

</details>