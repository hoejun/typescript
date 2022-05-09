# typescript

doc
https://typescript-kr.github.io/

1. 버그 예방 : js의 버그 중 15% 예방
2. 더 나은 개발자 경험과 코드 퀄리티 향상 
3. 크로스브라우징(브라우저 호환성) 문제 해결 : 바벨 없어도 됨??

바벨을 사용해야 하는 이유
-바벨7 이전
TS > TS compiler > JS > Babel > JS 순서
웹팩은 두개의 컴파일러를 함께 사용하기 위해 사용된다. 

-바벨7 이후
바벨은 타입스크립트를 우선 js로 변경한다.
바벨 + 타입스크립트코드는 느린 컴파일 시간 개선
준비가 되었을 때만 타입 오류를 확인하라 ( js로 우선 안정성 검사 하지 않고 컴파일한 다음 코드 실험이 끝나고 타입 검사를 진행한다. )
TypeScript는 전체 프로젝트를 컴파일 하지만 Babel은 한번에 하나의 파일만 컴파일 한다.

1.설치
npx create-react-app my-app --template typescript
