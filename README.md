"# Graphics_Theory" 

그래픽스에 관련된 이론

Part1 - Bloom Effect & RayTracing (그래픽스 기본 원리)

    1) Bloom Effect
        - Pixel에 관련된 기본 배열에 관한 이론
        - 2D Image Processing의 기초 원리
        - Bloom Effect의 이해를 위해 가우시안 블러 효과 이론
        - 가우시안 블러 기반으로 Bloom Effect 적용하는 법

    2) RayTracing (광추적)
        a) Coordinate System - 좌표계 기초
        b) Vector 기초
        c) Raytracing의 기본 원리 - 3D 물체 렌더링 (Orthographic Projection  방식 사용 (정투영))
        d) Light Effect (빛 효과) 기초 - Phong Model
        e) Perspective Projection (원근 투영) - 3D World에서 원근감을 위해 사용
        f) Triangle (삼각형) - 삼각형과 Ray의 충돌 (그래픽스에서 거의 모든 물체들을 삼각형들로 그리기에 매우 중요하다.)
        g) Shadow (그림자) - 그림자를 그리는 원리
        h) Barycentric Coordinates(무게중심 좌표) - 무게중심좌표를 사용해 삼각형의 색을 정하거나 Texture를 입힐 때 사용
        i) Texturing (텍스처링) - 모델을 정교하게 만들어 렌더링 하는 대신 기본적인 물체를 생성해 Texture Image를 덧붙여 정교한 물체처럼 만든다.
        j) Reflection (빛 반사) - 빛을 반사하는 모델을 위한 원리
        k) Transparency & Refraction (투명동 & 빛의 굴절) - 투명한 물체들(유리, 물 등)을 렌더링하기 위한 원리