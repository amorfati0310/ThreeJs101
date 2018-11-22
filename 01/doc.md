## three JS공부 01

사각형을 돌려보자

1. ThreeJS란?

- [webGL](https://developer.mozilla.org/ko/docs/Learn/WebGL)

먼저 WebGl이 뭔지 정도만 간단히 알아보자<br>
왜냐하면 ThreeJs가 결국 WebGl을 좀 편리하게 쓸 수 있게 만들어 준 라이브러리 !<br>

mdn을 살펴보면 webGL의 부모격인 기술인 OpenGL의 3D 그래픽을 통해서 그리고 여기에 빛이나 텍스쳐 그림자 등의 시각효과를 적용하기 위한 기술이라고 한다. <br>

WebGL은 + 그래픽 하드웨어인 GPU와 직접 통신할 수 있는 WebAPI<br>
GLSL이라는 작은 프로그래밍 언어를 함께 제공 <br>
이 GLSL을 통해서 GPU 계산 능력을 활용할 수 있다. <br>
2D/3D 그래픽스, 영상 처리, 절차적 텍스처, 지형 생성, 시각적 효과(반사, 굴절, 연기, 불, 유체),<br>
뿐만 아니라 그래픽스와 무관하지만 파워풀한 GPU를 활용한 일반 연산까지도 모두 WebGL에서 가능합니다.<br>

mdn따라 치며 개념 익히기넹 ...<br>

지금은 gpu 3d webAPI <br>
js canvas에 webGL context로 그릴 캔버스를 만들어 놓고 <br>
webGL API를 통해서 (GLSL)=> Shader Prgoram (Vertext Shader, Fragment Shader)=>GPU Rendering을 통해서 그린다 :D<br>

- Vertext Shader는 말 그대로 점의 위치를 계산 이를 통해서 기본 요소들을 rasterize한다고 한다.
- Fragment Shadr는 현재 그려져 있는 요소에 픽셀에 색상을 계싼
  요정도로만 알아두고

WebGL은 ... 좀 더 깊게 봐야 될 상황이 생기면 더 알아보기로 하고 이제 Three JS개념을 알아봅시다 <br>

## Reference

- [webGL_besideSoft](https://www.bsidesoft.com/?cat=50)
- [webGL_Study_Repo](https://github.com/hanmomhanda/WebGL-Study)
- [webGL_slideShare](https://www.slideshare.net/hanmomhanda/web-gl-42962918)

추후에 WebGL도 공부하면서 three JS 공부하기
