# FaceReader
눈의 모양을 잡아서 관상을 보여줍니다.
딥러닝 모델은 LeNet을 사용하였고, 학교 프로젝트로 제출하였습니다.

## Prerequisites
 * Pytorch
 * OpenCV
 * Python 2.7
 
## Data
`/Picture` 에 얼굴 사진을 넣으면   
`real/left`에 추출된 왼쪽 눈 사진이, `real1/right`에 추출된 오른쪽 눈이 저장되고, 결과가 txt 파일로 저장됩니다.

## Usage
test를 시킬 시에는 `python facereader1.py ./picture/____.jpg(input image path) 이름(사용자) output.txt(output file 이름)` 를 입려합니다.
