[신입/C#] 협업을 통해 성장한 개발자 이동규 입니다.
========================================


🔎 정보
------

- 2002년생 4급(키)
- [포토폴리오](https://drive.google.com/drive/folders/1l-CSpGe1R6aA_Kqtv_YR1_xi0fa0-tFl?usp=sharing)
- 이메일 : [korehdrb@gmail.com](korehdrb@gmail.com)
- [Unity Learn](https://learn.unity.com/u/6016cfc7edbc2a08db00c5b0?tab=profile)
- 코드 의도를 가지고 작성, 효율적인 팀프로젝트 진행 생각


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

### UnityWave

#### TRACK 1

<details>
<summary> 다양한 사례로 알아보는 유니티 프로젝트 최적화 </summary>

* CPU 비용 최적화
  * UGUI.Rendering.UpdateBatches() 문제 사례
    * 원인
      * Button의 좌표가 변경되면 모든 UI를 재배치 하기 떄문에 낭비되는 비용 발생
    * 해결 방법
      * 동적인 UI 요소는 Canvas를 따로 분리
  * GC Allocation 의한 히칭 문제 사례
    * 원인
      * child.name 참조시 GC.Alloc에 의한 메모리 할당 발생
    * 해결     
      * Player -> Incremental GC 활성화
    * Project Auditor를 통해 원인 찾기
* GPU 비용 최적화
  * 의도하지 않은 전체화면 렌더링 비용 문제 사례
    * Xcode Frame Debugger 에서 프로파일링
    * 원인
      * 원본 이미지의 사이즈가 실제 이미지보다 매우 큰 상황
    * 해결방법
      * 실제 사용 이미지 크기에 맞춰 사이즈를 줄임
* 메모리 & 에셋 비용 최적화
  * 에셋번들에서 파일에 중복해서 들어는 문제 사례
    * Memory Profiler에서 메모리 Capture하는 방법
      * Profiler 에서 Memory 탭 클릭한 상태에서 Open Memory Profiler 출력
    * 원인
      * 여러 개의 에셋번들이 에셋번들에 속하지 않은 에셋을 참조
    * 해결
      * 에셋 번들이 중복으로 참조하는 에셋을 미리 에셋번들로 만듬
  * GC Allocation에 의한 메모리 단편화 사례
    * 원인
      * 다양한 사이즈의 GC Alloc 할당/해제가 일어나면서 Managed Heap 공간에 할당할 수 없는 영역이 늘어남
    * 해결
      * Project Auditor를 통해 GC Alloc에 일어나는 위치를 찾아 코드를 수정하여 해결
* 정리
  * CPU
    * Unity Profiler를 통해 프레임 안에서 비용이 큰 원인 찾아서 제거
    * 정적 분석 도구 Project Auditor를 통해 확인된 코드를 점검하고 비용이 발생할 수 있는 부분 제거.
  * GPU
    * Native Profiler를 통해 전체화면으로 렌더링할 필요가 없는 오브젝트들을 찾고 사이즈를 조정하여 Fragment 렌더링 비용 줄임
  * 메모리 & 에셋
    * Memory Profiler를 통해 메모리 비용 점검 단편화 영역 커지지 않도록 원인을 찾아서 제거
    * 에셋 종속성에 따라 여러 개의 에셋 번들에 중복해서 포함되는 에셋을 점검하고 문제가 확인되면 수정
</details>

<!--
<details>
<summary> Gigaya 심층 분석: 몰입감 넘치는 월드 제작하기 </summary>



</details>

<details>
<summary> 승리의 여신: 니케 - 스파인 캐릭터 헤어&신체 물리 구현 </summary>



</details>

<details>
<summary> 블록체인 기술을 활용한 게임들과 NFT 적용 트렌드 </summary>



</details>

<details>
<summary> 유니티 데모 팀의 최신 플래그십 시네마틱 데모 “에너미즈(Enemies)” 제작 스토리 </summary>

</details>

-->
