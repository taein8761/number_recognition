주요 기능 설명

초기 설정 및 UI 그리기:
500x700 크기의 흰색 매트릭스(mat)를 생성합니다.
drawUI 함수는 검은색 테두리와 버튼을 그립니다.

마우스 이벤트 처리:
onMouse 함수는 마우스 클릭과 드래그를 처리합니다.
그림판 영역 내에서 마우스를 눌러서 그릴 수 있으며, 각 버튼을 클릭하면 해당 기능이 실행됩니다.

그림 그리기:
마우스 왼쪽 버튼을 누르고 이동하면 선을 그립니다.

이미지 저장 (Save):
사용자가 입력한 파일 이름으로 현재 이미지를 저장합니다.
검정색 테두리를 제외한 496x496 영역을 잘라내어 500x500 크기로 리사이즈한 후 저장합니다.

이미지 불러오기 (Load):
사용자가 입력한 파일 이름의 이미지를 불러옵니다.
불러온 이미지를 메인 매트릭스에 복사하고, UI를 다시 그립니다.

이미지 초기화 (Clear):
입력 창을 초기화하고 UI를 다시 그립니다.

프로그램 종료 (Exit):
프로그램을 종료합니다.

작동 원리
메인 함수:
프로그램을 실행하며 초기 매트릭스를 생성하고 UI를 그린 후 마우스 콜백을 설정합니다.

마우스 콜백 함수:
사용자의 마우스 입력을 처리하여 그림을 그리거나 버튼을 클릭하여 해당 기능을 실행합니다.

저장 기능:
그림판의 내용을 검정색 테두리를 제외하고 500x500 크기로 리사이즈하여 저장합니다.

불러오기 기능:
저장된 이미지를 불러와서 그림판에 표시하고, UI를 다시 그립니다.

초기화 기능:
그림판을 초기 상태로 되돌립니다.

종료 기능:
프로그램을 종료하고 모든 창을 닫습니다.
