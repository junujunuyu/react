# pofo
2023/01/12 만들어진 portfolio 반응형 디자인

2023/01/13 today 작업
1. 메뉴 상단의 header 부분의 각 메뉴당 하나씩 hover시에 contaier 넓이와 ul>li>a 안에 항목들의 넓이를 맞춰서 제작하였습니다.
2. section1 부분의 슬라이더가 자동으로 움직이게 설정하였습니다. mousehover시 슬라이더가 멈추도록 하였습니다. 반응형을 고려하여 제작하였습니다.
3. section2 부분의 img box와 text box로 나누어 작업하였습니다. 하단으로 스크롤 이동시 애니메이션 효과가 동작하도록 제작하였습니다. 

2023/01/16 today 작업
1. section3 부분의 text box으로 나누어 작업하였습니다. section2와 동일하게 하단으로 스크롤 이동시 애니메이션 효과가 동작하도록 제작하였습니다.

2. section3 부분의 각 li에 hover시에 화면전환 효과를 trasition 기능을 줘서 text,svg색깔을 흰색으로 바뀌게 하였습니다. 

3. section4 title 밑에 ul의 li(ALL,BROCHURE,BRANDING,IDENTITY,WEB,PHOTOGRAPHY)에게 애니메이션 효과를 줘서 gallery밑에 있는 img-wrap안에 있는 img의 그림 순서를 변경하게끔 만들었습니다.

4. section 3,4번 반응형을 고려하여 크기가 줄어들시에 flex-wrap: wrap과 flex-basis를 이용하여 크기가 줄어들시에 밑으로 항목들이 이동하게끔 작성하였습니다. 

2023/01/17 today 작업
1. footer 부분 작성 react 반응을 하기위해 간략하게 작성하였습니다.

2. 웹사이트에서 react추가하는 방식으로 react작업을 하였습니다.

3. script src="https://unpkg.com/react@18/umd/react.development.js" crossorigin>/script
   script src="https://unpkg.com/react-dom@18/umd/react-dom.development.js" crossorigin>/script
   위의 두 script는 웹사이트에서 react로 작업하기 위해 불러오는 script입니다.
   script src="https://unpkg.com/babel-standalone@6/babel.min.js">/script
   위의 babel은 script는 script 태그에서 type=text/babel 성질을 추가하면 JSX를 사용할 수 있습니다. 

4. rcc 형식을 사용하여 밑에처럼 양식을 만들어서 웹사이트 react를 구현한다 자세한 사항은 index1.html을 보면 알 수 있습니다. 
        class WrapComponent extends React.Component{
            render() {
                return (

                );
            }
        }