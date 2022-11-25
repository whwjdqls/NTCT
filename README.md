# NTCT
Neural Texture Color Transfer


Dataset 준비

- MS COCO
주소: https://cocodataset.org/#download
이미지만 받아오면 될듯 
(*근데 크롬에서 다운받으려니깐 안되고 edge 들어가서 다운 누르니깐 안전하지 않은 다운로드라고 뜨는데 무시하고 계속하면 다운로드 됨)

- WikiArt

주소: https://github.com/lucasdavid/wikiart
이거 git clone해서 다운받은 후 써있는거처럼 command 입력하면 자동으로 다운 받아짐


AdaIN 사용한건 아니지만 fast neural style transfer pytorch 구현한 github
https://github.com/rrmina/fast-neural-style-pytorch
이게 우리가 하려는것과 다른 점은 style을 미리 학습해야만 적용 가능하다? 아마도?
