# HW1

| 1-1 | 변수를 만들면 컴퓨터 안에서 공간이 만들어진다는 걸 확인 |

| 1-2 | 변수는 데이터를 직접 담지 않고, 데이터가 있는 위치를 기억함 |

| 1-3 | 숫자나 글자처럼 단순한 값은 바꿀 수 없는 값이라는 걸 알게 됨 |

| 1-4 | 복잡한 데이터는 같은 것을 가리켜도 값이 바뀔 수 있음 |

| 1-5 | 객체의 내용을 바꾸면, 가리키는 위치도 달라질 수 있음 |

| 1-6 | 객체 안에 또 다른 객체가 있으면, 서로 연결되어 있음 |

| 1-7 | 같은 객체를 복사하면 둘이 연결되어 있어서 하나만 바꿔도 같이 바뀜 |

| 1-8 | 복사한 객체를 바꾸면 원래 객체도 같이 바뀔 수 있다는 걸 경험 |

| 1-9 | 복사한 객체를 완전히 새로 만들면 원래와는 별개가 됨 |

| 1-10 | 얕은 복사를 하면 연결이 남아 있어서 문제가 생길 수 있음 |

| 1-11 | 아예 새 객체를 만들면 그런 문제를 피할 수 있음 |

| 1-12 | 얕은 복사를 직접 만드는 방법을 배움 |

| 1-13 | 직접 만든 복사 함수를 쓰면 원래 객체는 안 바뀜 |

| 1-14 | 복사할 때 안쪽 객체까지는 복사가 안 된다는 걸 확인 |

| 1-15 | 깊은 복사를 하면 안쪽 내용까지 다 복사됨 |

| 1-16 | 함수를 반복해서 불러서 깊은 복사를 만들 수 있음 |

| 1-17 | 깊은 복사를 하면 원래와 완전히 독립된 복사본이 생김 |

| 1-18 | JSON으로 복사하면 함수 같은 건 빠지게 됨 |

| 1-19 | 값이 없을 때 자동으로 undefined가 들어간다는 걸 확인 |

| 1-20 | 배열 안에서 undefined랑 비어 있는 칸은 다르다는 걸 확인 |

| 1-21 | 비어 있는 칸은 배열을 돌릴 때 건너뛰어진다는 걸 알게 됨 |

| 1-22 | null도 object로 보이는 오류가 있어서 정확히 비교해야 함 |


| 2-1 | 함수를 부르면 실행 순서가 쌓이고 내려가는 구조라는 걸 알게 됨 |

| 2-2 | 변수나 함수가 먼저 정리되고 나중에 실행된다는 걸 배움 |

| 2-3 | 함수의 매개변수도 변수처럼 먼저 만들어진다는 걸 확인 |

| 2-4 | 순서를 바꿔도 실행 결과는 똑같다는 걸 실험 |

| 2-5 | 코드를 보기 전에 결과를 예상해 보고 확인 |

| 2-6 | 실제 실행 결과와 예상이 맞는지 비교함 |

| 2-7 | 함수 선언 방식에 따라 동작이 달라질 수 있음 |

| 2-8 | 이름 없는 함수, 이름 있는 함수의 차이를 봄 |

| 2-9 | 어떤 함수는 정상 실행되지만, 어떤 건 오류가 나는 걸 봄 |

| 2-10 | 호이스팅 후 코드랑 원래 코드가 결과가 같음 |

| 2-11 | 같은 이름의 함수가 여러 개면 마지막 것이 실행됨 |

| 2-12 | 함수 표현식은 문제가 생기면 오류로 알려줌 |

| 2-13 | 함수 안에서는 바로 위에 있는 값을 먼저 찾는다는 걸 확인 |

| 2-14 | 개발자 도구에서 코드 흐름을 직접 볼 수 있었음 |

| 2-15 | 안쪽 함수에서도 바깥 변수를 볼 수 있다는 걸 알게 됨 |

| 2-16 | debugger를 사용해 함수 실행 과정을 확인해봄 |


| 3-1 | 브라우저에서는 this가 window랑 같다는 걸 알게 됨 |

| 3-2 | Node.js에서는 this가 global이라는 걸 확인 |

| 3-3 | 전역 변수도 this나 window로 접근할 수 있음 |

| 3-4 | 변수값을 바꾸고 접근해보며 어떻게 연결되는지 봄 |

| 3-5 | var로 만든 변수는 지우지 못하지만 직접 만든 건 지울 수 있음 |

| 3-6 | 일반 함수와 객체 안 함수는 this가 다르게 동작함 |

| 3-7 | 객체 안에서 this는 그 객체를 가리킴 |

| 3-8 | 대괄호로 불러도 this는 그대로 동작함 |

| 3-9 | 함수 안의 함수는 this가 전역을 가리킴 |

| 3-10 | self라는 변수를 써서 바깥 this를 기억해둠 |

| 3-11 | 화살표 함수는 바깥 this를 그대로 가져다 씀 |

| 3-12 | setTimeout과 forEach에서는 this가 달라질 수 있음 |

| 3-13 | 생성자 함수를 써서 객체를 만들 수 있다는 걸 봄 |

| 3-14 | call을 쓰면 this를 직접 지정해서 쓸 수 있음 |

| 3-15 | 다른 객체로 바꾸면 그 객체의 값이 this가 됨 |

| 3-16 | apply도 비슷하게 동작하지만 인자를 배열로 줌 |

| 3-17 | 배열 메서드를 객체에 적용해서 쓸 수도 있음 |

| 3-18 | 배열로 바꾸는 방법을 사용해서 여러 데이터를 다룸 |

| 3-19 | 문자열도 배열처럼 다룰 수 있지만 한계가 있다는 걸 봄 |

| 3-20 | 객체를 배열로 바꿔서 처리하는 방법을 확인 |

| 3-21 | 함수를 빌려서 다른 생성자처럼 쓸 수 있음 |

| 3-22 | 배열에서 큰 값, 작은 값을 찾는 방법을 배움 |

| 3-23 | Math 함수를 사용하면 쉽게 찾을 수 있음 |

| 3-24 | 전개 연산자(...)를 쓰면 더 간단해짐 |

| 3-25 | bind로 this와 인자를 고정한 함수를 만들 수 있음 |

| 3-26 | bind된 함수도 원래 이름은 그대로임 |

| 3-27 | call이나 bind로 this를 바꿔서 쓸 수 있음 |

| 3-28 | 비동기 함수 안에서 this가 달라지는 걸 조심해야 함 |

| 3-29 | 화살표 함수 안에서는 this가 바깥과 같음 |

| 3-30 | 여러 값을 더하고 평균을 구하는 예제 |

| 3-31 | 배열과 Set을 돌릴 때 함수가 어떻게 쓰이는지 배움 |

# HW2

| 4-1 | setInterval에 익명 함수를 직접 넘겨, 0.3초 간격으로 숫자를 0부터 출력함 |

| 4-2 | 익명 함수 대신 cbFunc라는 이름을 붙여서 setInterval에 전달함 |

| 4-3 | map 메서드에서 요소와 인덱스를 받아 출력하고, 각 값에 5를 더한 새 배열을 생성함 |

| 4-4 | map 메서드에 인자 순서를 잘못 넣으면 의도하지 않은 결과가 나오는 것을 확인함 |

| 4-5 | map 메서드를 직접 구현해서 내부적으로 어떻게 동작하는지를 이해함 |

| 4-6 | this의 동작 방식이 상황마다 다르다는 것을 setTimeout, forEach, 이벤트 리스너에서 비교함 |

| 4-7 | 객체의 메서드를 콜백으로 전달하면 this가 객체가 아닌 전역 객체를 참조하게 되는 문제를 확인함 |

| 4-8 | self = this 패턴을 사용해 클로저 안에서 this 값을 안전하게 유지하는 방법을 실습함 |

| 4-9 | self를 사용하지 않으면 콜백 내에서 this가 전역 객체로 바뀌어 문제가 발생함 |

| 4-10 | 메서드를 함수처럼 실행하면 this가 예상과 달라지며, call을 써도 this를 유지할 수 없음을 확인함 |

| 4-11 | bind를 사용하면 this가 바뀌지 않고 유지되어, 콜백에서도 원래 객체를 참조할 수 있게 됨 |

| 4-12 | 익명 콜백을 계속 중첩해서 쓰면 코드 들여쓰기가 깊어져 가독성이 떨어지는 문제를 체험함 |

| 4-13 | 콜백 지옥 문제를 함수 이름을 따로 정해서 구조화함으로써 해결함 |

| 4-14 | Promise를 사용해서 비동기 작업을 순차적으로 표현하고, 콜백보다 가독성이 좋아짐을 체감함 |

| 4-15 | 반복되는 Promise 코드를 함수로 분리해서 코드 중복을 줄이고 가독성을 높임 |

| 4-16 | Generator를 이용해 yield로 흐름을 멈추며 동기적으로 비동기 작업을 표현함 |

| 4-17 | async/await 문법으로 비동기 코드를 가장 깔끔하게 표현할 수 있음을 확인함 |

| 5-1 | 내부 함수가 외부 함수의 변수 a에 접근해서 값을 증가시키고 출력함 (기본적인 클로저 구조) |

| 5-2 | 내부 함수에서 외부 변수를 바꾸고 리턴값으로도 전달해서 값을 계속 유지시킴 |

| 5-3 | 외부 함수가 내부 함수를 리턴해서, 이후에도 외부 변수에 계속 접근 가능함 (클로저의 지속성 확인) |

| 5-4 | 즉시 실행 함수 안에서 setInterval과 버튼 클릭 이벤트가 클로저를 통해 각자의 상태를 유지함 |

| 5-5 | 클로저가 참조를 유지하는 한 메모리에 남아있고, null을 할당해 참조를 끊으면 해제되는 걸 실험함 |

| 5-6 | 리스트 항목마다 클릭했을 때 해당 과일 이름을 alert로 출력하도록 클로저를 활용함 |

| 5-7 | 반복문 안에서 동일한 함수가 실행되어 마지막 값만 뜨는 문제를 관찰하고, 클로저로 해결해야 함을 인식함 |

| 5-8 | bind를 사용해 각 클릭 이벤트마다 과일 이름을 고정해서 정확히 원하는 결과가 출력되게 함 |

| 5-9 | 클로저를 반환하는 함수를 만들어 각 과일 이름에 따라 별도의 알림 창을 띄우는 데 성공함 |

| 5-10 | car 객체의 run 메서드를 통해 연료 소모와 거리 누적을 구현했지만 외부에서 직접 접근이 가능했음 |

| 5-11 | createCar 함수를 만들어 연료, 연비, 이동거리를 클로저로 숨기고 run으로만 접근할 수 있도록 개선함 |

| 5-12 | 위의 createCar에서 Object.freeze를 추가해 외부에서 속성을 바꾸지 못하도록 막음 (보안성 향상) |

| 5-13 | bind를 사용해서 add 함수의 앞부분 인수를 고정하고, 뒤에 추가 인수를 받아 전체 합을 계산함 |

| 5-14 | partial 함수를 만들어 초기 인수를 고정한 함수를 생성하고, 이후 인수를 더해 결과를 반환함 |

| 5-15 | partial2에서는 _를 자리 표시자로 써서 인수 위치를 자유롭게 지정할 수 있게 함 |

| 5-16 | debounce 함수를 만들어 이벤트가 연속적으로 발생할 때 마지막 것만 실행되도록 조절함 |

| 5-17 | curry3 함수를 사용해서 인자를 하나씩 나눠 받고, 10과 비교해서 큰 값 또는 작은 값을 구함 |

| 5-18 | curry5 함수를 사용해서 5개의 인자를 하나씩 받아, 최종적으로 가장 큰 수를 반환하게 함 |

# HW3

| 6-1 | Person 생성자 함수로 이름을 저장하고 반환하는 기능을 구현함 |

| 6-2 | Constructor 함수와 프로토타입 메서드를 정의하고 객체를 생성함 |

| 6-3 | 기존 배열의 constructor를 이용하여 새 배열을 만들고 출력함 |

| 6-4 | 여러 데이터 타입의 constructor 속성을 변경하고 instanceof로 확인함 |

| 6-5 | 다양한 방법으로 Person 인스턴스를 만들고 instanceof로 검사함 |

| 6-6 | 인스턴스의 메서드를 재정의하여 메서드 오버라이딩 동작을 확인함 |

| 6-7 | 배열에 요소를 추가한 후 해당 속성이 직접 가진 것인지 확인함 |

| 6-8 | 배열의 toString 메서드를 재정의하여 커스텀 문자열을 반환함 |

| 6-9 | 객체에 getEntries 메서드를 추가하여 키-값 쌍 배열을 반환하게 함 |

| 6-10 | Grade 생성자 함수로 배열처럼 작동하는 객체를 정의하고 length도 설정함 |

| 7-1 | Rectangle 클래스에 넓이 계산과 인스턴스 검사를 위한 메서드를 정의함 |

| 7-2 | 배열처럼 동작하는 Grade 클래스를 정의하고 인스턴스를 초기화함 |

| 7-3 | Grade 인스턴스에서 length를 지운 후 배열 동작이 깨지는 것을 확인함 |

| 7-4 | Grade.prototype을 배열로 설정하고 push 시 length가 갱신되지 않는 점을 실험함 |

| 7-5 | Rectangle, Square 클래스를 만들고 각자의 넓이를 구하는 메서드를 추가함 |

| 7-6 | Square 클래스에서 속성을 중복 정의하여 마지막 값만 유지되는 구조를 실험함 |

| 7-7 | Rectangle을 상속받아 Square를 정의하고 넓이를 구하는 메서드를 상속함 |

| 7-8 | extendClass1 함수로 Square가 Rectangle을 상속하도록 구조화함 |

| 7-9 | 클로저와 Bridge 함수를 사용하여 상속 구조를 만드는 extendClass2를 정의함 |

| 7-10 | Object.create로 Rectangle의 프로토타입을 상속하여 Square의 구조를 구성함 |

| 7-11 | extendClass1에서 부모 메서드를 제거하고 자식 프로토타입을 동결함 |

| 7-12 | extendClass2 함수에서 Bridge와 클로저로 상속 구조를 설정하고 동결함 |

| 7-13 | extendClass3 함수에서 Object.create로 상속 구조를 만들고 동결함 |

| 7-14 | extendClass 함수에서 super 기능을 구현하고 메서드를 덮어쓰기함 |

| 7-15 | ES5와 ES6 방식의 클래스 정의 차이와 정적/인스턴스 메서드 사용을 비교함 |

| 7-16 | ES6 class 문법으로 Rectangle과 Square 클래스를 만들고 super로 상속을 구성함 |