# 복소수 진법 체계 기반 ALU 설계: 성능 평가 및 응용 방안

1960년 Donald Knuth가 처음 제안한 복소수 진법(An Imaginary Number System, DOI: [10.1145/367177.367233](https://doi.org/10.1145/367177.367233))은 복소수를 기수(Radix)로 사용하는 새로운 수 체계로, 기수로 어떤 복소수를 선택하느냐에 따라 숫자 집합과 표현법이 달라진다. 복소수 진법의 장점은 실수부와 허수부를 분리해 계산하지 않고 하나의 수로써 복소수 연산을 수행할 수 있다는 점이며, 이는 복소수 연산의 처리 속도 향상에 기여할 수 있다. 이후 연구에서는 다양한 기수를 탐구하면서 모든 복소수를 표현할 수 있는 체계를 확립하였고, 표현에 0과 1만을 사용하는 체계를 CBNS(Complex Binary Number System)로 정의하여 이진수와 유사한 표현을 갖게 되면서 컴퓨터 과학적 응용 가능성이 확대되었다. 본 논문은 국내에서 상대적으로 연구가 활발하지 않은 복소수 진법을 대상으로 수학적 이론을 정리하고, 복소수 연산에 특화된 ALU 설계 및 하드웨어 구현 방안을 제시한다. 설계한 ALU의 성능을 기존 방법과 비교·평가하고, 복소수 진법의 특성을 활용한 응용 사례들을 논의한다. 특히 특정 기수를 사용하는 복소수 진법에서 소수부를 복소평면에 나타냈을 때 생성되는 프랙털 구조를 영상 손실 압축 기법에 적용하는 가능성을 탐색한다.

**키워드:** 복소수 진법, 논리회로, ALU, 프랙털, 양자컴퓨팅, 영상 손실압축, AI

> 본 논문은 2025년 [한국계산과학공학회](http://www.cse.or.kr/) 추계학술대회 출품 논문이며, 해당 분야에 대한 국내 연구 활성화를 목적으로 국문으로 작성한 만큼 자유롭게 이용 가능함을 알랍니다.
> 
> This paper was submitted to the 2025 Fall Conference of the [Korean Society for Computational Science and Engineering](http://www.cse.or.kr/). It was written in Korean to promote research in this field within Korea and is freely available for use.
