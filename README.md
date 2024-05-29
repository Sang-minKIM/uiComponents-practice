# UI요소 만들기

인프런 정재남님의 [[React / VanillaJS] UI 요소 직접 만들기 ](https://www.inflearn.com/course/react-vanillajs-ui%EC%9A%94%EC%86%8C%EB%A7%8C%EB%93%A4%EA%B8%B0-part1) 강의를 기반으로 합니다.

## 디렉토리 구조

-   `app`: app 전반에 대한 기본 view 제공
    -   `[...item]/page.tsx`: `/[...item]` route의 page view. `routes`의 `key`에 매칭된 컴포넌트를 렌더링.
    -   `layout.tsx`: 기본적인 html 구성
    -   `page.tsx`: `/` route의 page view. `/README.md`를 보여줍니다.
    -   `global.scss`: app 전반의 style
    -   `gnb.tsx`: 좌측 메뉴 컴포넌트
-   `components`
    -   `vanillaWrapper.ts`: 독립적인 VanillaJS 환경의 wrapper 컴포넌트
-   `routes.ts`: route 구성
