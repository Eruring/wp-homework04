1. 과제 주제 설명

4주차에 배운 레이아웃 관련된 내용을 활용하여,웹페이지의 레이아웃을 잡아 본다.

2. 주요 코드 설명

전체 레이아웃
 전체 레이아웃을 container로 설정하여 창크기가 커져도 콘텐츠나 다른 레이아웃들의 크기를 고정시켰습니다. 

메뉴 부분

 flex를 사용하여 남은 부분에 콘텐츠를 정렬 시켰고 relative로 위치 상태 기준을 부모 div를 기준으로 하여 위치 좌표를 설정하였습니다. 아직 버튼을 누르면 어디로 이동을 할지 구현을 안했기 때문에 일단 임시로 버튼을 클릭하면 index로 다시 오게 해놨으며 폰트는 메인제목과 같이 나이대가 있는 등산모임 홈페이지 컨셉에 맞게 궁서체로 하였습니다.

메인제목 부분

 container레이아웃 안에 넣어서 선언을 하였지만 위의 메뉴 부분과 맞추기 위해 길이를 따로 설정을 해주고 메인 제목 안에 사진과 글귀를 넣었습니다. 가운데 정렬은 전체 (가로픽셀 - 대문글귀)/2로 픽셀을 계산하여서 픽셀로 가운데 정렬을 하였습니다. 

콘텐츠 부분

 사진 - 대문사진인 Gate_pic은 단순히 크기 조정만 해주었고 콘텐츠에 삽입이 되는 content_pic부분은 float:left을 통해 왼쪽으로 정렬을 해주었습니다. 

 텍스트 - 텍스트 레이아웃은 공지사항인 main_text와 금월 후원목록인 sub_text로 나뉘는데 1과 2의 비율을 픽셀단위로 조정하여 과제 레이아웃의 텍스트 비율을 맞추었습니다. 다만 content_text1은 위치 좌표를 설정을 해줘야 위의 메인 제목부분과 선이 맞기 때문에 메뉴부분처럼 relative을 주고 left를 10만큼 이동한 위치로 좌표를 주었습니다. 그리고 마지막 그림과 같이 있는 도차지차 부분은 pic2와 배열만 해주면 되기 때문에 따로 좌표는 주지 않았습니다. 


3. 비고 및 고찰

레이아웃의 틀도 주워지고 배운내용으로 하긴 하였지만 처음부터 레이아웃을 만든 것은 처음이라 처음에 어떻게 시작할지 정하는 것이 막막하여 제일 어려웠습니다. 
그리고 강의를 들으면서 이해를 했다고 생각을 하였지만 막상 해보니 position부분이 했갈려서 의외의 부분에 시간이 많이 소요가 되었고 상속 부분도 좀 햇갈렸습니다. 또한 정확히 가운데 정렬을 하고 싶은데 마지막에 Copyright는 margin auto로 정렬이 되었지만 제목부분은 같은 방법으로 하니 되지 않았습니다. 두부분다 container에 상속이 되어있는데 결과가 다른 이유를 모르겠어서 일단 픽셀 단위로 정렬을 해뒀지만 앞으로 업데이트할 과제에서는 이러한 찝찝한 부분을 해결하여 업데이트를 하고 싶습니다. 

4. 기타(선택 사항)

 - 여기에는 무엇을 써야할지 정확히 모르겠어서 일단 적지 않았습니다. 