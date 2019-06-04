# hekate - Bootlogo

bootlogo는 최대 크기가 720 x 1280 로 될 수 있습니다.

크기가 720 x 1280 보다 작으면 자동으로 중앙에 배치되고 배경이 첫 번째 픽셀의 색상을 사용합니다.

가로보기 부트 로그를 저장할 때 시계 반대 방향으로 90 도 회전해야합니다.

마지막으로, 지원되는 형식은 32 비트 (ARGB) BMP입니다. 클래식 24 비트 (BMP) BMP는 성능상의 이유로 지원되지 않습니다.


## 구성 방법

사용자 정의 로고 옵션을 사용하면 /bootlogo.bmp 를 로드하려고 시도합니다. 이것이 없으면 기본 hekate의 로고가 사용됩니다.

부트 항목이 사용자 정의 로고 경로를 지정하는 경우 부트 항목이 로드됩니다. 다시 이것이 발견되지 않으면 bootlogo.bmp가 로드되고 실패하면 hekate의 내장 기능이 사용됩니다.